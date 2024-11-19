# Telecom Customer Churn Analysis

### **Background**  
Airtel, a leading telecommunications company, has noticed a concerning trend: an increasing number of customers discontinuing their services. This trend poses a significant threat to the company’s revenue and market share.

### **Scenario**  
As a data analyst at Airtel, your responsibility is to analyze customer data to uncover patterns and insights contributing to churn. These findings will be instrumental in shaping strategies to enhance customer retention.

### **Problem Statement**  
The core challenge is identifying the factors driving customer churn at Airtel. Understanding these factors will enable the development of targeted interventions, reducing churn rates and enhancing customer satisfaction.

---

## **Data Dictionary**

| **Column Name**               | **Description**                                                                 |
|-------------------------------|---------------------------------------------------------------------------------|
| `area_code`                   | The geographic code associated with the customer's location.                    |
| `customer_service_calls`      | The number of calls made by the customer to customer service.                   |
| `account_length`              | The duration (in months) the customer has been with Airtel.                     |
| `international_plan`          | Indicates if the customer has an international calling plan (`yes` or `no`).    |
| `international_charge`        | Charges incurred by the customer for international calls.                       |
| `evening_calls`               | Total number of calls made by the customer during the evening hours.            |
| `evening_charge`              | Charges incurred for evening calls.                                             |
| `voice_mail_plan`             | Indicates if the customer has subscribed to a voice mail plan (`yes` or `no`).  |
| `voice_mail_messages`         | The number of voice mail messages sent by the customer.                         |
| `day_minutes`                 | Total minutes of calls made during the day by the customer.                     |
| `day_calls`                   | Total number of calls made during the day.                                      |
| `international_calls`         | Total number of international calls made by the customer.                       |
| `churn_status`                | Indicates if the customer churned (`yes` or `no`).                              |

---

## **Solutions and Key Insights**

### **1. Geographic Analysis**
- Area Code 415 has the highest churn rate (**49.60%**) compared to 408 (**25.55%**) and 510 (**24.85%**).  
- **Insight**: Regional service quality or competitive factors need attention.

### **2. Customer Service Calls**
- Customers making **4+ service calls** have a **60%+ churn rate**.  
- **Insight**: Dissatisfaction from unresolved issues drives churn.

### **3. Customer Tenure**
- Churn peaks at **101–120 months** of tenure but is also significant for newer customers (**1–40 months**).  
- **Insight**: Both onboarding and re-engagement programs are crucial.

### **4. International Plans and Charges**
- Customers with high international charges (**4–6 units**) have **50% churn**.  
- **Insight**: Pricing optimization for international plans is necessary.

### **5. Daytime Calls and Minutes**
- High usage (**200–300 minutes/day**) correlates with churn.  
- **Insight**: Daytime pricing plans need adjustment to reduce churn.

### **6. Evening Calls and Charges**
- Evening users with charges in the **20–25 unit range** experience higher churn.  
- **Insight**: Flexible evening plans could help retain these customers.

### **7. Voicemail Plans**
- Customers sending **30–39 voicemail messages** show moderate churn.  
- **Insight**: Bundling voicemail with other features could increase perceived value.

### **8. International Call Patterns**
- Customers making **4–7 international calls** churn at higher rates.  
- **Insight**: Moderate users need affordable, value-driven international plans.

---

## **Business Impact**

1. **Improved Retention**: Targeted interventions based on the insights can reduce churn rates significantly.  
2. **Revenue Growth**: Retaining customers with optimized pricing and service offerings will enhance revenue.  
3. **Customer Satisfaction**: Addressing service quality and pricing concerns will build stronger customer loyalty.  
4. **Market Competitiveness**: Retaining customers in high-churn regions will strengthen Airtel’s market position.

---

## **Conclusion**

This analysis provides actionable insights into the factors driving customer churn at Airtel. By focusing on improving service quality, offering flexible pricing, and tailoring regional marketing strategies, the company can effectively enhance customer retention, satisfaction, and revenue.

---

## **License**

This project is released under the [MIT License](https://opensource.org/licenses/MIT). You are free to use, modify, and distribute the content for educational or professional purposes.

---

## **Portfolio and LinkedIn**

- **Portfolio**: [Visit my portfolio](https://peerlist.io/kunalmalviya06)  
- **LinkedIn**: [Connect with me](https://www.linkedin.com/in/kunal-malviya-0b6340289/details/skills/)
