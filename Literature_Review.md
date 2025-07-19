Literature Review: **Emerging Technologies and Cybersecurity Challenges in Healthcare**   By: Nabaraj Dahal


**1.	The Evolving Threat Landscape in Healthcare**
The sensitivity of patient information and vital medical facilities exposes the healthcare organizations to extreme cyber threats.
The most serious are:

•	**Ransomware:** Ransomware tends to dominate the healthcare cyberattack and cripples services (e.g., delayed surgeries), causing a threat to patient safety.

•	**Phishing & Social Engineering:** Phishing is still among the leading vectors of attack, and spear phishing, and clone phishing use trusted channels to acquire credentials.

•	**IoT/Medical Device Vulnerabilities ("Medi-Jacking"):** Infected IoT device (e.g. infusion pump, pacemaker) can be controlled remotely, a potentially life challenging issue.

• **Data Breaches:** If the Electronic Health Records (EHRs) access is not authorized, data breaches continue to occur thanks to certain third-party breaches and ransomware-based theft.
•	**DDoS Attacks:** These strike with the aim to overload networks leading to outages that slow the process of accessing patient records and apps that are critical.

**2.	Emerging Technologies for Cyber Defence**

• **Block chain:** Tamper resistant storage of health records, more integrity of information and patient privacy. It decreases the attack zones that are centralized and facilitates the sharing of data in a secure way.

•	**Artificial Intelligence (AI) & Machine Learning (ML):**

o **Anomaly Detection:** AI keeps watch over the traffic in networks to signal malicious threats in real-time (e.g. ransomware patterns).
          
o **Predictive Defence:** ML identifies attacks based on the past attacks.
          
o **Phishing Mitigation:** AI is capable of detecting malicious email texts with high success rate.
          
•	**Cloud Computing:** Provides scalable security, automatic updates and solid disaster recovery. Its decentralized storage prevents the effects of DDoS and ransomware.

•	**Homomorphic Encryption:** Has the ability to compute on encrypted data, hence privacy preserving analytics.

**3.	Regulatory Frameworks and Risk Management**

Standards are critical for systematizing defences:

•	**NIST Cybersecurity Framework and ISO 27001:** Offer a patterned methodology in risk analysis, access administration and HIPAA conformity.

•	**Zero-Trust Architecture (ZTA):** Tests each user / devices prior to enabling their access to the data, thus reducing the risks of breaches.

•	**Integrated Risk Models:** Insert the data about the threats and vulnerability to IoMT and cloud topologies.


**4.	Persistent Challenges and Research Gaps**

Key unresolved challenges include:

•	**Unsecured resource-challenged medical devices**Image-based medical devices do not have inherent security.

•	**Interoperable vs. Security**Interoperable data can bring security challenges opposite enduing architecture constraints.

•	**Human Factors:** Lack of Staff training exposes them to social engineering.

•	**The Ever-Changing Threat:** AI-enabled attacks and Ransomware-as-a-Service (RaaS) have outlawed the traditional defenders.

**5.	Conclusion**
Although block chain, AI, and zero-trust architectures can provide strong protection against the healthcare cyber threats, the implementation of these strategies needs coordination with the standards related to regulatory frameworks, such as HIPAA, and vulnerabilities that may manifest in human beings. Lightweight IoMT security, threat hunting powered by AI, and uniform frameworks of cross-institutional data sharing are on the agenda in the future. Multi-layered adaptive security ecosystem should be used to protect the digital future of healthcare.

---
---


Literature Review: **The Role of Implementing Machine Learning Approaches in Enhancing the Effectiveness of Healthcare Services** By:**Abhishek Maharjan**

**1.	Introduction to Machine Learning in Healthcare**
•	What it is and why it's important: Machine Learning (ML) is a new technology that helps us understand massive data better, especially in the health field.
•	Uses: ML helps people make better decisions in many areas, such as:
•	Disease assessment and treatment predictions
•	Pharmaceutical product development
•	Biomarker recognition
•	Patient monitoring and management
Current Trends: The Internet of Things (IoT) and machine learning (ML) are changing healthcare by making it possible to provide customized care and use predictive analytics.

