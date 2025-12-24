#  Amazon Sales Analysis Dashboard

A comprehensive Power BI dashboard analyzing Amazon's global sales performance, customer profitability, product performance, and market distribution across multiple regions and segments.

##  Project Overview

This Power BI project provides deep insights into Amazon's sales ecosystem, enabling data-driven decision-making through:
- Multi-year sales trend analysis (2012-2015)
- Geographic sales distribution with interactive maps
- Customer profitability analysis
- Product performance tracking
- Market and segment-wise revenue breakdown
- Loss and profit identification by products

##  Key Metrics & KPIs

| Metric | Value | Description |
|--------|-------|-------------|
| **Sales Projection** | $4.30M | Forecasted sales target |
| **Product Quantity** | 3,418 | Total products sold |
| **KPI Score** | 61K | Key Performance Indicator |
| **Return Count** | 371 | Total product returns |

##  Dashboard Components

### 1. **Year-Wise Sales Filter**
- Interactive year selector (2012-2015)
- Enables temporal analysis of sales trends
- Currently showing 2015 data

### 2. **Sales By Segment** 
- **Consumer**: $2.14M (49.8%) - Largest segment
- **Corporate**: $1.29M (30.08%) - B2B sales
- **Home Office**: $0.87M (20.12%) - Small business segment

### 3. **Sales By Market**
- **Asia Pacific**: $1.37M (31.93%) - Highest performing market
- **Europe**: $1.18M (27.45%) - Second largest market
- **USCA**: $0.76M (17.61%) - North American market
- **LATAM**: $0.71M (16.43%) - Latin American market
- **Africa**: $0.28M (6.58%) - Emerging market

### 4. **Sum of Sales by Region** (Interactive Map)
- Bubble map visualization showing sales concentration
- Size of bubbles represents sales volume
- Covers all continents with detailed city-level data
- Interactive hover functionality for detailed metrics

### 5. **Profit By Customer Name**
Top 10 most profitable customers:
- Ray Buch: $7.4K
- Jane Waco: $5.7K
- Tom Ashbrook: $5.4K
- Bill Eplett: $5.3K
- Hunter Lopez: $5.2K
- Patrick Jones: $3.8K
- Rick Wilson: $3.5K
- Gary Zandusky: $3.2K
- Dave Kipp: $3.2K
- Alan Hwang: $3.1K

### 6. **Loss By Product Name**
Products with highest losses:
- Bevis Comp...: -$2.0K
- Lexmark MX...: -$2.7K
- Barricks Con...: -$2.8K
- Ibico EPK-21...: -$2.9K
- Cubify Cube...: -$3.8K

### 7. **Profit By Product Name**
Top performing products:
- Canon ima...: $16K (Best seller)
- Cisco Smart...: $7K
- Motorola S...: $6K
- Hoover Sto...: $5K
- Sauder Clas...: $5K

##  Technical Stack

- **Visualization Tool**: Microsoft Power BI Desktop
- **Data Processing**: Power Query
- **Calculations**: DAX (Data Analysis Expressions)
- **Map Visualization**: Bing Maps integration
- **Data Source**: Excel/CSV files
- **Design**: Custom theme with blue gradient background

##  Project Structure
```
Amazon-Sales-Analysis/
│
├── Amazon-Sales-Dashboard.pbix    # Main Power BI file
├── data/                          # Data files
│   ├── sales_data.csv
│   ├── customers.csv
│   └── products.csv
├── screenshots/                   # Dashboard images
│   ├── screenshot.png
│   └── detailed_views/
├── documentation/                 # Additional docs
│   └── data_dictionary.md
└── README.md                      # Project documentation
```

##  Data Schema

### Sales Data
- Order ID, Order Date, Ship Date
- Customer ID, Customer Name
- Product ID, Product Name, Category
- Sales Amount, Quantity, Discount
- Profit, Region, Market, Segment

### Customer Data
- Customer ID, Name, Segment
- Region, Country, City
- Customer Since Date

### Product Data
- Product ID, Name, Category, Sub-Category
- Unit Price, Cost Price
- Supplier Information

##  Key Business Insights

### Market Analysis
1. **Asia Pacific Dominance**: APAC contributes 32% of total revenue, indicating strong market presence
2. **Consumer Segment Leading**: Consumer segment generates nearly 50% of total sales
3. **Top Customer Value**: Ray Buch generates $7.4K in profit, highlighting importance of key accounts

### Product Performance
1. **Canon Products Excel**: Canon imaging products lead with $16K profit
2. **Loss-Making Products**: 5 products showing significant losses need attention
3. **Tech Products Win**: Cisco, Motorola, and Canon dominate profitable products

### Geographic Insights
1. **Global Presence**: Sales spanning 5 major regions across all continents
2. **Regional Distribution**: Relatively balanced sales across regions (except Africa at 6.58%)
3. **Growth Opportunities**: Africa and LATAM show potential for expansion

### Customer Behavior
1. **Customer Concentration**: Top 10 customers contribute significant profit
2. **Retention Strategy**: High-value customers need focused account management
3. **Diversification Needed**: Reducing dependency on top customers

##  Future Enhancements

- [ ] Add predictive analytics for sales forecasting
- [ ] Include customer lifetime value (CLV) calculations
- [ ] Integrate inventory management metrics
- [ ] Add competitive analysis benchmarks
- [ ] Include supplier performance metrics
- [ ] Create mobile-optimized layout
- [ ] Add drill-through pages for detailed analysis
- [ ] Implement RLS (Row-Level Security) for multi-user access
- [ ] Add AI-powered insights and anomaly detection
- [ ] Create automated email reports

