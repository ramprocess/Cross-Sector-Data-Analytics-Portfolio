# U.S. Crime Analysis (1979-2023)

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
Comprehensive analysis of 45 years of FBI crime data to identify trends, patterns, and insights for evidence-based policy making and public safety resource allocation. This project examines criminal activity across all 50 states and Washington D.C. from 1979 through 2023.

## Objectives
- Identify national crime trends and peak periods over 45 years
- Compare state-level crime patterns and crime-to-population ratios
- Analyze relationship between violent and property crimes
- Calculate per-capita crime improvements accounting for population growth
- Provide data-driven insights for policy makers and law enforcement

## What Was Done

### Data Processing
- Cleaned FBI crime dataset (estimated_crimes_1979_2023.csv, 200.2 KB)
- Removed 38 rows with missing state identifiers to ensure data quality
- Standardized rape reporting categories (legacy vs. revised definitions)
- Calculated crime-to-population ratios for all states and D.C.
- Validated data integrity and documented all cleaning procedures

### Analysis Methodology
- **Trend Analysis**: Examined 45-year crime patterns to identify peak periods and decline trajectories
- **State Comparison**: Calculated crime-to-population ratios for geographic analysis
- **Crime Categorization**: Analyzed violent vs. property crime distributions
- **Per-Capita Analysis**: Adjusted crime rates for population growth over time
- **Statistical Modeling**: Applied trend analysis and comparative statistics

### Key Techniques
- Time series analysis for trend identification
- Data aggregation and grouping by state and crime type
- Comparative ratio analysis across geographic regions
- Statistical calculations for percentage changes and growth rates

![Crime Trends Analysis](images/crime-trends-chart.png)
*45-year national crime trends showing dramatic decline from 1990s peak*

## Results

### National Crime Trends
- **48.4% total crime reduction** from 1991 peak (14.8M incidents) to 2023 (7.6M incidents)
- **50.5% property crime decrease** from 12.96 million to 6.42 million incidents
- **34.4% violent crime reduction** from 1.91 million to 1.25 million incidents
- **Peak crime period identified**: Early 1990s (1991-1993) with highest recorded levels

### State-Level Analysis
**Highest Crime States (Total Volume 1979-2023):**
1. **California**: 66.6M crimes (4.44% crime-to-population ratio)
2. **Texas**: 46.6M crimes (4.76% ratio)
3. **Florida**: 37.6M crimes (5.19% ratio)
4. **New York**: 31.4M crimes (3.72% ratio)
5. **Illinois**: 22.7M crimes (4.12% ratio)

**Lowest Crime States (Total Volume 1979-2023):**
1. **North Dakota**: 747K crimes (2.51% ratio)
2. **Wyoming**: 771K crimes (3.30% ratio)
3. **Vermont**: 782K crimes (2.94% ratio)
4. **South Dakota**: 860K crimes (2.47% ratio)
5. **Alaska**: 1.2M crimes (4.42% ratio)

**Special Finding**: Washington D.C. highest crime-to-population ratio at 7.8%

### Crime Type Distribution
- **Property crimes consistently 4-7 times more frequent** than violent crimes
- **Larceny dominates**: 300.1M incidents (nearly 50% of all crime)
- **Top crime categories**: Larceny, Burglary (105.4M), Motor Vehicle Theft (50.1M)
- **Violent crime breakdown**: Robbery (20.0M), Rape (4.9M combined), Homicide (844K)

![State Crime Comparison](images/state-crime-ratios.png)
*Crime-to-population ratios by state showing geographic patterns*

### Per-Capita Improvements
**2023 National Rates:**
- Total crime rate: 2.2% of population
- Property crime rate: 2.0% of population
- Violent crime rate: 0.2% of population

**Average State Decreases (1991-2023):**
- Property crime: 60.83% decrease
- Total crime: 58.41% decrease
- Violent crime: 38.91% decrease

## Business Impact & Recommendations

