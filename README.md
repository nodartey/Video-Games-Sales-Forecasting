# Video-Games-Sales-Forecasting
Analyzed historical video game sales data to identify key success factors and forecast top-performing games for 2017. Explored trends in platforms, genres, and reviews, performed regional analysis, and tested hypotheses to guide strategic marketing decisions.
This project explores historical video game sales data to uncover patterns that drive commercial success. As a data analyst at Ice, a global online game retailer, the goal was to identify top-performing platforms, genres, and review factors to forecast 2017's potential hits and support marketing decisions.

##  Dataset

- **Source:** Provided dataset (`games.csv`)
- **Columns:** Name, Platform, Year of Release, Genre, Regional Sales (NA, EU, JP, Other), Critic Score, User Score, ESRB Rating
- **Note:** Some 2016 data may be incomplete.

##  Project Steps

1. **Data Preprocessing**
   - Cleaned column names and handled missing values
   - Converted data types and calculated total global sales
2. **Exploratory Data Analysis**
   - Analyzed sales by year, platform lifecycle, and genre trends
   - Identified leading and declining platforms
3. **Regional User Profiling**
   - Found top platforms and genres by region (NA, EU, JP)
   - Assessed the impact of ESRB ratings on regional sales
4. **Hypothesis Testing**
   - Compared average user ratings across platforms and genres using statistical tests
5. **Conclusion**
   - Summarized findings to support 2017 campaign strategy

##  Tools & Libraries

- `pandas`
- `matplotlib`
- `seaborn`
- `scipy.stats`

##  Key Insights

- Certain platforms dominate specific regions.
- User and critic reviews show moderate correlation with sales.
- Genre preferences vary widely by region.
- ESRB ratings influence sales more in NA and EU than in JP.

