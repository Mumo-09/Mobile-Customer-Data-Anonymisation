## Mobile Customer Data Anonymisation

### Overview

This project demonstrates the anonymisation of a mobile customer dataset by applying data privacy techniques to protect personally identifiable information (PII) while preserving the dataset's analytical value. The anonymised dataset is suitable for data analysis without exposing sensitive customer information.

### Objective

The objective of this project was to:

* Protect customer privacy by removing or transforming sensitive information.
* Preserve valuable data for analysis.
* Demonstrate practical data anonymisation techniques commonly used in data science and data governance.

### Anonymisation Techniques

#### Pseudonymisation

* Replaced the original customer identifier with anonymous IDs (`U0001`, `U0002`, ...).

#### Generalisation

* Converted **Age** into **Age Groups**:

  * `<20`
  * `20–29`
  * `30–39`
  * `40–49`
  * `50+`

* Converted **Salary** into **Salary Brackets**:

  * `<50k`
  * `50k–99k`
  * `100k–149k`
  * `150k+`

#### Removal of Sensitive Data

The following information was removed to protect customer privacy:

* Username
* Name
* Email Address
* Birthdate
* Residence
* Employer
* GPS Location
* Credit Card Provider
* Credit Card Number
* Credit Card Security Code (CVV)
* Credit Card Expiry Date
* Original Age
* Original Salary

### Final Dataset

The anonymised dataset contains the following fields:

* anonymous_customer_id
* date_registered
* gender
* job
* Age Group
* Salary Bracket

### Tools Used

* Microsoft Excel

### Skills Demonstrated

* Data Cleaning
* Data Anonymisation
* Data Privacy
* Data Generalisation
* Pseudonymisation
* Data Minimisation
* Microsoft Excel
* Data Preparation

### Outcome

The resulting dataset maintains its analytical usefulness while reducing the risk of identifying individual customers. This project demonstrates practical data privacy techniques that are widely used in data analytics, business intelligence, and data science workflows.
