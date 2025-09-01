## 1.0 Introduction

This report presents a quantitative analysis of data collected from a survey of 100 IT and cybersecurity professionals in the Australian healthcare sector. The objective of our research was to answer the following question: **"How can AI and machine learning improve the detection and mitigation of cyber-attacks, such as phishing and ransomware, within hospital information systems?"**

To address this, our analysis is structured into two main parts. First, a descriptive analysis was conducted to summarize the overall trends and perspectives captured in the survey. Second, a comparative analysis was performed to explore the relationships between different variables and uncover deeper insights into the data.


---

## 2.0 Methodology

As outlined in the course materials for this unit, our project followed a quantitative research strategy. We used a survey to collect primary data, which was then analyzed to identify patterns and draw conclusions.

* **Data Source:** The dataset consists of 100 responses from our survey, which was distributed online to a targeted sample of professionals.
* **Analysis Tool:** All data processing and visualization were conducted using **Microsoft Excel**.
* **Analytical Techniques:**
    * **Descriptive Statistics:** We used **PivotTables** in Excel to calculate frequencies (counts) and percentages for each survey question. This allowed us to summarise the main features of the data.
    * **Correlation & Comparative Analysis:** To investigate the relationships between different variables, we used **cross-tabulation** to compare the responses of different groups. This technique helps to infer relationships and draw more nuanced conclusions from the data.

---

## 3.0 Descriptive Analysis of Overall Findings

This section presents the overall results for each of the seven closed-ended questions in our survey.

### 3.1 Respondent Demographics: Current Role

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/e308e801-d9ad-490d-8e41-99c01e1a52ed" />

**Interpretation:** The sample provides a strong operational perspective, with 71% of respondents being frontline staff (Analysts and Other IT Staff). The remaining 29% consist of management and leadership roles, allowing for a useful comparison between strategic and operational viewpoints.

### 3.2 Current Use of AI/ML Tools

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/2b1156fc-eb5d-4dd2-9a85-03226a4bc79d" />


**Interpretation:** The data shows that AI adoption is low. Exactly half of the organisations (50%) do not use dedicated AI tools. Only 19% have fully implemented them, with a similar number (18%) in the process. This indicates that the industry is still in the very early stages of adoption.

### 3.3 Effectiveness in Detecting Phishing

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/26b53c00-8a44-49b2-a13c-8330057065b6" />



**Interpretation:** A majority of professionals (57%) believe AI is more effective than traditional methods at detecting phishing. However, a significant portion (37%) feel it is only about the same or less effective, suggesting that opinions on its value are positive but not universally shared.

### 3.4 Speed Against Ransomware

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/c9c5ef71-7da8-47bd-b8a7-0e046a591631" />


**Interpretation:** There is a high degree of uncertainty regarding AI's automated defense capabilities. The largest group of respondents (45%) is neutral on the topic. While 42% agree that AI is fast enough, the overall sentiment is one of caution and a lack of conviction.

### 3.5 Biggest Adoption Challenge

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/6cccbabf-81cc-402e-a69a-cbba50be1517" />


**Interpretation:** The primary barriers to AI adoption are clearly financial and technical. **'The high cost' (44%)** is the most significant obstacle, followed closely by **'Problems with existing systems' (31%)**. Together, these two factors account for 75% of the challenges cited.

### 3.6 Most Urgent Security Alert

| Alert | Count | Percentage |
| :--- | :--- | :--- |
| Phishing attempt detected | 44 | 44% |
| Ransomware activity suspected | 32 | 32% |
| Network intrusion alert | 19 | 19% |
| Suspicious user login | 5 | 5% |

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/e74c2168-274c-49ce-9de6-bb678eab165a" />


**Interpretation:** Professionals prioritize alerts that signal a severe and immediate threat. **'Ransomware activity suspected' (36%)** is ranked as the most urgent, reflecting its potential to cause catastrophic operational disruption to patient care.

### 3.7 Impact on Investigation Time

| Response | Count | Percentage |
| :--- | :--- | :--- |
| Yes, a little time | 55 | 55% |
| Yes, a lot of time | 23 | 23% |
| No, it's about the same | 18 | 18% |
| No, they create more work | 4 | 4% |

<img width="500" height="500 alt="image" src="https://github.com/user-attachments/assets/368ceb99-dc32-4317-ab20-e9cddf9bf1ab" />