**2.	How Machine Learning Affects Healthcare Services**
          • Use of Data: The amount of data in healthcare is growing quickly, thus it needs to be analyses quickly to improve patient outcomes.
          • Health prediction systems say that ML algorithms can handle unexpected changes in patient flows, including those that happen during disasters or calamities.
          • Results of the survey:   The study included 78 medical professionals and found:
          • 64% of people said that IoT and ML are often used in healthcare.
          • 75% agree that ML algorithms can help find cancerous tumors early.


**3.	Putting Machine Learning into Action Is Hard**
•	Quality and Understandability of Data: The data must be of high quality and the methods must be simple to grasp for machine learning to operate.
•	Trust Issues: Healthcare practitioners often have trouble trusting machine learning models since they are hard to understand.
•	Integration with Current Systems: Machine learning solutions are still hard to connect to the healthcare systems that are already in place.

**4.	How Machine Learning Can Help Healthcare**
•	Personalized Healthcare: Machine learning makes care better by letting doctors create treatment plans that are specific to each patient.
•	Predictive analytics: Machine learning (ML) makes it feasible to act before a medical emergency happens by anticipating what patients will need and what might happen.

**5.	 Conclusion and What to Look Forward to in the Future**
The Potential of Machine Learning: Using ML in healthcare could make services and patient outcomes far better. To guarantee that machine learning is used responsibly and successfully resolves problems, cooperation between data scientists, regulators, and healthcare professionals is crucial.
Future study: More study is needed to properly understand how machine learning could be used in healthcare. This study should be focused on making users more trusting, algorithms more open, and data better.

---
# Paper 3: Deep Learning-Driven Cybersecurity Threat Detection and Mitigation in Saudi Arabia Healthcare System


### **Summary**
This study addresses the escalating cybersecurity risks in the Saudi Arabian healthcare sector, amplified by the digital transformation initiatives of Saudi Vision 2030. The authors propose and evaluate a hybrid deep learning model to provide a proactive defense mechanism against cyber threats like ransomware, phishing, and malware. The research provides a tailored solution that considers the specific regulatory and operational landscape of the region.

---

### **Key Findings and Methodologies**

* **Methodology:** The core of the research is a hybrid deep learning model combining **Convolutional Neural Networks (CNNs)** with **Bidirectional Long Short-Term Memory (Bi-LSTM)** networks.
    * CNNs are used to extract spatial features and detect attack patterns from system logs and IoT device communications.
    * Bi-LSTMs analyze sequential data, like network traffic logs, to identify temporal patterns and evolving threats.

* **Key Findings:** The model demonstrated high effectiveness in identifying and classifying threats.
    * It achieved an overall accuracy of **94%**.
    * It showed excellent performance against critical threats, with **100% accuracy for ransomware** and **96.19% accuracy for phishing**.
    * The system automates mitigation recommendations based on threat severity (Low, Medium, High).

### **Research Gaps and Unresolved Issues**

The paper highlights several key limitations and areas for future work:
* **Insider Threats:** The model struggles to detect subtle threats originating from within the organization.
* **Model Interpretability:** The system lacks transparency, making it difficult for professionals to trust its decisions. The paper recommends integrating **Explainable AI (XAI)** to improve clarity.
* **Data Dependency:** Performance relies heavily on high-quality, healthcare-specific datasets.
* **Real-Time Scalability:** Deploying the model in large-scale environments requires advanced computational strategies.

### **Contribution to Research**
This paper provides a validated proof-of-concept for a hybrid AI model in a hospital setting. It demonstrates a comprehensive framework that includes detection, severity classification, and mitigation recommendations. By focusing on a specific region, it also highlights the need for tailored cybersecurity solutions and pinpoints crucial directions for future research.

