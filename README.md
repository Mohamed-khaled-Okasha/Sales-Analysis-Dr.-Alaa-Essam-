# Sales Data Analysis (2022-2024) - Ramadan Data Analysis Competition

## Project Overview  
This project was developed as part of the **Ramadan Data Analysis Competition** under the guidance of **Dr. Alaa Essam**. The goal was to analyze sales data for the years 2022, 2023, and 2024 using Power BI, uncovering insights into revenue trends, segment performance, regional contributions, and channel effectiveness to support data-driven decisions.

## Objectives  
- Analyze sales performance across 2022, 2023, and 2024.  
- Identify key trends in revenue, discounts, and product diversity.  
- Evaluate performance by segment, region, and channel.  
- Provide actionable recommendations to improve future sales.

## Data Overview  
- **Source:** Sales data for 2022, 2023, and 2024.  
- **Details:** Includes revenue after discount, discounts, quantities, products, channels (e.g., Retail, Online), regions (e.g., Northeast, Pacific), and segments (e.g., Business, Consumer).  
- **Structure:** Separate tables for each year (`2022`, `2023`, `2024`) with supporting tables for products, channels, and regions.  
- **Scale:** Revenue in millions (e.g., 2024 revenue = 47M).

## Tools Used  
- **Power BI:** For data modeling, visualization, and analysis.  
- **DAX:** For creating measures like `Total Revenue`, `Total Discount`, and `Top Channel by Revenue`.  
- **Power Query:** For data cleaning and transformation.  
- **CapCut:** For merging dashboard and presentation videos.

## Key Steps  

### 1. Data Preparation  
- Created a `Years` table using DAX to link sales data across years.  
- Extracted `Year` and `Month` columns from `order date` in each table (`2022`, `2023`, `2024`) using Power Query.  
- Converted `product id` to Text to prevent aggregation errors.  
- Established relationships between `Years` and yearly tables for dynamic filtering.

### 2. Data Cleaning  
- Ensured consistent date formats in `order date` columns (e.g., MM/DD/YYYY).  
- Removed errors and invalid entries in date and revenue columns.  
- Extracted `Year` and `Month` for monthly sales tracking.

### 3. DAX Measures  
- Created measures for revenue analysis:  
  - `Total Revenue 2022`, `Total Revenue 2023`, `Total Revenue 2024`.  
  - `Total Revenue` (dynamic based on selected year).  
- Calculated discounts, order counts, and segment performance:  
  - `Total Discount`, `Percentage of Orders with Discount`.  
  - `Sales by Segment`, `Sales by Region`, `Top Channel by Revenue`.

### 4. Visualizations  
- **Gauge:** Compared 2024 revenue (47M) to target (50M), showing a 6% shortfall.  
- **Line Chart:** Tracked monthly revenue trends across years.  
- **Clustered Bar Chart:** Analyzed sales by segment (Consumer vs. Business) and region (e.g., Northeast, Pacific).  
- **Cards:** Displayed key metrics like `Distinct Product Count` and `Top Channel by Revenue`.

### 5. Insights & Recommendations  
- **Insights:**  
  - 2024 revenue missed the target by 6%.  
  - Consumer segment outperformed Business; Retail was the top channel.  
  - Northeast and Pacific led in regional sales.  
- **Recommendations:**  
  - Focus on Consumer segment and Retail channel for growth.  
  - Optimize discounts to improve profitability.  
  - Invest in high-performing regions like Northeast.

## Deliverables  
- **Power BI Dashboard:** Interactive visuals showcasing revenue trends, segment performance, and regional analysis.  
  [[Watch the Dashboard Walkthrough Video](link-to-video)](https://github.com/Mohamed-khaled-Okasha/Sales-Analysis-Dr.-Alaa-Essam-/blob/main/Dashboard%20Video.mp4)  
- **Presentation:** Summarizes the analysis, insights, and recommendations.  
  [[Watch the Presentation Video](link-to-video)](https://github.com/Mohamed-khaled-Okasha/Sales-Analysis-Dr.-Alaa-Essam-/blob/main/presentation%20video.mp4)
  
## How to Use  
1. Clone the repository:  
   ```bash  
   [git clone https://github.com/your-username/sales-data-analysis.git  ](https://github.com/Mohamed-khaled-Okasha/Sales-Analysis-Dr.-Alaa-Essam-)
   ```  
2. Open the `.pbix` file in Power BI Desktop to explore the dashboard.  
3. Watch the videos for a detailed walkthrough of the analysis and findings.

## Acknowledgments  
- Special thanks to **Dr. Alaa Essam** for her guidance during the Ramadan Data Analysis Competition.  
- Grateful for the opportunity to participate and enhance my data analysis skills.

## Contact  
Feel free to reach out for questions or feedback:  
- LinkedIn: www.linkedin.com/in/mohamed-okasha-715b8a280 
- Email: mkashh770@gmail.com

