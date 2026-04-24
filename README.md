🚚 Delivery Performance & Logistics Optimization Analysis
📌 Project Overview

This project analyzes a simulated last-mile delivery dataset to understand the key drivers of delivery delays and evaluate system-level optimization strategies.

The focus is not just on identifying problems, but on testing operational improvements such as rider capacity, demand-based allocation, and order batching.

🎯 Objective

To evaluate how delivery performance changes under different operational scenarios:

Rider capacity constraints
Demand distribution across time periods
Order batching efficiency
System-level workload imbalance
📊 Key Findings (Diagnosis)
Kitchen preparation time is relatively stable across cuisine types and time periods
Delivery delays are not driven by prep time variability
Demand varies significantly across daytime (Morning, Afternoon, Evening, Night)
Rider supply remains fixed (51 riders across all periods), creating structural imbalance
Peak periods experience higher workload pressure per rider
🧠 Analytical Approach
1. Workload Modeling
Defined Orders per Rider as a proxy for system demand pressure
Used annual and segmented demand distributions to evaluate imbalance
2. Sensitivity Modeling
Developed a calibrated coefficient (k = 0.056) to estimate the relationship between workload and delivery time
3. Scenario Testing

Simulated three operational strategies:

Rider capacity expansion
Demand-based rider redistribution across daytime
Order batching (batch size = 3)
⚙️ Key Simulations
🚴 Rider Redistribution
Riders allocated based on demand intensity across daytime
Improved peak-hour balance but limited system-wide impact due to fixed capacity
📦 Order Batching (Batch Size = 3)
Increased rider productivity per trip
Reduced effective workload per rider
Delivered the strongest efficiency gain among tested strategies
📉 Outcome

Combining redistribution and order batching reduced average delivery time to approximately:

~31 minutes

This demonstrates that performance improvements can be achieved without increasing rider headcount, but through better system design.

🧩 Key Insight

Delivery performance is not solely a function of rider quantity, but a combination of:

Capacity allocation
Demand distribution
Operational efficiency (batching)
📁 Project Structure
CSV/               Raw dataset files  
EXCEL/             Analysis workbook  
SCREENSHOTS/       Visual outputs and charts  
README.md          Project documentation  
🛠 Tools Used
Microsoft Excel
Data modeling & simulation
Scenario analysis
Basic operational modeling
🚀 Conclusion

This analysis shows that last-mile delivery performance is primarily a systems problem rather than a single-factor issue.

Optimizing rider allocation and introducing order batching can significantly improve delivery efficiency without proportional increases in operational cost.

📌 Note

This analysis is based on a simulated dataset used for operational modeling and scenario testing.

👤 Author

Mayokun Olayiwola
Data Analyst | SQL | Excel | Power BI

🔗 GitHub: https://github.com/layimayokun/delivery-analysis

🔗 LinkedIn: https://www.linkedin.com/in/mayokun-jide-olayiwola