---
# Paper 4: Influence of Ransomware Attacks in the Healthcare Industry
### **Summary**
This paper provides a comprehensive overview of the severe and growing threat that ransomware poses to the healthcare industry.The authors argue that healthcare organizations are prime targets due to a combination of factors: they often operate with underfunded and outdated IT systems, they lack sufficient technical staff, and their continuous operation is critical for patient care. The study uses recent statistics and highlights major case studies to demonstrate how these vulnerabilities are exploited by Ransomware-as-a-Service (RaaS) groups, leading to devastating impacts on patient health, safety, and data privacy.

---

### **Key Findings and Methodologies**

* **Methodology:** The research is a qualitative analysis based on a review of existing literature, cybersecurity industry reports (primarily from ENISA), and prominent case studies of ransomware attacks. It synthesizes this information to build a case for the severity of the problem.

* **Key Findings:**
    * Ransomware is the second most common threat to the healthcare sector, accounting for 26% of all cyber incidents analyzed by ENISA between July 2023 and June 2024.
    * The rise of the "Ransomware-as-a-Service" (RaaS) model allows less-skilled criminals to launch sophisticated attacks, with major groups like LockBit and ALPHV/BlackCat responsible for 30% of healthcare attacks in 2023.
    * Many healthcare facilities are unprepared; a study found over 80% lack a ransomware-specific incident response plan, and 40% have no security awareness program for staff.
    * The consequences are dire, leading to delayed patient care, higher mortality rates, and enormous financial costs, with the average remediation cost exceeding $5 million.
    * Initial access for attackers is often achieved through simple exploits, such as an employee opening a malicious email or the compromise of an account that was not protected by two-factor authentication.

### **Research Gaps and Unresolved Issues**

The paper points to several critical challenges:
* While new EU regulations like NIS2 provide a framework for security, many healthcare institutions may not have the financial resources or in-house expertise to implement the required measures.
* Dedicated support structures, like the EU's Cybersecurity Support Centre, are still in development and not yet fully implemented, leaving an immediate support gap.
* Academic research specifically on the effects of ransomware on healthcare was "sparsely researched" until a recent increase in interest, indicating the field is still developing.
  
### **Contribution to Research**
This paper does not propose a new AI solution. Instead, its primary contribution is establishing the critical context and justification for our research question. It contributes by:
* **Detailing the Problem:** It thoroughly documents the "why" and "how" of ransomware attacks in healthcare, providing strong evidence that new defensive solutions are urgently needed.
* **Identifying Key Vulnerabilities:** It highlights specific weaknesses (e.g., outdated software, lack of staff training, weak authentication) that an AI-driven detection and mitigation system could be designed to address.
* **Quantifying the Impact:** It provides recent, compelling statistics on the financial and human cost of these attacks, reinforcing the importance of developing effective countermeasures like those proposed in your research.

---
# Paper 5: Machine Learning-Based Methodology for Preventing Ransomware Attacks on Healthcare Sector
### **Summary**
This paper proposes a direct, machine learning-based solution to defend hospital networks from ransomware. The authors' core idea is to place a dedicated, ML-trained server in the network path to act as a security checkpoint. This server's job is to inspect incoming data packets and, using a trained algorithm, identify and block malicious ones before they can reach the critical hospital infrastructure.After comparing several common machine learning models, the research concludes that the Random Forest algorithm is the most effective and accurate for this task.

---

### **Methodology and Key Findings**

The study's approach was to design and test a practical defense architecture for a healthcare network.

* **Proposed Architecture:** They designed a layered defense where all internet traffic must first pass through a standard firewall and then through their specialized "ML Trained System" before being allowed to access the main hospital server.
* **Machine Learning Models:** The research focused on comparing the performance of three different algorithms for the detection task:
    * Support Vector Machine (SVM) 
    * Logistic Regression 
    * Random Forest Classifier (RFC) 
