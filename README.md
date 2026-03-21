# PATIENT-ENGAGEMENT-AND-MISSED-APPOINTMENT-ANALYSIS
Analyzing behavioral patterns to reduce no-shows and improve care continuity for high-risk patients.
## PROBLEM STATEMENT
Remote Health has experienced increasingly missed and cancelled consultations, affecting care continuity, provider utilization, and revenue stability. Missed appointments disrupt operational efficiency and pose significant clinical risk when high-risk patients disengage from care.

This analysis evaluates patient engagement patterns, identifies repeat offenders, assesses consultation-type performance, examines scheduling trends, and integrates findings with health risk stratification from Project 1 to determine combined clinical and operational exposure.

## METHODOLOGY
Consultation data was merged with patient health risk data from Project 1. 
The following engagement metrics were calculated: Completion Rate, Missed Rate, Cancellation Rate, Engagement Score (2 = Completed, 0 = Cancelled, 0 = Missed), Engagement Segmentation, High-Risk Disengagement Identification.
### Rates were calculated as:
Rate = Category Count ÷ Total Appointments
Engagement trends were analyzed by: Patient, Age group. Consultation type, Visit date

## TOOL USED
PowerBI

<img width="975" height="552" alt="image" src="https://github.com/user-attachments/assets/3c8013d0-c3f4-412d-a549-5257b8f49b18" />

## EXECUTIVE SUMMARY
The analysis shows that 43% of consultations were missed and 14% were cancelled, leaving only 43% successfully completed, meaning more than half of all appointments were unsuccessful. One patient (P002) was identified as a repeat offender, and notably, all chat consultations had a 0% completion rate, while physical consultations achieved 100% completion. Additionally, most weekend appointments were missed or cancelled, and one patient was not scheduled at all, indicating a potential care coordination gap. Most importantly, 100% of patients who missed their consultations were classified as High Health Risk, revealing a strong relationship between clinical vulnerability and engagement failure.

## KEY FINDINGS
### 1	Overall Appointment Performance
Out of 7 consultations: 3 Completed, 3 Missed, 1 Cancelled
More appointments were unsuccessful (57%) than completed (43%), signaling engagement instability.
### 2	Patient-Level Engagement
•	Patients who missed appointments: P002 - 2 missed visits (Repeat Offender), P007 – 1 missed visit
•	Additionally, one patient was not scheduled for consultation, indicating a potential gap in proactive scheduling or care coordination.
•	The 40–59 age group recorded the highest missed frequency.

## CONSULTATION TYPE PERFORMANCE
<img width="327" height="59" alt="image" src="https://github.com/user-attachments/assets/1e2d2326-f491-4972-8b8d-b7e9a3469658" />
Chat consultations demonstrate structural engagement failure, while physical consultations show the highest reliability.

## APPOINTMENT TIMING PATTERN
Most consultations scheduled on weekdays were missed or cancelled except Thursday, with weekends showing the strongest completion reliability.
This suggests that scheduling timing may influence attendance behavior and should be strategically optimized.

## HEALTH RISK & ENGAGEMENT INTEGRATION
A critical insight from combining Patient Health Risk Analysis and Statification Project and Patient engagement and missed appointment Analysis Project:
All patients who missed appointments are classified as High Health Risk.
Additionally, most high-risk patients either missed or cancelled their consultations.
This overlap represents dual exposure:
•	Increased clinical emergency risk
•	Reduced operational efficiency
High-risk disengagement is the most urgent intervention priority.

## ENGAGEMENT SEGMENTATION
High-Risk Disengaged: P002, P007
These patients require immediate engagement intervention.
Fully Engaged: P001, P003, P004, P005
These patients demonstrate stable adherence to scheduled consultations.

## BUSINESS IMPLICATIONS
Current engagement patterns indicate:
•	Revenue leakage due to no-shows
•	Underutilized provider capacity
•	Elevated risk for high-risk patients
•	Ineffective chat consultation performance
•	Scheduling gaps for certain patients
Without intervention, these trends may increase emergency events and long-term care costs.

## RECOMMENDATIONS
1.	Implement risk-based reminder system (SMS + phone calls for high-risk patients).
2.	Review and optimize chat consultation processes to improve reliability.
3.	Establish repeat offender protocol with mandatory confirmation after missed visits.
4.	Adjust weekday scheduling strategy or require reconfirmation.
5.	Integrate health risk and engagement metrics into a unified monitoring dashboard for proactive care management.

## CONCLUSION
This analysis demonstrates that disengagement is concentrated among high-risk patients, amplifying both clinical and operational exposure. With a 43% missed rate and complete failure of chat consultations, Remote Health must adopt targeted, data-driven engagement strategies.
By integrating health risk stratification with behavioral analytics, Remote Health can improve care continuity, reduce emergency risk, enhance provider efficiency, and strengthen revenue stability.






