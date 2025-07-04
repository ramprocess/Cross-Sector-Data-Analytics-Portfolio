# HHS Contract Awards Analysis (FY 2023)

## Table of Contents
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [What Was Done](#what-was-done)
- [Results](#results)
- [Business Impact & Recommendations](#business-impact--recommendations)
- [Future Improvements](#future-improvements)
- [Technical Implementation](#technical-implementation)
- [Files in Repository](#files-in-repository)

---

## Project Overview
Comprehensive analysis of $514 billion in U.S. Department of Health and Human Services contract awards for fiscal year 2023. This project examines federal healthcare spending patterns, contractor concentration, geographic distribution, and industry sector allocation to provide transparency into public health investments and procurement processes.

## Objectives
- Analyze federal healthcare spending patterns and contractor concentration
- Identify top recipients and awarding agencies in HHS procurement
- Map geographic distribution of contract awards across states
- Examine industry sector funding priorities and business size allocation
- Track spending trends over time to identify patterns and anomalies
- Provide transparency into federal health spending for stakeholders

## What Was Done

### Data Processing
- Processed comprehensive HHS contract dataset (FY2023_075_Contracts_Full_20250611_1.csv, 163 MB)
- Cleaned and standardized 71,587 contract records from USAspending.gov
- Filled missing values in current_total_value_of_award with 0 for accurate calculations
- Handled 7,257 contracts with missing end dates (10% of total records)
- Validated geographic data and flagged records with missing state/country information

### Analysis Methodology
- **Contractor Analysis**: Aggregated contract values by recipient to identify top performers
- **Agency Breakdown**: Analyzed spending patterns across HHS sub-agencies
- **Geographic Distribution**: Mapped contract awards by state and region
- **Industry Sector Analysis**: Examined funding by NAICS codes and service categories
- **Temporal Analysis**: Tracked spending trends from 1999-2023 using performance start dates
- **Business Size Analysis**: Compared large business vs. small business contract allocation

### Key Techniques
- Financial aggregation and ranking analysis
- Geographic mapping and regional concentration studies
- Industry sector categorization using NAICS codes
- Time series analysis for trend identification
- Comparative analysis between business sizes and competition types

![HHS Contract Distribution](images/hhs-contract-overview.png)
*Overview of $514 billion HHS contract distribution across top recipients and agencies*

## Results

### Top Contract Recipients
**Highest Value Recipients (FY 2023):**
1. **Leidos Biomedical Research Inc.**: $40.9 billion (8.0% of total)
2. **Noridian Healthcare Solutions, LLC**: $23.7 billion (4.6% of total)
3. **Northrop Grumman Systems Corporation**: $19.1 billion (3.7% of total)
4. **Palmetto GBA, LLC**: $18.1 billion (3.5% of total)
5. **Rapid Deployment Inc.**: $17.5 billion (3.4% of total)
6. **Novitas Solutions, Inc.**: $17.4 billion (3.4% of total)
7. **General Dynamics Information Technology, Inc.**: $17.2 billion (3.4% of total)
8. **National Government Services, Inc.**: $16.0 billion (3.1% of total)
9. **CGS Administrators, LLC**: $14.7 billion (2.9% of total)
10. **Leidos, Inc.**: $12.1 billion (2.4% of total)

**Key Finding**: Top 10 recipients captured $196.8 billion (38.3% of total funding), showing high concentration

### Agency Spending Patterns
**Top Awarding Agencies by Contract Value:**
1. **Centers for Medicare and Medicaid Services**: $205.9 billion (40.0% of total)
2. **National Institutes of Health**: $121.1 billion (23.6% of total)
3. **Centers for Disease Control and Prevention**: $62.2 billion (12.1% of total)
4. **Office of Assistant Secretary for Preparedness and Response**: $57.0 billion (11.1% of total)
5. **Administration for Children and Families**: $28.5 billion (5.5% of total)

**Key Finding**: Top 5 agencies account for $474.7 billion (92.3% of total spending)

### Geographic Distribution
**States by Contract Value:**
1. **Virginia**: $136.6 billion (26.6% of total)
2. **Maryland**: $99.2 billion (19.3% of total)
3. **Pennsylvania**: $21.5 billion (4.2% of total)
4. **Texas**: $16.3 billion (3.2% of total)
5. **Massachusetts**: $16.0 billion (3.1% of total)

**Key Finding**: Virginia and Maryland combined capture $235.8 billion (45.9% of total), reflecting DC-area contractor concentration

![Geographic Distribution](images/hhs-geographic-distribution.png)
*State-by-state breakdown of HHS contract awards showing regional concentration*

### Industry Sector Analysis
**Top Funded Industry Sectors:**
1. **Direct Health and Medical Insurance Carriers**: $99.3 billion (19.3%)
2. **Computer Systems Design Services**: $55.9 billion (10.9%)
3. **Custom Computer Programming Services**: $32.4 billion (6.3%)
4. **R&D in Physical/Engineering/Life Sciences**: $30.1 billion (5.9%)
5. **Facilities Support Services**: $24.0 billion (4.7%)

**Key Finding**: Health insurance and IT services dominate, representing 30.2% of total spending

### Business Size Analysis
**Contract Distribution by Business Size:**
- **Large Businesses**: 36,764 contracts, $431.1 billion (83.8% of value)
  - Average contract value: $11.7 million
- **Small Businesses**: 34,823 contracts, $83.3 billion (16.2% of value)
  - Average contract value: $2.4 million

**Key Finding**: Large businesses capture 5x more value per contract than small businesses

### Temporal Trends
**Contract Value Growth Over Time:**
- **2016**: $17.9 billion in new contract starts
- **2020**: $77.7 billion in new contract starts (4.3x increase)
- **Peak Period**: 2020-2021 (pandemic response era)
- **Post-2021**: Noticeable decline toward historical averages

**Key Finding**: 334% increase from 2016-2020, likely driven by pandemic-related spending

![Spending Trends](images/hhs-spending-trends.png)
*HHS contract spending trends showing dramatic increase during 2020-2021*

## Business Impact & Recommendations

### For Government Procurement Officials
- **Contractor Diversification**: Consider strategies to reduce concentration risk (top 10 capture 38.3%)
- **Geographic Equity**: Evaluate whether 46% concentration in VA/MD serves national interests
- **Small Business Support**: Enhance programs to increase small business contract values and competition
- **Pandemic Preparedness**: Maintain enhanced procurement capabilities developed during 2020-2021

### For Policy Makers
- **Spending Transparency**: Use analysis for congressional oversight and budget justification
- **Regional Development**: Consider impacts of geographic concentration on economic development
- **Competition Policy**: Address potential anti-competitive effects of high contractor concentration
- **Emergency Response**: Formalize rapid procurement procedures based on pandemic experience

### For Healthcare Stakeholders
- **Market Analysis**: Understand federal funding priorities for strategic planning
- **Partnership Opportunities**: Identify potential collaboration with major recipients
- **Innovation Investment**: Leverage R&D spending patterns ($30.1B) for research alignment
- **Technology Focus**: Capitalize on IT services emphasis ($88.3B combined)

### For Oversight Bodies
- **Risk Assessment**: Monitor concentration risks in critical health services
- **Performance Metrics**: Develop outcome-based evaluation for large contracts
- **Fraud Prevention**: Focus resources on highest-value contracts and recipients
- **Trend Analysis**: Establish baseline for future procurement pattern analysis

## Future Improvements

### Performance Analysis
- **Outcome Measurement**: Link contract spending to health outcomes and service delivery
- **ROI Analysis**: Calculate return on investment for major contract categories
- **Contractor Performance**: Develop scoring system for recipient effectiveness
- **Cost-Benefit Studies**: Analyze value delivered per dollar spent

### Advanced Analytics
- **Predictive Modeling**: Forecast future spending patterns based on historical trends
- **Network Analysis**: Map relationships between contractors, subcontractors, and agencies
- **Efficiency Metrics**: Compare cost per outcome across similar contracts
- **Risk Assessment**: Identify potential concentration and dependency risks

### Data Enhancement
- **Real-Time Monitoring**: Integrate with current procurement systems for ongoing analysis
- **Outcome Integration**: Connect spending data with health program results
- **Competitive Analysis**: Compare HHS patterns with other federal agencies
- **International Benchmarking**: Assess efficiency against comparable health systems

### Visualization Improvements
- **Interactive Dashboards**: Create stakeholder-specific visualization tools
- **Geographic Mapping**: Develop detailed regional and local impact analysis
- **Temporal Analysis**: Build dynamic trend analysis capabilities
- **Mobile Access**: Ensure analysis accessibility for field personnel

## Technical Implementation

### Data Sources
- **Primary Dataset**: USAspending.gov Award Data Archive
- **URL**: https://www.usaspending.gov
- **File**: FY2023_075_Contracts_Full_20250611_1.csv
- **Size**: 163 MB, 71,587 contract records
- **Coverage**: All HHS contract awards for fiscal year 2023

### Tools and Technologies
- **Database**: PostgreSQL for data storage and management
- **Programming**: Python for data processing and analysis
- **Visualization**: Tableau for interactive dashboards and reporting
- **Analysis Tools**: Statistical analysis, trend modeling, geographic mapping
- **Data Processing**: Large dataset handling, missing value treatment, aggregation

### System Requirements
- **Database**: PostgreSQL 12+ for data storage
- **Memory**: 8GB+ RAM recommended for full dataset processing
- **Storage**: 2GB for complete analysis including visualizations
- **Software**: Tableau Desktop/Public, Python 3.7+, pgAdmin

### Data Quality Procedures
- **Missing Value Treatment**: Filled blank current_total_value_of_award with 0
- **Date Validation**: Handled 7,257 contracts with missing end dates
- **Geographic Verification**: Flagged records with missing state/country data
- **Financial Validation**: Verified sum totals and prevented null calculation errors

## Files in Repository
- `hhs_contract_analysis.ipynb` - Complete analytical workflow and findings
- `data/FY2023_075_Contracts_Full_20250611_1.csv` - HHS contract dataset (cleaned)
- `tableau/` - Interactive dashboard files and visualizations
- `images/` - Charts, graphs, and analysis outputs
- `sql/` - Database queries and data processing scripts
- `documentation/` - Data cleaning procedures and methodology
- `README.md` - This project documentation

## Data Quality & Limitations
- **Missing End Dates**: 7,257 contracts (10.1%) lack performance end dates
- **Geographic Gaps**: Small subset missing state/country information
- **Data Currency**: Analysis based on data as of June 6, 2025
- **Scope**: Limited to HHS contracts only, not broader federal spending
- **Disclaimer**: Analysis for transparency and oversight purposes, not policy recommendations

## Contact Information
- **Email**: ramonmarlow.business@gmail.com
- **LinkedIn**: [linkedin.com/in/ramprocess](https://linkedin.com/in/ramprocess)
- **Kaggle**: [kaggle.com/ramprocess](https://kaggle.com/ramprocess)
- **Tableau**: [public.tableau.com/profile/ramprocess](https://public.tableau.com/profile/ramprocess)
- **Location**: Florida, USA
