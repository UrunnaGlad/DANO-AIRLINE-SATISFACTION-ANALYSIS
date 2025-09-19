# ✈️ Dano Airline Passenger Satisfaction Analysis (Power BI Project)

<img width="1745" height="913" alt="intro_image" src= https://github.com/urunna-glad/DANO-AIRLINE-SATISFACTION-ANALYSIS/blob/main/intro_image.png/>

## 📌 Introduction 
PowerBI dashboard analyzing Dano Airline's performance and customer satisfaction
This is **Power Bi airline passenger satisfaction analysis**  of an imaginary airline called Dano Airline. The project is to analyze and derive insights into customer experience and overall satisfaction and help the airline make data driven decisions.
The dataset includes passenger demographics, travel type, class, delays, and service quality ratings and it comprises of two pages (Overview and Insights).

---
## 📊 Key Insights
- **Satisfaction Rate**: Out of 130,000 passengers report only 790,000 passengers were satisfied rating 43%, 1,028,000 passengers expressed dissatisfaction, rating 53%
- **Age Impact**:  Satisfaction is highest among Adults (58%), Young Adults (38%), Elderly (27%), Teenager (20%) and Children (13%) report much lower satisfaction
- **Gender**: Satisfaction is nearly balanced between Male (51%) and Female (49%) passengers.
- **In-flight Service, Baggage Handling and seat comfort**: are the highest rank drivers of satisfaction.  
- **Ease of Location**: Scored an average of **2.98**, making it one of the lowest-rated factors. This shows that passengers face difficulties with airport navigation, signage, and boarding gate accessibility.  
- **WiFi services and Ease of Online Booking**: Also rank loww, highlighting areas for improvement.  
- **Returning customers**: Form the majority of the dataset, showing loyalty but also higher expectations.  
- **Arrival and Departure delays**: Strongly reduce passenger satisfaction scores, emphasizing the importance of operational efficiency.

---

## 🛠️ Steps Taken
1. **Data Collection & Import**  
   - Imported `Dano_Airline_Data.xlsx` into Power BI.  
   - Reviewed dataset containing 24 columns with demographic, travel, and satisfaction related data.  

2. **Data Cleaning & Preparation**  
   - Checked for missing/null values and handled inconsistencies.  
   - Standardized categorical values (e.g., `Satisfied`, `Neutral or Dissatisfied`, `Class`, `Customer Type`).  
   - Verified numerical ranges for service rating columns (1–5).     

3. **Created Calculated Columns**  
   To enhance the analysis, the following columns and measures were created in Power BI:  
   - **Age Groups** → Grouped passengers into age ranges (e.g.,0-12, 13-17, 18-40, 40-60, 60+)  
   - **Satisfaction Numeric** → Converted satisfaction to numeric values (`Satisfied = 1`, `Neutral/Dissatisfied = 0`) for easier aggregation.  
   - **Arrival Delay Time** → Captured and standardized arrival delays.  
   - **Departure Delay Time** → Captured and standardized departure delays.  
   - **Service Name** → Unpivoted service-related columns into a single column for flexible analysis (e.g., "Seat Comfort", "Food & Drink", "In-flight Entertainment").  
   - **Rating** → Corresponding rating values (1–5) aligned with each service name.

4. **Created Measures for KPI and Dashboard**
   -  Dissatisfaction Rate
   -  Satisfaction Rate
   -  Dissatisfied Count
   -  Satisfied Count
   -  Service Rank
   -  Total Respondents

5. **Exploratory Data Analysis (EDA)**  
   - Generated descriptive statistics to identify top/bottom rated services.  
   - Conducted correlation analysis to see which factors influenced satisfaction most.  

6. **Visualization & Dashboard Development**  
   - Built **interactive dashboards**:  
     - Passenger demographics (age group, gender, travel type, class).    
     - Delay analysis (departure vs arrival impact).  
     - Satisfaction distribution by service category.   

---

## ✅ Recommendations
- Enhance **digital boarding systems** and reduce queue times.  
- Upgrade **in-flight WiFi** to meet modern passenger expectations.  
- Improve **airport navigation (Ease of Location)** with clearer signage, staff assistance, and mobile app integration.  
- Reduce **operational delays** through process optimization and crew coordination.   
- Collect **real-time customer feedback** for continuous improvement.  

---

## 📸 Dashboard Preview
 <img width="1745" height="913" alt="Dano_Airline_Dashboard" src= https://github.com/urunna-glad/DANO-AIRLINE-SATISFACTION-ANALYSIS/blob/main/Dano_Airline_Dashboard1.png/>

<img width="1745" height="913" alt="Dano_Airline_Dashboard2" src= https://github.com/urunna-glad/DANO-AIRLINE-SATISFACTION-ANALYSIS/blob/main/Dano_Airline_Dashboard2.png/>


## 📈 Conclusion
The analysis reveals that while the airline excels in **In-flight Service, Baggage Handling, On-boarding Service, entertainment, and seat comfort**, there are significant pain points in **ease of location (2.98 average rating)**, **WiFi connectivity**, and **food services**.  
By improving **end-to-end customer experience** from airport navigation to in-flight amenities, the airline can significantly raise satisfaction scores and strengthen passenger loyalty.
