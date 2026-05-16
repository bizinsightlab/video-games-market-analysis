# Global Video Games Market & Consumer Trend Analysis

## Objective
The objective of this study was to analyze historical global video game sales data for the online store Ice. The commercial focus was to identify the core factors driving a product's success (leading consoles, popular genres, impact of critic/user reviews, and ESRB ratings) to forecast market trends and guide the strategic marketing planning for the upcoming year (2017).

## Key Results
The study demonstrated that consumer preferences are highly regionalized (e.g., Xbox leads in North America, while Nintendo handhelds dominate Japan). Action and Sports genres yield the highest aggregate sales volumes globally. Statistically, professional critic scores show a moderate positive correlation with sales, whereas user reviews show no linear impact on purchase decisions.

## Tools & Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **SciPy** (Statistical Tests for Comparing Means)

## What I Learned
- Manipulating and cleaning historical databases containing high volumes of structural missing data.
- Building regionalized consumer profiles using dynamic aggregations of revenue by geographic slices (NA, EU, JP).
- Applying statistical hypothesis testing to verify whether user satisfaction ratings vary between competing platforms (Xbox One vs. PC).

## Future Improvements
- Integrate recent market data to analyze consumer behavior trends following the complete industry shift toward digital-only sales.
- Build a baseline predictive model to estimate global sales of a game prior to launch based on early critic reviews.

---

## Methodology
1. **Data Cleansing:** Standardized columns, handled "TBD" (To Be Determined) entries, and cast appropriate data types.
2. **Lifecycle Analysis:** Calculated the average commercial lifespan and relevance window of gaming platforms.
3. **Regional Profiling:** Identified the top 5 platforms and genres across different continents.
4. **Hypothesis Testing:** Evaluated statistical significance in user scores across platforms and genres using probabilistic criteria.

## How to Run
1. Clone this repository.
2. Install the required dependencies: `pip install pandas numpy scipy matplotlib seaborn`
3. Open the notebook to review regional market shares and distribution plots.
