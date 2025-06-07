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
| `Cost of the treatment` | Treatment cost                 |
| `Bed LOS`               | Length of stay in bed (for inpatients)                      |
| `ER_Time`               | Time spent in Emergency Room (in minutes)                   |
| `Date`                  | Date of visit or admission                                  |
| `Feedback`              | Patient feedback                         |
| `Rating`                | Rating                                    |
| `Age Bucket`            | Age category                        |
| `Custom`                | Possibly a placeholder/custom note                          |
| `FZ me`                 | Sentiment (e.g., "Postive") |

**🧑‍⚕️ Sheet 2: Staff_Detail**
| Column Name  | Description                              |
| ------------ | ---------------------------------------- |
| `Staff_Id`   | Unique staff ID                          |
| `Staff Name` | Code name or ID for staff |

**🏥 Sheet 3: Department**
| Column Name       | Description                                             |
| ----------------- | ------------------------------------------------------- |
| `Dpt_ID`          | Unique department ID                                    |
| `Department_Name` | Name of medical department  |

**🛏️ Sheet 4: Bed_Detail**
| Column Name  | Description                               |
| ------------ | ----------------------------------------- |
| `Bed_ID`     | Unique bed ID                             |
| `Bed Number` | Bed number in the hospital  |

**PATIENT VIEW**

**✅ Top KPIs (Cards at the Top)**

2506 Total Patients - Shows the overall volume of patients treated.

1679 Admitted - Highlights how many patients required hospitalization.

209 Discharged - Shows patients who were successfully treated and released.

82 ICU - Indicates critical care demand – useful for ICU resource planning.

86 Deaths - Reflects mortality rate, crucial for quality control and review.

1.70 Avg LOS (Length of Stay) - Measures hospital efficiency – shorter stays usually imply better resource usage or milder cases.

**📌 1. Department-wise Patient Detail (Line + Bar Chart)**

Insight:

Shows how many patients were admitted, discharged, sent to ICU, or died in each department.

Identifies departments with high patient loads or high ICU/death counts.

**📌 2. Outpatient vs. Inpatient by Month (Bar Chart)**

Insight:

Tracks monthly trends of patient visits split into outpatient and inpatient.

Helps in staff scheduling, bed management, and predictive planning.

**📌 3. Patient by Age Group (Bar Chart)**

Insight:

Shows patient distribution across age groups.

Useful for targeted healthcare programs (e.g., adolescent health, adult wellness).

**📌 4. Avg LOS by Age Group (Horizontal Bar Chart)**

Insight:

Displays average length of hospital stay per age group.

60+ patients stay the longest (2.00 days), likely due to complexity of conditions.

Helps with bed turnover and long-term care resource planning.

**📌 5. Patient by Gender (Pie Chart)**

Insight:

Shows a nearly equal gender split: 51.08% Female, 48.92% Male.

Indicates balanced healthcare access across genders.

Can support gender-focused program planning.

**📌 6. Total Revenue by City (Map Visualization)**

Insight:

Geographic heat map showing cities contributing the most to hospital revenue.

Useful for market expansion, branch planning, and strategic partnerships.

**HOSPITAL VIEW**

**✅ Top KPIs (Cards at the Top)**

2506 Total Patients - Overall patient volume handled by the hospital.

1679 Inpatient -  High inpatient count indicates substantial use of hospital beds and resources.

827 Outpatient - Shows considerable outpatient visits, implying strong demand for consultation services.

262 Total Staff - Helps measure staff-to-patient ratio, critical for service quality and planning.

65.63 Avg ER Time - Average Emergency Room processing time – valuable for monitoring emergency care efficiency.

$161.41 Avg Treatment Cost - Indicates financial accessibility or burden for patients; useful for pricing and budgeting strategy.

**📌 1. Total Revenue by Age Group (Bar Chart)**

Insight:

The 6–20Y age group contributes the most revenue ($135.96K).

Revenue decreases with older age groups.

May suggest that younger patients either need more services or pay more for specialized care.

**📌 2. Avg ER Time by Department (Horizontal Bar Chart)**

Insight:

OPD Outpatient department has the longest average ER wait time (95.6 mins).

OT and Physical Medicine are fastest.

Highlights departments that need workflow optimization or resource support to reduce delays.

**📌 3. Rating by Age Group (Bar Chart)**

Insight:

Highest satisfaction ratings from 6–20Y (4.89) and Below 6Y (4.65) age groups.

Ratings decrease with age, lowest in 60+Y group (3.87).

Suggests need for improved elderly care experience.

**📌 4. Bed Count (Pie Chart)**

Insight:

61.5% beds are occupied, while 38.5% are available.

Efficient usage, but nearing full capacity – could lead to resource strain if patient load increases.

**📌 5. Treatment Cost and Discharge by Day (Line Chart)**

Insight:

Shows daily trends in treatment costs and discharge rates.

Peaks indicate busy days with high treatment volumes – helpful for staff planning and cost control.

**📌 6. Patient Satisfaction and Feedback (Donut Chart)**

Insight:

Dominated by positive feedback, with very few negative or neutral comments.

Reflects high overall patient satisfaction – a good performance metric.

**📌 7. Doctor Explains Treatment Clearly (Bar Chart)**

Insight:

Majority of patients (1.8K) “Fully Agree” that doctors explained treatment understandably.

Very few selected “Rather Disagree”, “Fully Disagree”, or “Don’t know”.

Strong indicator of effective doctor-patient communication.

**OVERVIEW**

From this Healthcare Dashboard overview, we are telling a data-driven story about how a hospital is functioning — in terms of patients, departments, resources, revenue, and patient satisfaction. Here's what we’re communicating through the dashboard:

**1. Hospital Workload & Efficiency**

The hospital has handled 2,506 patients, with 1,679 inpatients and 827 outpatients.

Average ER time is 65.63 minutes, with some departments (like OPD and Dermatology) taking much longer than others — showing where attention is needed.

**2. Resource Management**

Bed occupancy is at 61.5%, showing the hospital still has room to accommodate more patients if needed.

ICU cases (82) and deaths (86) are relatively low, but important to monitor.

**3. Revenue Trends**

The 6–20 years age group contributes the most revenue ($135.96K), showing where most healthcare activity and spending occur.

Older age groups (60+ years) contribute the least, possibly due to lower treatment rates or limited services utilized.

**4. Patient Satisfaction & Quality of Care**

Overwhelmingly positive feedback is reported.

Most patients (1.8K) say doctors clearly explain treatments, which indicates strong communication practices.

Ratings by age groups also remain high (above 4.5/5 for most), except for seniors (60+ Y) — suggesting room for improvement in elderly care experience.

**5. Daily Trends and Hospital Costs**

Treatment cost and discharge trends show fluctuations, helping management understand patient inflow/outflow and cost spikes.

The average treatment cost is $161.41, which could be compared to industry benchmarks.

**6. Geographical Insights**

Cities like Langford, Cliffside, and Oxford contribute significantly to revenue, which helps in regional performance analysis and expansion planning.

**🧠 Final Message**

The dashboard tells a complete story of hospital operations, patient demographics, performance by department, and overall service quality. It helps stakeholders quickly identify strengths, gaps, and opportunities to improve healthcare delivery.
