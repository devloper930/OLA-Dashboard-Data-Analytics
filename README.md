# 📊 Ola Mobility Data Analysis – Bengaluru City

## 📝 Introduction

Urban mobility is one of the defining challenges of modern cities, and ride-hailing platforms like **Ola** have revolutionized how people navigate metropolitan areas. This project uncovers insights from a **simulated dataset** of Ola ride bookings in **Bengaluru**, India’s tech capital—renowned for its dense traffic and dynamic commuter patterns.

Through data-driven analysis, we explore user behavior, operational bottlenecks, service reliability, and satisfaction metrics—aiming to support smarter mobility strategies and informed decision-making within the ride-hailing ecosystem.

---

## 📦 About the Dataset

The dataset is a **synthetic yet realistic representation** of Ola ride bookings in Bengaluru. It includes diverse information on mobility behavior, customer interactions, and operational dynamics—enabling a multifaceted analysis of the city’s ride-hailing ecosystem.

### 📁 Dataset Columns

1. **Date** – Booking date  
2. **Time** – Booking time  
3. **Booking ID** – Unique identifier per booking  
4. **Booking Status** – Success, Cancelled, or Incomplete  
5. **Customer ID** – Unique identifier per customer  
6. **Vehicle Type** – Categories:  
   - Auto  
   - Prime Plus  
   - Prime Sedan  
   - Mini  
   - Bike  
   - eBike  
   - Prime SUV  
7. **Pickup Location** – 50 dummy areas in Bengaluru  
8. **Drop Location** – Same set of dummy areas  
9. **Avg VTAT** – Avg. vehicle time to arrive at pickup  
10. **Avg CTAT** – Avg. customer time to reach vehicle  
11. **Cancelled Rides by Customer** – Binary indicator  
12. **Customer Cancellation Reasons**:  
    - Driver not moving towards pickup  
    - Driver asked to cancel  
    - AC not working *(for 4-wheelers only)*  
    - Change of plans  
    - Wrong address  
13. **Cancelled Rides by Driver** – Binary indicator  
14. **Driver Cancellation Reasons**:  
    - Personal/Car issues  
    - Customer-related issues  
    - Health/sick customer  
    - Over-capacity passengers  
15. **Incomplete Rides** – Binary indicator  
16. **Incomplete Ride Reasons**:  
    - Customer demand  
    - Vehicle breakdown  
    - Other issue  
17. **Booking Value** – Ride cost in currency  
18. **Ride Distance** – Distance traveled in km  
19. **Driver Rating** – Rating given by customer (1–5)  
20. **Customer Rating** – Rating given by driver (1–5)  

---

## 🎯 Project Objectives

This analysis addresses the following core questions:

- What are the overall booking patterns and values?
- Which vehicle types perform better in terms of usage and satisfaction?
- What are the main causes of booking failures?
- How do payment methods influence revenue?
- What steps can improve service efficiency and reliability?

---

## 📈 Key Findings & Visualizations

### 1. Total Bookings and Booking Value  
![Booking Dashboard](OLA%20Dashboard/Dashboard/Total%20bookings.png)

---

### 2. Booking Value by Vehicle Type  
![Booking Value per Vehicle Type](OLA%20Dashboard/Dashboard/2.%20Vehcle%20Type.png)

#### 📊 Insights

- 🟢 **E-Bike** has the highest average ride distance (25.15 km), showing strong long-route efficiency.  
- 🟡 **Auto** has the lowest distance metrics, indicating usage for short local trips.

#### ✅ Recommendations

- Promote **E-Bikes** for long-distance urban commutes.  
- Optimize **Auto** supply in short-distance, high-density zones.

---

### 3. Booking Status Distribution  
![Booking Status](OLA%20Dashboard/Dashboard/booking%20status%20over%20time.png)

#### 📊 Insights

- ✅ **Success Rate:** 62.09% – healthy operational efficiency.  
- ❌ **Driver Cancellations:** 17.89% – top failure reason, harming customer trust.  
- ⚠️ **Driver Not Found:** 9.83% – significant inefficiency.

#### ✅ Recommendations

- Introduce **driver incentive programs** to lower cancellation rates.  
- Improve **driver availability algorithms** to reduce unfulfilled requests.

---

### 4. Revenue by Payment Method  
![Payment Methods](OLA%20Dashboard/Dashboard/revenue%20by%20payment%20method.png)

#### 📊 Insights