* **Dataset:** They trained and tested their models using a pre-processed dataset from the Canadian Institute for Cybersecurity, which contained a mix of 3,700 ransomware and 9,980 benign software samples.
* **Top Performing Model:** The results clearly showed that the **Random Forest** algorithm was the superior choice.
    * It achieved an impressive accuracy of **99.79%** in detecting ransomware.
    * This was higher than both SVM (99.24%) and Logistic Regression (99.30%).
    * Crucially, Random Forest had the lowest error rates, with only 4 false positives and 15 false negatives in the test set, making it the most reliable.



### **Identified Gaps and Limitations**

The authors were upfront about the conditions that influenced their strong results.

* The research highlights that traditional antivirus tools are often not successful against new and unknown malware, a gap this kind of ML-based behavioral analysis aims to fill.
* A key limitation noted in the paper is its reliance on a very clean, pre-processed dataset. The authors acknowledge that the model's accuracy might be different when used on messy, "uncleaned" data from a real-world network.



### **Contribution to Research**
* It provides a **specific and tested blueprint** for an ML-based ransomware defense system within a healthcare setting.
* It offers a clear, evidence-based recommendation for using the **Random Forest** algorithm over other common models for this specific security task.
* The work demonstrates a **proactive prevention strategy**, focusing on blocking threats before they can do damage, rather than just detecting them after the fact.
* It provides a strong, quantitative answer to *how* effective ML can be, with a **99.79% accuracy** metric serving as a powerful benchmark.

---
# Paper 6: Ethical & Legal Concerns of Artificial Intelligence in the Healthcare Sector
### **Summary**
This paper shifts the focus from the technical implementation of AI to the critical ethical and legal challenges that arise when these technologies are used in healthcare. The study specifically investigates the situation in Jordan, using a focus group of legal, medical, and IT experts to understand the current landscape. The key takeaway is that while the Jordanian government and hospitals are eager to adopt AI, the country's legal system has not kept pace. It lacks a specific, dedicated law to govern AI, creating significant uncertainty and risk. The authors strongly recommend developing more comprehensive laws and prioritizing ethics training for all healthcare staff who use AI tools.

---

### **Methodology and Key Findings**

The research was conducted as a qualitative study to gather expert opinions on the core issues.

* **Methodology:** The authors used a Focus Group Discussion (FGD) as their primary method for collecting data. The group consisted of six experts: two from the legal field, three medical practitioners, and one IT professional from a major hospital.
* **Lack of Specific AI Regulation:** A central finding from the discussion was that Jordan currently has no "special law" designed specifically to regulate AI systems. While there are general data protection policies, these are not sufficient for the complexities of AI.
* **Gap Between Technology and Law:** The participants agreed that a major challenge is that technology is changing much faster than the policies meant to govern it.
* **Patient Trust:** Medical practitioners in the group noted that patients still have significant fears about their privacy and the potential for their personal information to be disclosed by AI systems.
* **Need for Training:** A consensus among the experts was that extensive ethical and legal training for hospital staff is essential to safely implement AI and mitigate potential risks.

### **Identified Gaps and Limitations**

The study effectively highlights the non-technical gaps that can prevent successful AI adoption.

* The most significant gap is the absence of a robust legal framework in Jordan specifically designed for AI, which creates a risky environment for both patients and providers.
* The paper points to other practical barriers to AI integration in the region, including high operational costs, a lack of skilled employees, and inadequate infrastructure.
* It also touches on the potential for conflict between broad ethical principles and the specifics of legal compliance, a complex area that needs to be navigated carefully.

### **Contribution to Research**

This paper's contribution is not technical but provides crucial **socio-legal context** for our research question.