**Interpretation:** AI tools are widely seen as an efficiency benefit. A combined **71%** of respondents report that AI saves their team time. However, the fact that the majority only save 'a little time' suggests that these efficiency gains may be modest, possibly offset by the need to manage and validate AI-generated alerts.

---

## 4.0 Comparative Analysis

Our analysis revealed a notable difference in opinion between strategic leadership roles and frontline operational staff regarding AI's ability to stop ransomware.

### 4.1 The "Confidence Gap": Role vs. Belief in Ransomware Defense
A cross-tabulation of professional roles against their confidence in AI's speed reveals a significant difference in perspective between strategic leaders and frontline staff.

<img width="1200" height="800" alt="Code_Generated_Image (1)" src="https://github.com/user-attachments/assets/ad355ada-f809-4fd0-9b61-ed469beb0f95" />


**Finding:** The data shows what can be described as a "confidence gap." Senior roles (CISOs and Managers), who are often responsible for the strategic decision to purchase technology, showed much higher levels of agreement that AI is fast enough. In contrast, frontline staff (Analysts and Other IT Staff), who manage the technology's daily operations, expressed significantly more uncertainty or disagreement. This suggests a potential disconnect between the strategic perception and the operational reality of AI's performance.

### 4.2 The Efficiency Problem: Challenges vs. Time Saved
We also investigated whether the challenges faced by an organisation were related to the efficiency gains they experienced from AI.

<img width="1200" height="800" alt="Code_Generated_Image" src="https://github.com/user-attachments/assets/8e28f44d-b668-442d-9c04-a78ae9fd8f0c" />


**Finding:** There appears to be a strong relationship between integration issues and a lack of efficiency. Respondents who cited 'Problems with existing systems' as their biggest barrier were far more likely to report that AI saves no time or even creates more work. This finding is critical, as it suggests that without proper integration, the investment in an AI tool may fail to deliver on its promise of efficiency.

---

## 5.0 Thematic Analysis of Qualitative Data

The open-ended responses provided important context to the quantitative data. Three key themes were identified:

* **Theme 1: The Need for Explainability and Transparency:** A lack of trust in "black box" AI was a common concern. Professionals need to understand *why* a tool flags a threat before they can take action, especially in a clinical setting. As one respondent stated, *"AI still feels like a black box. We need explainable AI to trust its decisions fully."*
* **Theme 2: Cost and Resource Barriers:** The high cost of AI tools was a dominant theme, which respondents noted creates a security divide between large, well-funded hospitals and smaller ones. One professional said, *"The upfront cost of AI systems is high, making it hard for smaller hospitals."*
* **Theme 3: The High Stakes of False Positives:** In a hospital, a false alarm is not just an inconvenience; it can directly impact patient care by disrupting critical workflows. This was summarized well by one participant: *"Automation is useful, but in healthcare, false quarantines risk disrupting patient care."*

---

## 6.0 Discussion and Implications

The combined analysis paints a clear picture of cautious optimism versus practical reality. While IT professionals in healthcare recognise the potential of AI to be more effective than traditional tools, its adoption is being slowed by the significant real-world constraints of high costs and complex technical integration.

The "confidence gap" identified between leadership and frontline staff is a key finding, suggesting that strategic expectations of AI may not always align with operational experiences. Furthermore, the strong relationship between integration problems and a lack of efficiency gains implies that simply purchasing an AI tool is not a sufficient solution; without proper implementation, it may not provide the expected benefits.

Finally, the qualitative feedback underscores a critical requirement for the healthcare sector: trust. The demand for "explainable AI" shows that in a high-stakes environment where errors can affect patient safety, transparency is just as important as technical capability.

---

## 7.0 Conclusion and Recommendations

In conclusion, our research indicates that while AI/ML can improve hospital cybersecurity, its full potential is currently limited by financial barriers, technical challenges, and a need for greater trust.

Based on our analysis, we offer two recommendations:

1.  **For Hospitals:** We recommend that organisations prioritise infrastructure modernization alongside the procurement of new AI security tools. A holistic approach that plans for integration from the start is necessary to maximize the return on investment and achieve real efficiency gains.
2.  **For AI Vendors:** We recommend a focus on developing "explainable AI" (XAI) features that provide clear and simple reasoning for security alerts. This is critical for building trust and ensuring the safe and effective adoption of these tools in the risk-averse healthcare sector.
