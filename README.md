# Assignment-Victoria-solution

Project name: Data Cleaning, Analysis, and Business Insights

1. Remove Duplicates
Remove Duplicates: No exact duplicates found in the dataset
The dataset had 8 rows, and no exact duplicates were found, so all rows were retained.
2. Fill Missing Values (IF/ISBLANK equivalent)
Fill Missing Values:
Email: 2 missing values filled with 'Unknown'
Phone: 2 missing values filled with 'Unknown'
Discount (%): 2 missing values filled with 0
3. Standardize Dates (TEXT formula equivalent)


FEEDBACK FROM VICTORIA SOLUTIONS:
Dear Asaduzzaman,

Thank you for submitting your Week 2 project on Data Cleaning, Analysis, and Business Insights. I have carefully reviewed your report and would like to provide very detailed feedback. This feedback is designed to highlight what you did well and give you concrete suggestions to further strengthen your analysis and presentation.

1. Data Cleaning & Preprocessing
Strengths:

You clearly documented your cleaning steps: checking for duplicates, handling missing values, and standardizing dates.

It was good that you explicitly reported “no duplicates found” — this shows you validated the dataset rather than assuming.

Filling missing emails and phone numbers with "Unknown" is a consistent and professional placeholder strategy.

You converted all dates to a standardized format (YYYY-MM-DD) with clear before-and-after examples, which was excellent for transparency.

Final dataset summary (8 rows, clean and standardized) demonstrates completeness.

Suggestions for Improvement:

For missing discounts, you filled them with 0. While this is acceptable, it may mislead interpretation — since 0% discount is not the same as “unknown”. A short note explaining why you chose 0 (e.g., to simplify calculations) would strengthen your justification.

Instead of "Unknown" for phone numbers, "Not Provided" or "N/A" may be preferable to avoid confusion with text fields during future validation.

Adding a before-and-after data sample (e.g., one row showing missing email → “Unknown”) would help non-technical readers visualize the cleaning impact.

2. Sales Trend Analysis
Strengths:

You quantified revenue contribution by category with precise percentages:

Electronics: 47.37% ($5,400)

Furniture: 37.72% ($4,300)

Clothing: 14.91% ($1,700)

You went beyond raw totals by comparing category revenue shares against order volumes and average order values — very good analysis depth.

Highlighting Clothing’s lowest average order value shows you’re linking numbers to business implications.

Suggestions for Improvement:

While your percentages were accurate, adding a visual (pie chart or stacked bar) would make category comparisons clearer for stakeholders.

You noted that Electronics dominated, but you could explore why (e.g., higher discount sensitivity, stronger seasonal peaks).

It would add depth to compare Clothing’s low order value against discount strategies (since Clothing received minimal discounts).

3. Discount Effectiveness Analysis
Strengths:

You clearly compared discount averages by category:

Furniture: 20% average discount, still strong revenue.

Electronics: 13.33% average discount, excellent performance.

Clothing: 1.67% discount, lowest revenue.

The observation that higher discounts correlated with higher revenue was accurate and in line with the scatter plot evidence.

Calculating the overall average discount (10.62%) added useful context.

Suggestions for Improvement:

Your correlation coefficient (0.826) was excellent. To make it even more compelling, include the scatter plot with regression line and R² value in the report.

Consider testing for non-linearity — sometimes discounts show diminishing returns beyond a certain point. Noting this would strengthen your business insights.

Linking this analysis back to profitability (e.g., “while discounts drive revenue, margin impact must be considered”) would make your insights more strategic.

4. Monthly Sales Trends
Strengths:

You highlighted January 2024 as the peak month ($3,500 revenue), with a strong 45.83% growth from December 2023.

Noting the volatility (e.g., -52% in March, +50% recovery in April) shows good attention to trends beyond single-month peaks.

The heatmap interpretation (Electronics in Dec/Jan, Furniture in Feb/Apr, Clothing in Jan/Mar) was spot on.

Suggestions for Improvement:

Including the actual line chart and heatmap screenshots would make this section far more powerful. Visuals are critical in communicating seasonality.

You described growth/decline percentages well, but adding a table of monthly revenues would make it easier for stakeholders to follow.

A short interpretation of seasonality (e.g., holiday shopping in December, New Year spikes in January, spring recovery in April) would make your analysis more business-oriented.

5. Distribution Analysis
Strengths:

You provided all key statistics: mean ($1,425), median ($1,200), SD ($934.65), and range ($500–$3,000).

Identifying Electronics as the highest average revenue per order ($1,800) and Furniture as consistent with less variation showed a good balance of descriptive and interpretive analysis.

The conclusion that order sizes were diverse was valid and important.

Suggestions for Improvement:

Your histogram description was good, but including bin counts (e.g., “4 orders under $1,000, 2 orders between $1,000–$2,000”) would make it clearer.

Add a box plot or explicitly mention outliers (if any), since the range was wide.

Relating distribution back to marketing strategy (e.g., “most customers buy in the $500–$1,000 range, suggesting bundle offers could lift them into higher-value tiers”) would strengthen the recommendation link.

6. Insights & Recommendations
Strengths:

You connected insights to business action well:

Electronics and Furniture should be prioritized.

Discounts are effective when applied strategically.

Volatility and seasonal peaks require campaign alignment.

The link between Clothing’s low discounts and poor performance was an important takeaway.

Suggestions for Improvement:

Add a revival strategy for Clothing — e.g., bundle with high-performing categories, targeted flash sales, or loyalty incentives.

Quantify recommendations: e.g., “increasing Clothing discounts to 10% could potentially lift revenue by X%.”

Suggest inventory planning tied to seasonal trends (e.g., “boost Electronics stock before December/January”).

7. Formatting & Guidelines
Strengths:

The report was clear, professional, and well-structured.

Word count per section (100–150 words) was appropriate.

You adhered to project formatting rules (PDF submission, professional tone).

Suggestions for Improvement:

Start with a short executive summary (top 3 findings + recommendations) for business readers.

Use bullet points for recommendations to improve clarity.

Always embed actual charts/screenshots rather than relying on text descriptions.

Overall Evaluation
Understanding: Excellent — you demonstrated clear knowledge of data cleaning, summarization, and trend analysis.

Application: Very good — applied calculations and correlation analysis correctly, though more visuals would improve impact.

Clarity: Strong — well-structured, but could use tables/visuals for quicker comprehension.

Creativity: Good — identified strategic implications, but could expand Clothing strategy further.

Completeness: High — all deliverables covered, with only presentation and minor strategic depth improvements needed.

✅ Final Score: Pass with Merit/High Merit

Asaduzzaman, this was a strong submission that demonstrated technical skill and business awareness. To push your work to “Distinction” level, focus on embedding visuals, quantifying your recommendations, and expanding strategies for underperforming categories like Clothing. Overall, very well done — you’re progressing strongly, and your ability to balance analysis with insights is clearly improving.

Best regards,
Sophie
Victoria Solutions
