# Hospital-Matters

This is an overview of my project,
Tool used: Excel, Power Query, Pivot
Data Dictionary — Doctors Dataset
Column Name	Data Type	Description	Example	Constraints / Notes
doctor_id	String / Text	A unique identifier assigned to each doctor.	DOC0009	Should be unique for every doctor; follows the format DOC + 4 digits.
doctor_name	String / Text	The full name of the doctor.	Dr. Benjamin Manirakiza	Names should ideally use consistent capitalization and should not contain unnecessary leading/trailing spaces.
specialty	String / Text	The medical specialty or area of practice of the doctor.	Cardiology	Categorical field. Examples include Cardiology, Neurology, Pulmonology, Endocrinology, and General Practice.

Business Questions
1. doctor_id

Purpose: Uniquely identifies each doctor.
Example: DOC0009
Data type: Text
Key: Primary/unique identifier
Nulls: Should not contain null values.

2. doctor_name

Purpose: Stores the doctor's name.
Example: Dr. Bertrand Sebazungu
Data type: Text
Nulls: Should not contain null values.
Data quality note: Your dataset has some inconsistent formatting, such as dr. grace kayitare being lowercase and some names having extra spaces.

3. specialty

Purpose: Identifies the doctor's medical specialization.
Example: Cardiology
Data type: Text / Categorical
Nulls: Should not contain null values.
Possible values in this dataset: Cardiology, General Practice, Endocrinology, Pulmonology, Neurology.
Summary


Absolutely. For this dataset, the data dictionary can be kept simple because there are only three columns.

### Data Dictionary — Doctors Dataset


### Field Details

**1. `doctor_id`**

* **Purpose:** Uniquely identifies each doctor.
* **Example:** `DOC0009`
* **Data type:** Text
* **Key:** Primary/unique identifier
* **Nulls:** Should not contain null values.

**2. `doctor_name`**

* **Purpose:** Stores the doctor's name.
* **Example:** `Dr. Bertrand Sebazungu`
* **Data type:** Text
* **Nulls:** Should not contain null values.
* **Data quality note:** Your dataset has some inconsistent formatting, such as `dr. grace kayitare` being lowercase and some names having extra spaces.

**3. `specialty`**

* **Purpose:** Identifies the doctor's medical specialization.
* **Example:** `Cardiology`
* **Data type:** Text / Categorical
* **Nulls:** Should not contain null values.
* **Possible values in this dataset:** Cardiology, General Practice, Endocrinology, Pulmonology, Neurology.