* It makes a strong case that technical solutions for cybersecurity are only one part of the puzzle. Any AI system, no matter how accurate, will fail if it doesn't address legal and ethical concerns.
* It highlights the importance of **data privacy and patient trust**, key considerations for any AI security tool that handles sensitive medical records.
* It emphasizes the "human factor," showing that the successful deployment of an AI system depends heavily on **staff training and institutional policy**. This adds a critical, non-technical dimension to the problem of improving cybersecurity.
---
# Paper 7: Digital Health: The Cybersecurity for AI-Based Healthcare Communication
### 
**Summary**

This paper discusses AI-driven healthcare system communications regarding cybersecurity because it should focus on responding to the threats such as ransomware proactively. It offers the JOINER framework- it is a policy-based solution that bonds Explainable AI (XAI) and federated learning to protect communication hubs. This study brings to light the importance of protecting the healthcare infrastructure, in particular, during the digital transformation efforts governed by Saudi Vision 2030, and provides a theoretical design that fits the expectations of a changing threat landscape.

****Key Findings and Methodologies**

**Methodology:**

• Puts forward the JOINER framework (Joint, Optimized, Infrastructure, Network, Empowered, Research) on end-to-end secure communication.

• Uses XAI and federated learning (FED-XAI) in order to support collaborative AI training without compromising privacy of data.

• Installs measures of proactive security (e.g., happiness wall/secrecy rate monitoring, hub authentication) against ransomware.
         
         

**Key Findings:**

• The theoretical performance measures are better than current systems (e.g., data rate >200 Gbps, latency <0.1ms, reliability 99.9%, see Table 3).

• JOINER allows security orchestration of the tasks, adapting to the level of threat.

 • Ransomware backups Offline Ransomware resilience requires offline backups.
         
         
**Research Gaps and Unresolved Issues**

 • **Insider Threats:** Low capability of detection of malicious actors within the company.
 
 • **Real-Time Scalability:** Scalability in high hardware requirements in large deployment can be problematic.
 
• **Model Interpretability:** Although XAI is implemented, there remains a lack of trust over AI-based decisions.

 • **Ethical Issues:** Gender Bias in the Collection of AI Data and Algorithms Transparency.
 
 • **Cost-Quality Trade-offs:** Reimbursement schemes (e.g. fee-for-service) overlook the concept of quality of security, subjecting them to attacks.
 
         
**Conclusion**

In the paper, a conceptual blueprint of policy-centric cybersecurity in AI-based healthcare communications is presented whose gaps can be filled by technical and governance barriers. It also combines JOINER and XAI in a unique way to fit region-specific requirements within Saudi vision 2030, besides the identification of gaps in ethics, scalability as well as reimbursement to be worked on in the future.

---
# Paper 8: Assessment of the Impact of Cyber-Attacks and Security Breaches in Diagnostic Systems on the Healthcare Sector
### 

**Summary**

This study assesses the operational implication of the ransomware attack on hospitals with a focus on the interference of the diagnostic systems. It employs simulation of 231 node network representing a hospital using an agent based simulation (CaESAR) to measure resilience measures during a cyber-attack. The study reveals the frequency of enhanced vulnerabilities caused by legacy systems and how training of the staff and fast IT recovery contributes largely to a shorter recovery period. Operating on the example of European healthcare cases (e.g., Ireland HSE attack), it offers an outline of how hospitals can maximize their resource levels and incident-response rates.

**Key Findings and Methodologies**

**Methodology:**

• The hospital components can be modeled into various nodes, which are having interconnections with the other nodes (agent-based simulation, e.g., CaESAR).

• Two conditions: Unprepared (A) vs. prepared and mitigation measures (B).

• Resilience measures: R1 (Minimum performance), R2 (Minimum performance time), R3 (Recovery time), R4 (Total loss of performance).

**Key Findings:**

• **Scenario A (no protocols):** Performance decreases down to 3.8%, and it requires 40.2 days to go back to the normal (Table 2).

• **Scenario B (with training/backups):** The performance suffers to 61.1%, and restores in 8.7 days.

• Training the staff eliminated mistakes when handling operations manually; the 5 days IT restoration was critical to continuity.

