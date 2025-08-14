# Power-BI-Phishing-Campaign-Analysis

## Project Overview

Phishing is one of the most common and costly cybersecurity threats because it targets people rather than systems. This project uses Microsoft Power BI to turn raw phishing campaign data into interactive dashboards that show where the risks are, who is most vulnerable, and whether training is working.The dataset contains records for 30,000+ simulated phishing emails across departments and locations in Victoria, Australia. After cleaning, modelling, and visualising the data in Power BI, the dashboards provide clear findings that both technical and non-technical stakeholders can act on.

---
## Dashboards Provided
1. **Campaign Manager Dashboard** – Tracks phishing campaign performance across departments and locations.
2. **Individual User Dashboard** – Analyses user behaviour, training completion, and risk scores.
3. **HR Manager Dashboard** – Breaks down vulnerability by role, department, and geography, and shows training impact.
---
## Skills Demonstrated
- **Power BI dashboard design** with filtering, drill-through, and cross-highlighting
- **Data modelling** across multiple datasets for a unified analysis view
- **Storytelling with data** to translate metrics into decisions
- **Cybersecurity risk analysis** using behaviour-based indicators
---
## Objectives
1. Show campaign managers which phishing campaigns and departments are most at risk.
2. Help HR evaluate training effectiveness and identify underperforming teams or roles.
3. Enable targeted interventions by revealing user-level risk patterns and scores.
---
## Detailed Dashboard Descriptions
### **Campaign Manager Dashboard**
<img width="1141" height="634" alt="image" src="https://github.com/user-attachments/assets/8028d07c-2c2a-47ec-8e38-06d4157555cf" />

### Emails Sent vs Emails Opened by Department
The Finance department received approximately 6,000 phishing emails and opened around 4,000 of them, giving a 67% open rate. Marketing followed closely, with about 5,500 emails sent and 3,800 opened (≈69%). Sales and IT showed slightly lower engagement, while HR had the lowest volume overall. High open rates in Finance and Marketing indicate greater initial exposure risk to phishing attempts, making these departments key targets for awareness and prevention efforts.

### Geographic Distribution of Link Clicks
The map visualisation shows that Melbourne recorded the highest number of phishing link clicks (20), followed by Geelong (15), Ballarat (10), and Bendigo (8). The concentration of clicks in metropolitan areas suggests that phishing campaigns may be more effective where there are larger employee clusters. These locations should be prioritised for targeted training and simulated phishing exercises.

### Breakdown of Clicks, Downloads, and Reports
The pie chart reveals that 68% of recorded interactions involved clicking phishing links, 31% involved downloading malicious attachments, and only 1% resulted in phishing reports being submitted. This disparity shows that while risky behaviours are common, actual incident reporting remains extremely low. Bridging this gap is critical for reducing the impact of phishing attacks and improving organisational response times.

### Reported Phishing vs Employee Count by Department
The treemap highlights that Finance and Marketing departments have the highest number of phishing reports in proportion to their employee counts, while IT, Sales, and HR have notably fewer reports. This suggests possible underreporting in technical and administrative areas, which may indicate either overconfidence in identifying threats or gaps in awareness about reporting procedures.

### Reported Phishing vs Compromised Accounts by Department
The line chart compares the number of phishing reports against the number of compromised accounts. IT stands out with around 20 compromised accounts but relatively few phishing reports, signalling a dangerous gap in incident awareness or willingness to report. Finance shows a higher report rate relative to compromised accounts, suggesting better vigilance, while HR and Sales show both low reporting and moderate account compromise rates.


### **Individual User Dashboard**
<img width="1139" height="606" alt="image" src="https://github.com/user-attachments/assets/b316e0b8-41d1-472a-a7db-712b9e650197" />

This dashboard turns simulated phishing data into clear insights for security teams. Each visual answers a specific question about training, behaviour, and risk so action is obvious.

### 1. Training Completed vs Phishing Reports
This clustered bar chart compares how many employees in each department completed phishing awareness training and how many reported suspicious messages.  
Operations shows 12 completions and 14 reports, reflecting strong vigilance after training.  
IT records 9 completions yet 17 reports, indicating a strong culture of awareness even with fewer completed modules.  
Finance and HR show moderate completions with lower reporting, suggesting follow through needs improvement.  
Marketing completes 5 modules and files 8 reports, showing engagement but leaving room to lift both metrics.  
Overall, training supports reporting, but department culture and processes also drive results.