### For Government Agencies
- **Resource Allocation**: Focus on property crime prevention (4-7x higher frequency than violent crime)
- **Geographic Targeting**: Prioritize states with highest crime-to-population ratios
- **Budget Planning**: Leverage 48% crime reduction success for continued investment
- **Policy Development**: Use evidence-based approach for crime prevention strategies

### For Law Enforcement
- **Prevention Focus**: Emphasize larceny and burglary prevention (highest volume crimes)
- **Resource Deployment**: Allocate personnel based on state-specific crime patterns
- **Training Programs**: Develop specialized units for property crime investigation
- **Community Policing**: Implement successful models from crime reduction era

### For Policy Makers
- **Evidence-Based Decisions**: Use 45-year trend data for long-term planning
- **Interstate Cooperation**: Address crime patterns that cross state boundaries
- **Economic Analysis**: Quantify cost savings from 48% crime reduction
- **Public Safety Investment**: Continue strategies that achieved sustained decreases

![Crime Impact Analysis](images/business-impact.png)
*Economic impact of crime reduction over 45-year period*

## Future Improvements

### Economic Correlation Analysis
- **Income vs. Crime**: Analyze relationship between state income levels and crime rates
- **Education Impact**: Examine correlation between education levels and crime reduction
- **Employment Factors**: Study unemployment rates and crime pattern relationships
- **Housing Market**: Investigate property values and crime location patterns

### Advanced Analytics
- **Urban vs. Rural**: Break down crime patterns by population density
- **Demographic Analysis**: Examine age, race, and socioeconomic factors
- **Predictive Modeling**: Build forecasting models for future crime trends
- **Seasonal Patterns**: Analyze monthly and seasonal crime variations

### Technical Enhancements
- **Interactive Dashboards**: Create dynamic visualizations for stakeholder use
- **Real-Time Integration**: Connect with current crime reporting systems
- **Geographic Mapping**: Develop heat maps and spatial analysis tools
- **Automated Reporting**: Build systems for regular trend updates

## Technical Implementation

### Data Sources
- **Primary Dataset**: FBI Crime Data Explorer (CDE)
- **URL**: https://cde.ucr.cjis.gov/LATEST/webapp/#/pages/downloads
- **File**: estimated_crimes_1979_2023.csv
- **Size**: 200.2 KB, 45 years of data
- **Coverage**: All 50 states plus Washington D.C.

### Tools and Technologies
- **Programming Language**: Python
- **Key Libraries**: pandas, numpy, matplotlib, seaborn
- **Analysis Tools**: Jupyter Notebooks, statistical modeling
- **Visualization**: Custom charts, trend analysis, comparative graphics
- **Data Processing**: Large dataset handling, missing value treatment

### System Requirements
- **Python Version**: 3.7+
- **Required Packages**: pandas>=1.3.0, numpy>=1.20.0, matplotlib>=3.3.0, seaborn>=0.11.0
- **Memory**: 4GB+ RAM recommended for full dataset processing
- **Storage**: 500MB for complete analysis and visualizations

## Files in Repository
- `crime_analysis.ipynb` - Complete analytical workflow and findings
- `data/estimated_crimes_1979_2023.csv` - FBI crime dataset (cleaned)
- `images/` - Charts, graphs, and visualization outputs
- `documentation/` - Data cleaning procedures and methodology notes
- `requirements.txt` - Python package dependencies
- `README.md` - This project documentation

## Data Quality & Limitations
- **Data Cleaning**: Removed 38 rows with missing state identifiers
- **Standardization**: Unified rape reporting categories for consistency
- **Transparency**: All cleaning procedures documented for reproducibility
- **Limitations**: Some states may be underrepresented due to data quality issues
- **Disclaimer**: Analysis for educational purposes, not policy recommendations

## Contact Information
- **Email**: ramonmarlow.business@gmail.com
- **LinkedIn**: [linkedin.com/in/ramprocess](https://linkedin.com/in/ramprocess)
- **Kaggle**: [kaggle.com/ramprocess](https://kaggle.com/ramprocess)
- **Location**: Florida, USA
