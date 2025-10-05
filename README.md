# Coupon_Dreams
Practical application of data analysis using python to understand coupon preference among drivers
# Practical Application 1 — Will a Customer Accept the Coupon?

### Overview
This project explores data from the UCI Machine Learning Repository to analyze which factors influence whether drivers accept or reject different types of coupons.  
The dataset includes variables such as destination, time, weather, age, and passenger type.  
The goal is to identify behavioral and demographic patterns in coupon acceptance.

---

### Tools Used
- **Python**
- **Pandas** for data cleaning and exploration  
- **Matplotlib** and **Seaborn** for visualization  
- **Jupyter Notebook** for analysis  

---

### Key Analyses
1. **Overall coupon acceptance rate**
2. **Temperature Distribution**
2. **Acceptance by coupon type** (Bar, Coffee House, etc.)
3. **Acceptance by visit frequency** (e.g., bar visits per month)
4. **Demographic insights** — age, gender, and passenger influence

---

---

### Bar Insights
- **Frequent bar visitors** (≥1 visit/month) accept coupons **65–78% of the time**.  
- **Drivers over 25** show a **61% acceptance rate**, suggesting consistent appeal over many age groups who visit a bar at least once a month** 
- **62%  of the frequent bar visitors did not have child passenger nor worked farm  jobs, indictaing lifstyles with more leisure time are more likely to accept**
- **63% of bar patrons who go to bars > once/month and under 30 would accept a bar coupon, indicating strong appeal from younger drivers.**
- **Based on the initial observations people who accept bar coupons are less likely to have children and have more leisure time.**

### Coffee House Insights
- Overall acceptance rate: **~50%**
- **Men and women equally accepted coupon from a coffee house, suggesting no gender bias in accepting coffee house coupons.**.
- **Drivers who never visited a coffee house only accepted a coupon 20% of the time, meaning minimal interest from drivers without a history of coffee house patronage.**
- **Male drivers who never visited a coffee house showed minimal interest in the coupon, consistent with prior findings and no gender bias.**


### Key Findings
- Frequent visitors to bar venues are **far more likely** to accept related coupons.  
- Acceptance is lowest among individuals who **never visit** the type of venue offered.  
- Demographics such as **age**, **passenger type**, and **occupation** influence responsiveness.  
- Targeting promotions based on **customer patronage** (rather than broad demographics) can significantly improve conversion.
