# Healthcare-Analysis-Dashboard-Power-BI

![Screenshot 2025-06-06 182733](https://github.com/user-attachments/assets/28c95d90-652c-402d-be69-8f2a7262cbe1)
![image](https://github.com/user-attachments/assets/3791afae-f93d-4350-8590-b9043b1c74df)
**Dataset Overview**

This dataset contains 2,506 records related to hospital visits and patient care management. It captures important information about patients, the departments they visited, staff interactions, treatment costs, feedback, and bed usage. The dataset is structured to help analyze hospital operations, patient experiences, and resource utilization.

**🧾 Sheet 1: Detail data dataset**
| Column Name             | Description                                                 |
| ----------------------- | ----------------------------------------------------------- |
| `Staff_Id`              | ID of the staff attending the patient                       |
| `Bed_ID`                | ID of the bed used (if inpatient)                           |
| `Dpt_ID`                | Department ID the patient was treated in                    |
| `ID`                    | Unique patient ID                                           |
| `Name`                  | Name of the patient                                         |
| `Gender`                | Gender of the patient                                       |
| `City`                  | Patient’s city                                              |
| `State`                 | Patient’s state                                             |
| `Age`                   | Age of the patient                                          |
| `Patient type`          | Inpatient or outpatient                                     |
| `Cases`                 | Type of medical case                                        |
| `Cost of the treatment` | Treatment cost (appears as `treatemencost`)                 |
| `Bed LOS`               | Length of stay in bed (for inpatients)                      |
| `ER_Time`               | Time spent in Emergency Room (in minutes)                   |
| `Date`                  | Date of visit or admission                                  |
| `Feedback`              | Patient feedback (e.g., Fully Agree)                        |
| `Rating`                | Rating (e.g., 1–5 stars)                                    |
| `Age Bucket`            | Age category (e.g., 6-20Y, Below 6Y)                        |
| `Custom`                | Possibly a placeholder/custom note                          |
| `FZ me`                 | Sentiment (e.g., "Postive") – likely meant to be "Positive" |

**🧑‍⚕️ Sheet 2: Staff_Detail**
| Column Name  | Description                              |
| ------------ | ---------------------------------------- |
| `Staff_Id`   | Unique staff ID                          |
| `Staff Name` | Code name or ID for staff (e.g., f1, f2) |

**🏥 Sheet 3: Department**
| Column Name       | Description                                             |
| ----------------- | ------------------------------------------------------- |
| `Dpt_ID`          | Unique department ID                                    |
| `Department_Name` | Name of medical department (e.g., Cardiology, Oncology) |

**🛏️ Sheet 4: Bed_Detail**
| Column Name  | Description                               |
| ------------ | ----------------------------------------- |
| `Bed_ID`     | Unique bed ID                             |
| `Bed Number` | Bed number in the hospital (e.g., X1, X2) |


