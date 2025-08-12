# Power-BI-Phishing-Campaign-Analysis

## Project Overview
Phishing is one of the most common and costly cybersecurity threats because it targets people rather than systems. This project uses **Microsoft Power BI** to turn raw phishing campaign data into interactive dashboards that show where the risks are, who is most vulnerable, and whether training is working.

The dataset contains records for **30,000+ simulated phishing emails** across departments and locations in Victoria, Australia. After cleaning, modelling, and visualising the data in Power BI, the dashboards provide clear findings that both technical and non-technical stakeholders can act on.
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
- <u>Emails sent vs opened by department</u>: Finance opened **4,000 of 6,000** phishing emails (**67%**). Marketing opened **3,800 of 5,500** (**69%**). These high open rates point to elevated exposure.
- <u>Geographic distribution of link clicks</u>: Melbourne **20** clicks, Geelong **15**, Ballarat **10**, Bendigo **8**. Cities with more clicks should be prioritised for awareness campaigns.
- <u>Breakdown of clicks, downloads, and reports</u>: **68%** link clicks, **31%** attachment downloads, **1%** reports. Reporting remains very low relative to risky interactions.
- <u>Reported incidents vs compromised accounts</u>: IT showed **20** compromised accounts with relatively few reports, highlighting a critical awareness gap.

### **Individual User Dashboard**
- <u>Training completion vs phishing reporting</u>: Operations completed **12** modules and filed **15** reports; Marketing completed **5** modules and made **8** reports. Training appears correlated with reporting in some areas, but not all.
- <u>Departmental risk scores</u>: Finance ≈ **1,050**, Operations ≈ **1,000**, Marketing ≈ **850**. Higher scores reflect more risky behaviours and lower reporting.
- <u>Link click distribution</u>: Marketing **27%** of clicks, Finance **23%**, Sales **20%**, HR **18%**, IT **7%**, Operations **5%**. Most clicks are concentrated in three departments.
- <u>Risk score trends by employee tenure</u>: Longer-serving Finance staff showed higher risk scores than new hires, suggesting possible complacency.

### **HR Manager Dashboard**
- <u>Link clicks vs training completion by department</u>: Marketing recorded **18** clicks despite **16** completions; IT recorded **14** clicks with **7** completions; Finance **8** clicks with **9** completions. Training impact varies by department.
- <u>Phishing reports by department</u>: HR reported **16** incidents, Marketing **15**, IT **13**, Finance **9**. Reporting culture differs across teams.
- <u>Geographic mapping of link clicks</u>: Confirms Melbourne and Geelong as hotspots.
- <u>Clicks by department and role</u>: Coordinators **16** clicks, Recruiters **15**, Specialists **11**, Managers **8**, Assistants **6**. Certain roles remain more vulnerable.

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