• Diagnostic systems that would have the greatest impact as a point of failure (cascading to 80 percent of nodes).

**Research Gaps and Unresolved Issues**

• **Integrations with legacy systems:** The assumption is that all the nodes are equally vulnerable; legacy heterogeneity not taken into account.

• **Patient Impact Simplification:** Deterioration of patient status has a binary variable form (critical/non-critical); is not clinically specific.

• **Financial Quantification:** Means that business effect (that is, loss of revenue) not calculated.

• **Total AI Integration Gap:** There is no synergy with AI-based detection (solutions of Papers 3-4).

• **Drill Effectiveness:** Training helps in reducing recovery time and frequency/depth optimum has not been studied.

**Contribution to Research**

The present paper presents a convenient simulation tool (CaESAR) to measure hospital resilience to quantitatively cross the barrier between technical and operational planning of cybersecurity. It is the only means of revealing cascading failure in diagnostic systems, and it empirically confirms the effectiveness of staff training as one of the low-cost mitigations.

---
# Paper 9: The Role of Implementing Machine Learning Approaches in Enhancing the Effectiveness of Healthcare Service
### 

**Summary**

The article is an exploration of Machine Learning (ML) in healthcare with the focus on disease prediction, personalized treatment, and efficiency. Via the survey of 78 people working in the field of healthcare and the analysis of the literature, it confirms the ML contribution to early tumor detection, flow of patients, and integration with IoT. Another major adoption barrier, which the paper brings to the fore, is interpretability barriers, such as "black-box" algorithms, and offers interpretable ML frameworks as solutions to fill clinician trust gaps.

**Key Findings and Methodologies**

**Methodology:**

• Review of the ML in healthcare (therapy, imaging, EHR analysis, drug discovery).

• Quantitative survey (3 closed ended questions) to measure the uptake rolled out in the field.

**Key Findings:**

• The vast majority of professionals (36 percent strongly agree and 28 percent agree) conclude that ML/IoT were widely adopted (Table 1).

• 75.6 percent believe that ML is able to detect malignant tumors early (e.g., skin cancer model that was demonstrated by Stanford; Table 2).

• Two-thirds of respondents have expressed the view that ML averts medical tribulation using safe services (Table 3).

• CNN results in a higher prediction of disease compared to the KNN (94.5%, as opposed to lower), however, clinical interpretation is needed.

**Research Gaps and Unresolved Issues**

• **Interpretability Deficit:** Clinicians do not trust the results of the ""black-box"" ML models; existing solutions, such as XAI, are undeveloped.

