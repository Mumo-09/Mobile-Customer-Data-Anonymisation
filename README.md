## Mobile Customer Data Anonymisation

### Overview

This project demonstrates the anonymisation of a customer dataset containing personally identifiable information (PII) and sensitive financial data. The objective was to preserve the dataset's usefulness for analysis while protecting customer privacy using standard data anonymisation techniques.

### Dataset

The original dataset contained customer information such as:

* Customer ID
* Username
* Name
* Email Address
* Residence
* Current Location
* Birthdate
* Age
* Salary
* Employer
* Credit Card Information

###Anonymisation Techniques Used

#### 1. Pseudonymisation

* Replaced the original `customer_id` with anonymous identifiers (`U0001`, `U0002`, ...).

#### 2. Generalisation

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

#### 3. Removal of Sensitive Information

The following fields were removed to protect customer privacy:

* Original Customer ID
* Username
* Name
* Email Address
* Residence
* Current Location (GPS Coordinates)
* Birthdate
* Employer
* Credit Card Provider
* Credit Card Number
* Credit Card Security Code (CVV)
* Credit Card Expiry Date

### Final Dataset

The anonymised dataset contains only the following fields:

* anonymous_customer_id
* date_registered
* gender
* job
* Age Group
* Salary Bracket

### Tools Used

* Microsoft Excel

### Learning Outcomes

This project demonstrates practical application of data privacy principles, including:

* Data anonymisation
* Pseudonymisation
* Data generalisation
* Data minimisation
* Protection of Personally Identifiable Information (PII)
* Preserving analytical value while safeguarding sensitive information

### Project Outcome

The resulting dataset is suitable for data analysis while significantly reducing the risk of identifying individual customers. The anonymisation process follows best practices for handling sensitive data and demonstrates techniques commonly used in data science and data governance.