- 💵 **Cash** dominates revenue, contributing nearly ₹20M.  
- 💳 **Card payments** (Credit & Debit) show minimal adoption.  
- 📱 **UPI** shows strong performance after cash.

#### ✅ Recommendations

- Launch **UPI-based promotions** to boost digital adoption.  
- Offer **discounts on card usage** to reduce cash dependency.

---

### 5. Average Customer Ratings by Vehicle Type  
![Customer Ratings](OLA%20Dashboard/Dashboard/customer%20rating.png)

#### 📊 Insights

- 🌟 **Prime Plus** leads with the highest customer rating (4.01).  
- 🚲 **Bike** and **E-Bike** have the lowest ratings (3.99), though still close to 4.

#### ✅ Recommendations

- Investigate **Bike & E-Bike service gaps** via customer feedback.  
- Promote **Prime Plus** as a premium, highly rated experience.

---

### 6. Average Driver Ratings by Vehicle Type  
![Driver Ratings](OLA%20Dashboard/Dashboard/driver%20rating.png)

#### 📊 Insights

- 🏆 **E-Bike** and **Prime SUV** drivers rated highest (4.01).  
- 🛵 **Bike** drivers rated lowest (3.98), suggesting room for improvement.

#### ✅ Recommendations

- Acknowledge & retain **top-rated drivers**.  
- Provide **training & incentives** for lower-rated categories.

---

### 7. Cancellation Reasons – Customers  
![Customer Cancellations](OLA%20Dashboard/Dashboard/cancel%20ride%20by%20customer.png)

#### 📊 Insights

- 🚫 30.24% of customer cancellations occur when **drivers don’t move toward pickup**.

#### ✅ Recommendations

- Strengthen **live tracking and driver commitment systems** to minimize abandonment.

---

### 8. Cancellation Reasons – Drivers  
![Driver Cancellations](OLA%20Dashboard/Dashboard/cancel%20ride%20by%20rider.png)

#### 📊 Insights

- 🧰 35.49% of driver cancellations are due to **personal or vehicle-related issues**.

#### ✅ Recommendations

- Offer **maintenance support** and **backup driver options** to minimize service disruption.

---

## ✅ Final Recommendations Summary

| Area            | Recommendation                                              |
|-----------------|--------------------------------------------------------------|
| Vehicle Types   | Promote E-Bikes for long trips; deploy Autos in dense zones |
| Cancellations   | Incentivize drivers, optimize routing, offer car maintenance |
| Payments        | Encourage UPI & card use with offers and discounts          |
| Service Ratings | Focus on Bike & E-Bike quality improvements                 |
| Driver Engagement | Recognize top performers and train lower-rated drivers     |

---

## 🌍 Complete Analysis – July 2024 (Bengaluru)

### 📊 Key Highlights

- **Total Bookings:** 103,024  
- **Total Booking Value:** ₹35M  
- **Success Rate:** 62.09%  
- **Cancellation Rate:** 28.08%  
- **Daily Ride Volume:** ~3,000–3,400

### ❌ Cancellation Insights

#### Cancelled by Customer
- 🚧 Driver not moving: 30.2%  
- 🙅 Driver asked to cancel: 25.4%  
- 🔁 Change of plans: 19.8%

#### Cancelled by Driver
- 🔧 Car/personal issues: 35.5%  
- 😤 Customer-related: 29.4%

> **~38% of rides failed** due to cancellations or unavailability.


### 🚀 Recommendations

- 🔁 **Auto reassign on no-shows**  
  Automatically reassign bookings when drivers don't show up on time to reduce customer cancellations and improve ride completion rates.

- ✅ **Driver accountability system**  
  Implement a performance tracking system that flags frequent cancellations or poor ratings, holding drivers accountable and improving service consistency.

- ⏱️ **Better ETA communication**  
  Provide real-time, accurate ETA updates to customers and drivers to reduce uncertainty, cancellations, and improve time management during pickups.

- 🤝 **Passenger trust-building features**  
  Add features like verified driver profiles, live tracking, and safety alerts to foster trust and improve the overall experience.


⚠️ **Focus:** Reduce cancellations, optimize driver behavior, and enhance user satisfaction.

---

### 🧾 Conclusion

Ola’s July 2024 ride data in Bengaluru reveals strong service demand but highlights notable inefficiencies in cancellations. While e-Bikes and premium rides show promise, improving driver reliability and reducing failed bookings are key. Focused operational adjustments can significantly enhance user trust, satisfaction, and revenue potential in urban mobility.
