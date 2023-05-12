# Top-10-Startup-Unicorn-Companies-in-the-World-by-their-Industries

![image](https://github.com/olajumokeabe/Top-10-Startup-Unicorn-Companies-in-the-World-by-their-Industries/assets/125363157/01a72b3c-75ad-4d18-bb92-ed0430e16ef1)


# INTRODUCTION

A unicorn is an animal so rare that some will even argue it’s mythical and not real, no wonder it is used to represent the rarity of privately held startup companies valued at over US$1 billion. The term unicorn company was first published in 2013, coined by venture capitalist Aileen Lee. A unicorn startup is a company that’s been in business for under ten years, isn’t publicly listed, haven’t been acquired by a third party, and become valued at 1 billion dollars or more worldwide.

These analyses offers insightful information about the top 10 unicorn startup companies in the world based on their industry.

# Data Requirement

I intend to answer the following business questions through this analysis;

1. Which unicorn companies have had the biggest return on investment?

2. How long does it usually take for a company to become a unicorn? Has it always been this way?

3. Which countries have the most unicorns?

4. Are there any cities that appear to be industry hubs?

5. Which investors have funded the most unicorns?

# Data Collection

The data was downloaded from Maven Analytics, containing just a table consisting 1073 rows and 10 columns of data. The columns of the datasets are outlined below:

![image](https://github.com/olajumokeabe/Top-10-Startup-Unicorn-Companies-in-the-World-by-their-Industries/assets/125363157/ccced368-f127-4458-af15-03c54edc2602)

Primary key is a column in a table that uniquely identifies the rows in that table and in the case of this dataset, the company name can be identified as primary key.

# Data Cleaning and Transformation

The dataset was loaded to power query in Power BI for cleaning. Data cleaning is a very crucial aspect in data analysis as it ensures accuracy and credibility of the insights generated from the data.

Under this step, I took into consideration of the following, the data types, null values, duplicates, and incorrect spellings.

Using the column quality feature on Power Query, I was able to identify that there were no errors in each column, however, there was a missing value which I simply classified as ‘Undefined’. Also, I checked and removed the duplicates using the column distribution such that I had an equal amount of distinct and unique data under my primary key (Company’s Name).

![image](https://github.com/olajumokeabe/Top-10-Startup-Unicorn-Companies-in-the-World-by-their-Industries/assets/125363157/8f00ce4e-bae6-42c6-8806-492fa0c8cbe9)

I also split the ‘select investors’ column using the split by delimiter function and renamed the columns main investor and other investors. I realised some company has just one investor and the value for the other investors became null, this I replaced with Unknown.

![image](https://github.com/olajumokeabe/Top-10-Startup-Unicorn-Companies-in-the-World-by-their-Industries/assets/125363157/d2951686-d008-473a-a03d-aca8386c6ac6)

![image](https://github.com/olajumokeabe/Top-10-Startup-Unicorn-Companies-in-the-World-by-their-Industries/assets/125363157/6b1d6ffc-63e3-4b0b-acd8-aaab63944bbe)


At the end of this process, the Unicorn_companies table contains 1073 rows and 13 columns. Now the data is ready for exploratory analysis.

# Exploratory Data Analysis and Visualization

In this chapter, I answered the questions in the data requirement gathering process.

I displayed a quick summary of the data which will reveal some Key Performance Indicators (KPIs) .

![image](https://github.com/olajumokeabe/Top-10-Startup-Unicorn-Companies-in-the-World-by-their-Industries/assets/125363157/ce46d5cc-1ab9-4d2f-a03d-ed8393f716ac)

![image](https://github.com/olajumokeabe/Top-10-Startup-Unicorn-Companies-in-the-World-by-their-Industries/assets/125363157/372ce544-aade-4569-88ed-b77aa8ee459f)

![image](https://github.com/olajumokeabe/Top-10-Startup-Unicorn-Companies-in-the-World-by-their-Industries/assets/125363157/0f48a075-410f-4d41-9e14-9cb4bf56baa9)

Bytedance was valued at 180 billions of Dollars as at 2021 making it the biggest unicorn company. Its funding amount at startup year in 2012 was 8 billions of Dollars, it reached its unicorn status in year 2017.

![image](https://github.com/olajumokeabe/Top-10-Startup-Unicorn-Companies-in-the-World-by-their-Industries/assets/125363157/e2d3b754-cd11-4376-95e1-8911fed756af)


Bytedance is an Artificial Intelligence company located in Beijing — China, with its main investor being Sequioa Capital China, and other investors include SIG Asia Investments, Sina Weibo, Softbank Group.

SpaceX and Shein are both valued at a 100 billion dollars. SpaceX startup was 7 billion in the year 2002 and attained unicorn in 2012, 10 years after it was first founded. SpaceX is located in Hawthorne — United States with it main investor being Founder Fund and others are Draper Fisher Jurvetson and Rothenberg Ventures.

However, Shein startup was 2 billion in the year 2008 and attained unicorn at 2018, another 10 years interval. Located in Shenzhen — China and focuses mainly on E-commerce, it has Tiger Global Management as its main investor and Sequoia Capital China and Shunwei Capital Partners as other investors.

Stripe is a Fintech company located in San Fransisco — United State valued at 95 billion in the year 2021. Its startup was 2 billion in 2010 when it was first founded and became Unicorn in the year 2014.

![image](https://github.com/olajumokeabe/Top-10-Startup-Unicorn-Companies-in-the-World-by-their-Industries/assets/125363157/2c90cf57-8f27-45b9-a537-187d3f2b010a)

It takes about six years on the average to become a unicorn company, however, in recent times there seems to be a decrease in the year it takes from start up to become unicorn, as some became unicorn company with a time frame of from three years.

The number of unicorn companies peaked by the year 2021. These countries were founded between the years 1984 to 2021 with about 21 companies founded in the year 2020 and 6 companies founded in the year 2021.

![image](https://github.com/olajumokeabe/Top-10-Startup-Unicorn-Companies-in-the-World-by-their-Industries/assets/125363157/57bdb790-10ac-40ed-b9cc-1ba1dd4a68d5)

The United States of America is the country with the highest company with 561 companies in the country. San Fransisco, a city in the United States of America, has the highest number of industries with count of industries at 151 and 13 distinct industries. New York with 103 industries and also 13 distinct industries, Beijing with 63 industries and 12 distinct, Shanghai with 44 and 11 distinct industries and then London with 34 industries and 9 distinct.

![image](https://github.com/olajumokeabe/Top-10-Startup-Unicorn-Companies-in-the-World-by-their-Industries/assets/125363157/a6d28483-36d3-4244-85d7-76368e00a0a2)

Sequoia Capital is the biggest investors for most of the companies with it being the main investors for about 50 companies, and also falls under the category of other investors.


# Conclusion

. There are several industries with a significant number of unicorn companies, including e-commerce, transportation, and fintech.
. The top unicorn companies in the world are dominated by American and Chinese companies, with only a few other countries represented.
. Some of the notable unicorn companies in the e-commerce industry include Alibaba, Amazon, and JD.com, while in the transportation industry, Uber and Didi Chuxing are leading players.
. Fintech unicorns like Stripe, Square, and Robinhood are disrupting traditional financial services with innovative digital solutions.
. The Covid-19 pandemic has accelerated the growth of some unicorn companies, particularly those in the e-commerce and healthcare industries.
. The unicorn landscape is constantly evolving, with new companies reaching unicorn status and established companies facing challenges to maintain their valuations.
. Some startups take a long time before achieving its milestone, with proper investigation, management and funding, your startup may as well be on its way to achieving a new status.

# Link to interactive dashboard on novypro: https://www.novypro.com/project/portfolio-8
