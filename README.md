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

## Project Objectives
- Analyze the overall distribution of customers based on key characteristics.
- Examine churn patterns across different customer segments.
- Compare churn based on demographic factors.
- Analyze the relationship between customer services and churn.
- Understand how contract type is associated with customer churn.
- Examine the relationship between billing preferences and churn.
- Identify customer groups that show different levels of churn.

## Dashboard Analysis
The dashboard contains visualizations covering the following areas:

## Customer Demographics
- Gender vs Churn
- Senior Citizen Status vs Churn
- Partner Status vs Churn
- Dependents Status vs Churn
These visuals help compare churn patterns across different demographic and household characteristics.

## Service Analysis
- Internet Service vs Churn
- Tech Support vs Churn
- Online Security vs Churn
These analyses examine whether the type of internet service and additional support/security services are associated with differences in customer churn.

## Contract & Billing Analysis
- Contract Type vs Churn
- Paperless Billing vs Churn
These visuals explore how contractual commitments and billing preferences relate to customer retention.

## Key Dashboard Features
- Interactive Power BI visualizations
- Churn comparison across multiple customer attributes
- Customer-level segmentation
- Categorical analysis of services and subscriptions
- Clear comparison of churned and retained customers
- Consistent dashboard layout for easier interpretation

## Tools & Technologies
- Microsoft Power BI
- Power Query – Data cleaning and transformation
- DAX – Calculations and analytical measures
- Data Visualization
- Customer Churn Analysis

## Analytical Approach
- Data Import – Imported the customer churn dataset into Power BI.
- Data Cleaning & Transformation – Prepared the dataset using Power Query.
- Data Validation – Checked categorical values and data types.
- Data Modeling – Prepared the data for visualization and analysis.
- Visualization – Created comparative charts for churn analysis.
- Analysis – Examined churn patterns across demographic, service, contract, and billing attributes.
- Dashboard Design – Organized the visuals into a single structured Customer Churn Analysis dashboard.