• **Data Bias:** Inherently biased training sets can effect the predictions ( e.g., not well represented demographics.

• **Real-World Scalability:** Scanty literature or data on applicability of ML in various and resource-scarce environments.

• **Security Loopholes:** IoT/ML deployment creates vulnerability to data leakage attacks; there is no comprehensive cybersecurity model.

• **Ethical ambiguity:** Decision-making on whether ML errors (misdiagnosis) are accountable is not governed by the law or clinical policies.

**Contribution to Research**

The paper will be an empirical verification of the potential of ML in healthcare in terms of a survey of key stakeholders in addition to theoretical research. It is the first initiative to connect the problem of interpretability to a medical barrier to adoption and compile real-world applications (e.g., diagnostics of tumors, individualized diabetes treatment). It guides future work on the deployment of trustworthy AI by identifying the presence of synergies between IoT and ML and threats to bias.

---
# Paper 10: AI Cyber Security: Enhancing Network Security with Deep Learning for Real-Time Threat Detection and Performance Evaluation
###
**Summary**
This study looks at how AI, specifically deep learning, makes cybersecurity better by letting threats be found and responded to automatically and in real time.  It talks about how new AI methods can help deal with new threats like APTs, encrypted malware, and insider assaults that older methods often miss.

**Key Findings and Methodologies**
**Methodology**:
The study uses several AI technologies together to make networks safer:
  • Natural Language Processing (NLP) helps you go through system logs to find information about threats.
  • Big Data Integration: Makes it possible to find correlations and dangers in big databases.
  • Real-Time Response: Uses AI to change the flow of traffic and protect endpoints that are in danger.

**Key Findings**:
   • AI makes it much easier to find threats.
   • It lets security breaches be fixed automatically and in real time.
   • More people are using AI in cybersecurity because it can adapt and make accurate predictions.
   • Research Gaps and Unresolved Issues
   • Adversarial Attacks: AI systems are still open to carefully planned attacks from other AI systems.
   • Ethical Concerns: There are still problems with justice, following the rules, and AI prejudice.
   
**Contribution to Research**
This paper shows that deep learning greatly improves cybersecurity readiness by making it possible to find and fix risks with little help from people.  But it stresses the need for more research to make sure that AI is strong, private, and clear.

---
# Paper 11: Detecting Cyber Attacks in Healthcare IoT Systems
###
**Summary**

This study investigates cybersecurity weaknesses in hospitals that use the Internet of Things (IoT), where the hazards of DDoS attacks, ransomware, and unauthorized access are growing. It looks at AI methods that can help find things and explains how deep learning, specifically GRU-based models, can be used to protect against attacks.

**Key Findings and Methodologies**
**Methodology**:
  • RU (Gated Recurrent Units): A deep learning architecture that was tested against (Recurrent Neural Network) RNN, LSTM, CNN, SVM, and Naive Bayes to find threats.
  • SMOTE: this is used to balance synthetic data and real data and make anomaly detection more accurate.
  
**Key Findings**:
  • The GRU models were the best, with a 99.95% accuracy rate.
  • SMOTE makes datasets and detection much better.
  • Old gadgets and weak encryption make healthcare systems still susceptible.


**Research Gaps and Unresolved Issues**
  • Real-Time Integration: Putting detection models into action in real hospitals is not easy from a technical point of view.
  • Different forms of attack should be shown in bigger, more realistic datasets.
  • Human Factors: Staff training and awareness are still not fully understood, although they are very important.

**Contribution to Research**
This study shows that deep learning is still a good way to find IoT healthcare threats.  It shows that GRU is a better model and begs for more data sets and safe ways to integrate them to fully realize the potential of real-time defense.

---

# Paper 12: Enhancing Data Privacy of IoT Healthcare with Keylogger Attack Mitigation
###
**Summary**
This paper is about how to protect IoT healthcare systems from keylogger attacks that put sensitive patient data at risk.  It talks about how well LightGBM works for real-time detection and investigates blockchain, federated learning, and edge computing to improve privacy and spread-out security tasks.

**Key Findings and Methodologies**
**Methodology**:
  • LightGBM did a better job of finding keyloggers in real time than CNN and ANN.
  • Blockchain is used to handle data safely, run smart contracts, and connect different systems.
 • Federated Learning lets you train detection models in a decentralized way without giving up raw data.


**Key Findings**:
  • LightGBM can find keyloggers with very little delay and very high accuracy.
  • Blockchain makes authentication stronger and makes sure that data logs can't be changed.
  • Federated learning protects privacy and makes models work better.


**Research Gaps and Unresolved Issues**
  • Weaknesses in hardware: Physical pieces, such PS/2 keyboards, are still weak points.
  • Lack of Awareness: A lot of healthcare workers don't know how to spot cyber dangers.
  • Deployment Cost: It is still expensive and hard to put ML-enabled NICs to use on a large scale.

**Contribution to Research**
This study shows how ML and blockchain may make healthcare IoT environments safer.  It shows that LightGBM is a strong contender for finding keyloggers and stresses how important it is for future research to focus on cybersecurity frameworks that can grow, respect privacy, and be integrated.

---
**Format for week 4**
**Introduction**

**Purpose and Aims of the Literature Review**


**Literature Review Process**


**References(including 10 articles that you selected)**
