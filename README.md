# TransJakarta Bus Rapid Transit Analysis

## Project Overview
This project analyzes TransJakarta's bus rapid transit (BRT) trip records from April 2023 to understand passenger behavior and preferences. The analysis explores travel patterns, payment methods, route popularity, and demographic information to optimize service quality and increase ridership.

## Business Problem
TransJakarta needs to understand how passengers currently use their services to develop targeted strategies for different user segments. The main question addressed is: **What are the behavior patterns and preferences of passengers using TransJakarta services?**

The analysis specifically addresses:
- Peak usage patterns
- Passenger payment preferences
- Most popular routes and stops
- How different demographic groups use the TransJakarta system

## Dataset
The dataset contains detailed TransJakarta trip records with features including:
- Transaction IDs and payment information
- Passenger demographics (gender, age)
- Route and corridor details
- Entry/exit stop information with timestamps and coordinates
- Fare amounts

## Analysis Highlights

### Passenger Patterns
- **Peak Hours**: Distinct commuting patterns with peak hours during 6-9 AM and 4-7 PM
- **Weekly Patterns**: Weekday ridership is four times higher than weekend ridership
- **Service Types**: BRT is the backbone (51.3% of rides), with Mikrotrans as a feeder service (41.8%)

### Demographics
- **Age Distribution**: Core users are working-age adults (26-45 years old)
- **Gender Distribution**: Relatively balanced with a slight skew toward female riders (53.3%)
- **Youth Presence**: Significant ridership among the 18-25 age group (students and young professionals)

### Payment Analysis
- DKI card dominates with nearly half of all transactions
- E-money accounts for about one-fifth of payments
- Payment preferences vary by age group and gender

### Route Performance
- Cibubur - Balai Kota is the most popular route (~390 passengers)
- Highest revenue routes connect to major commercial areas
- Concentrated usage at specific stops (Penjaringan, BKN, etc.)

## Key Recommendations

### 1. TransJakarta Loyalty Program
- Point-reward system with multipliers based on travel timing and age
- Higher rewards for off-peak and weekend travel to redistribute ridership
- Special focus on students (ages 25 and under)
- Integration with JakOneMobile for convenient tracking and redemption

### 2. TransJakarta Leisure Route
- Target weekend ridership through partnerships with attractions like Taman Mini Indonesia Indah
- Family packages combining transportation and attraction entry fees
- "Family Pass" promotional rates and special express routes connecting multiple family-friendly destinations

### 3. Express Lane Service
- Express routes along highest-revenue corridors
- Stops only at major hubs with highest tap-in/tap-out activity
- Reduced travel times during peak hours

## Project Structure
This project was completed as part of a Data Analysis Capstone Project and includes:
1. Jupyter Notebook with full analysis and code documentation
2. Presentation slides summarizing findings and recommendations
3. Tableau Public dashboard visualizing key insights

## Methodology
The analysis process included:
1. Data cleaning and preprocessing to handle missing values and inconsistencies
2. Exploratory data analysis of passenger patterns, demographics, and payment preferences
3. Statistical analysis of relationships between variables
4. Visualization of key findings
5. Development of actionable recommendations

## Tools Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- Tableau Public for interactive visualization