### 2. Employee Tenure vs Risk Score
This line chart plots average tenure alongside total phishing risk by department.  
Finance and Operations carry the highest risk, close to one thousand points, despite longer average tenure.  
IT records the lowest risk at about six hundred with shorter tenure, pointing to strong practices and reinforcement.  
Sales, HR, and Marketing sit in the middle.  
The pattern shows experience alone does not lower risk and regular refreshers are essential.

### 3. Link Click Distribution
This pie chart shows the share of clicked phishing links by department.  
Marketing accounts for twenty seven percent of all clicks, Finance twenty three percent, and Sales twenty percent.  
HR contributes eighteen percent, while IT and Operations are lowest at seven and five percent.  
Clicks are concentrated in three teams, which should be first in line for targeted coaching and realistic simulations.

### 4. Departmental Risk Scores
This horizontal bar chart ranks total risk by department.  
Finance is highest at roughly one thousand fifty, Operations next at about one thousand, followed by Marketing near eight hundred fifty.  
HR and Sales sit in the middle band.  
IT is lowest, confirming the trend from other visuals.  
This ranking provides a clear order for prioritising awareness campaigns and policy enforcement.

### **HR Manager Dashboard**
<img width="1046" height="603" alt="image" src="https://github.com/user-attachments/assets/7fb1ad09-d1a4-4151-a9e2-f8f0aafea04e" />

### Link Clicks vs Training Completion by Department
The Marketing department recorded 18 phishing link clicks despite completing 16 training modules, showing a near one-to-one ratio between completions and risky interactions. IT registered 14 clicks but only 7 completions, suggesting a significant training gap. Finance recorded 8 clicks against 9 completions, showing a slightly better balance. This variation indicates that training impact differs across departments, and completion alone does not guarantee lower click rates.

### Phishing Reports by Department
HR emerged as the top reporter with 16 phishing incidents, followed closely by Marketing with 15, IT with 13, and Finance with 9. These figures highlight that while HR had a high reporting rate, other departments showed varying degrees of engagement in incident reporting, potentially reflecting differences in awareness or organisational culture around security.

### Geographic Mapping of Link Clicks
The geographic visualisation confirmed Melbourne and Geelong as the main hotspots for phishing link clicks. The clustering of activity in these areas suggests that employee concentration and possibly regional targeting may be influencing phishing success rates.

### Clicks by Department and Role
When clicks are broken down by role, Coordinators accounted for 16 clicks, Recruiters for 15, Specialists for 11, Managers for 8, and Assistants for 6. These insights reveal that certain roles—particularly those with frequent communication responsibilities—remain more vulnerable to phishing attempts. This data can guide role-specific awareness training to address these higher-risk groups.

---
## Key Outcomes
- **High-risk departments**: Finance, Marketing, and Sales account for roughly **70%** of all phishing link clicks.
- **Hotspot locations**: Melbourne and Geelong contribute **~43%** of total clicks.
- **Training gaps**: Some teams still click frequently despite completing training, indicating the need for more scenario-based, role-specific content.
- **Role-level vulnerability**: Coordinators and Recruiters are more exposed than Managers or Assistants.
- **Low reporting rates**: Fewer than **10%** of phishing emails are reported, allowing threats to go undetected.
---
## How the Project Was Built
1. **Data preparation**: Cleaned and normalised three datasets (Campaign Manager, Individual User, HR Manager) in Excel and Power BI.
2. **Data modelling**: Created relationships on shared keys (e.g., CampaignID, Department, Employee/User IDs) and built calculated columns/measures for rates and risk scores.
3. **Visual design**: Selected chart types to match questions (clustered bars for comparisons, line charts for trends, maps for geography, pies/treemaps for mix and proportion).
4. **Insight development**: Validated figures, compared across departments, roles, and cities, and paired metrics (e.g., opens vs compromises, training vs clicks) to find causation signals.
5. **Action framing**: Converted insights into focused, measurable next steps for security, HR, and departmental leaders.
---

