# HexSoftwares_Customer_Churn_Analysis
This project focuses on analyzing customer churn and retention patterns using Microsoft Power BI. The dashboard provides an interactive view of customer demographics, subscription details, services, and churn behavior to identify key factors associated with customer attrition.

## Data Glossary
| Column               | Description                                                                                                      |
| -------------------- | ---------------------------------------------------------------------------------------------------------------- |
| **customerID**       | Unique identifier assigned to each customer.                                                                     |
| **gender**           | Gender of the customer.                                                                                          |
| **SeniorCitizen**    | Indicates whether the customer is a senior citizen (1 = Yes, 0 = No).                                            |
| **Partner**          | Indicates whether the customer has a partner.                                                                    |
| **Dependents**       | Indicates whether the customer has dependents.                                                                   |
| **tenure**           | Number of months the customer has stayed with the company.                                                       |
| **PhoneService**     | Indicates whether the customer has subscribed to phone service.                                                  |
| **MultipleLines**    | Indicates whether the customer has multiple phone lines. Includes options such as Yes, No, and No phone service. |
| **InternetService**  | Type of internet service subscribed to, such as DSL, Fiber optic, or No internet service.                        |
| **OnlineSecurity**   | Indicates whether the customer has an online security service.                                                   |
| **OnlineBackup**     | Indicates whether the customer has an online backup service.                                                     |
| **DeviceProtection** | Indicates whether the customer has device protection service.                                                    |
| **TechSupport**      | Indicates whether the customer has technical support service.                                                    |
| **StreamingTV**      | Indicates whether the customer has a streaming TV service.                                                       |
| **StreamingMovies**  | Indicates whether the customer has a streaming movie service.                                                    |
| **Contract**         | Type of contract chosen by the customer, such as Month-to-month, One year, or Two year.                          |
| **PaperlessBilling** | Indicates whether the customer uses paperless billing.                                                           |
| **PaymentMethod**    | Payment method used by the customer, such as Electronic check, Mailed check, Bank transfer, or Credit card.      |
| **MonthlyCharges**   | Amount charged to the customer on a monthly basis.                                                               |
| **TotalCharges**     | Total amount charged to the customer during their tenure with the company.                                       |
| **numAdminTickets**  | Number of administrative support tickets raised by the customer.                                                 |
| **numTechTickets**   | Number of technical support tickets raised by the customer.                                                      |
| **Churn**            | Indicates whether the customer left the company (Yes = Churned, No = Retained).                                  |


* **Yes** → Customer churned
* **No** → Customer retained
