# **AI Governance Framework**

## **1\. Strategy & Ethical Principles**

This section outlines the ethical foundations governing the use of Artificial Intelligence across the organization.

### **AI Ethics and Governance Policy**

#### **Commitment to Responsible AI**

While AI systems offer incredible potential to improve our efficiency and support decision-making, they also introduce real risks to privacy, fairness, and security. These principles serve as a foundation for using AI responsibly. They apply to every AI technology, whether it’s a machine learning model, a Large Language Model (LLM), or a solution from one of our partners.

* **Meaningful Human Oversight**  
  * AI should support human judgment, not replace it. Responsibility for a decision always rests with a person, never a system.  
  * **Accountability:** Every AI solution must have designated business and technical owners who are responsible for its design, deployment, and impact.  
  * **Intervention:** Ensure that human oversight is possible at all times. This is especially critical when AI influences decisions that affect employees, customers, or the community. Users must always have a clear path to challenge or override an AI-generated outcome.  
* **Transparency and Explainability**  
  * Trust is built on transparency. Stakeholders must know when they are interacting with an AI system and understand how it reached a specific recommendation.  
  * The maintenance of clear documentation for every system, detailing its purpose, the data it uses, and its known limitations, is a must.  
* **Fairness and Bias Mitigation**  
  * Ensuring that AI systems treat everyone fairly. Do not build or use technology that results in unlawful discrimination.  
  * **Evaluation:** Before any system goes live, particularly in sensitive areas like recruitment, finance, or healthcare evaluate it for bias and data quality.  
  * **Continuous Review:** Fairness is an ongoing responsibility that should be managed throughout the entire life of the system.  
* **Privacy and Data Stewardship**  
  * Protecting sensitive information is a core requirement of governance. Follow the principle of data minimization, using only what is necessary to get the job done.  
  * Handle all personal information in strict accordance with legal standards, including PIPEDA and Quebec Law 25\. By conducting Privacy Impact Assessments (PIAs) early in the development phase, ensure privacy is built into the technology from day one.  
* **Security and Resilience**  
  * Treat AI security as a fundamental ethical duty. Implement robust safeguards including encryption, access controls, and incident response to protect systems from misuse or manipulation.  
  * Pay specific attention to emerging threats like prompt injection and model abuse.  
  * Any AI connected to production environments undergoes an enhanced security review before it is deployed.  
* **Reliability and Safety**  
  * AI systems must perform consistently and safely within their intended boundaries.  
  * Test and validate every model before it reaches the real world, and monitor it afterward for drift or unexpected behavior.  
  * If a system behaves in an unreliable manner, ensure that rollback or shutdown mechanisms are ready to be deployed immediately.  
* **Third-Party AI Governance**  
  * Using external AI services doesn't change our standards. Require all teams to disclose the use of third-party providers to assess the associated risks.  
  * Never expose sensitive or confidential data to external systems without the proper safeguards in place. Every partner must align with our own privacy and security requirements.  
* **Ongoing Governance**  
  * Manage AI from development through to its eventual retirement. Perform periodic reviews to ensure systems remain aligned with values, goals, and the overall organization’s risk appetite.

---

## **2\. Regulatory Mapping & Compliance**

This section maps our AI Governance Framework to the current legal landscape.

**Note:** As of May 2026, Canada has no dedicated federal AI legislation. Compliance is achieved by adhering to existing privacy laws and policies.

### **Canadian Legal Framework (The Patchwork)**

* **Federal: PIPEDA (Personal Information Protection and Electronic Documents Act)**  
  * *Status:* Active.  
  * *Application:* Private sector organizations across Canada (except in provinces with substantially similar laws like Quebec, Alberta, and British Columbia).  
  * *AI Context:* PIPEDA's "Appropriate Purposes" clause and "Consent" requirements apply to data used for AI training and profiling. Use of AI must be transparent and limited to the purposes disclosed to the individual.  
* **Provincial: Quebec Law 25 (Private Sector Act)**  
  * *Status:* Active and Enforced.  
  * *The "AI Provision" (Section 12.1):* This is currently the most significant AI-related legal requirement in Canada.  
  * *Transparency:* You must inform individuals when a decision is made exclusively by automated processing.  
  * *Right to Explanation:* You must provide, upon request, the parameters and logic used to reach that automated decision.  
  * *Right to Correction:* Individuals must be allowed to correct the personal information used to make the decision.  
* **Federal Public Sector: Directive on Automated Decision-Making (DADM)**  
  * *Status:* Mandatory for Federal Institutions. It is an active federal government policy directive issued under Treasury Board authority.  
  * *Key Requirements:*  
    * **AIA:** Mandatory completion of the Algorithmic Impact Assessment.  
    * **Human-in-the-loop:** Specific requirements for human intervention based on the "Impact Level" (1 through 4\) of the system.  
    * **Notification:** Mandatory notice that an automated system is being used.

### **International Extraterritorial Impact**

* **EU AI Act**  
  * *Status:* Enforced.  
  * *Relevance to Canada:* Canadian firms must comply if their AI systems are placed on the EU market or if the output of the AI is used within the EU.  
  * *Key Deadlines:* Many "High-Risk" obligations became enforceable in early 2026\.  
  * *Alignment:* Use the EU's risk-based classification as a global best practice to ensure market access.

### **Standardized Frameworks (Voluntary Compliance)**

Since there is no federal law, we align with the following standards to demonstrate "Due Diligence" in a court of law or during a privacy audit:

| Standard | Role in this Framework |
| :---- | :---- |
| **ISO/IEC 42001** | The overarching AI Management System (AIMS) structure used for this framework. |
| **NIST AI RMF 1.1** | The technical methodology for "Mapping" and "Measuring" AI risk. |
| **Voluntary Guardrails** | Alignment with Canada’s *Voluntary Code of Conduct on the Responsible Development and Management of Advanced Generative AI Systems*. |

---

## **3\. Compliance Gap Analysis**

| Regulatory Source | Requirement | Risk Area | Control Objective | Example Controls | Evidence |
| :---- | :---- | :---- | :---- | :---- | :---- |
| **Canada PIPEDA** | Consent & transparency | Privacy | Users understand AI data use | AI privacy notice, consent tracking | Privacy assessments |
| **Quebec Law 25** | Automated decision transparency | AI transparency | Inform individuals of automated decisions | AI disclosure process | Customer notices |
| **EU AI Act** | High-risk AI governance | Model risk | Ensure safe deployment | AI risk assessments | Risk register |
| **NIST AI RMF** | Govern function | Governance | Define accountability | AI steering committee | Meeting minutes |
| **ISO/IEC 42001** | AI management system | Oversight | Formal AI governance | AI policy and procedures | Approved policy |
| **SOC 2 / ISO 27001** | Security controls | Cybersecurity | Protect AI systems/data | Access controls, logging | Audit logs |

### **Regulatory & Legal References**

* **Canadian Frameworks:** Office of the Privacy Commissioner of Canada guidance , PIPEDA , Quebec Law 25 , Federal Directive on Automated Decision-Making , and Provincial privacy laws.  
* **International Frameworks:** National Institute of Standards and Technology (NIST) AI RMF , ISO/IEC 42001 , ISO/IEC 23894 , EU AI Act , and OECD AI Principles.

---

## **4\. Governance & Organization**

### **Approval Workflows**

To ensure all AI systems are developed responsibly and in compliance with internal ethics, every project must pass through a multi-stage approval gate.

#### **The Four-Stage Workflow**

\[ Stage 1: Intake & Ethics \] ──\> \[ Stage 2: Risk & Impact \] ──\> \[ Stage 3: Tech Validation \] ──\> \[ Stage 4: Final ATO \]

1. **Stage 1: Intake & Ethics Review**  
   * *Trigger:* A business unit proposes a new AI use case.  
   * *Requirements:* Initial use-case description and "Ethics Self-Assessment".  
   * *Gatekeeper:* AI Governance Committee.  
   * *Outcome:* "Go/No-Go" based on alignment with Core Ethics Principles.  
2. **Stage 2: Risk & Impact Assessment (The Compliance Gate)**  
   * *Trigger:* Project is approved for technical feasibility.  
   * *Requirements:* Algorithmic Impact Assessment (AIA), Privacy Impact Assessment (PIA) (Mandatory per Law 25 for personal data), and Data Sensitivity Classification.  
   * *Gatekeeper:* Privacy Office / Risk Management.  
   * *Outcome:* Risk Tier Assignment (Low, Medium, High).  
3. **Stage 3: Technical Validation & Peer Review**  
   * *Trigger:* Model development is complete in the sandbox.  
   * *Requirements:* Bias and Fairness testing results, Security penetration test (Prompt injection/Data leakage), and Explainability documentation.  
   * *Gatekeeper:* Technical Lead / CISO.  
   * *Outcome:* Technical Sign-off.  
4. **Stage 4: Final Authorization (ATO)**  
   * *Trigger:* All assessments and technical tests are passed.  
   * *Requirements:* Completion of the Model Card and entry into the AI Inventory.  
   * *Gatekeeper:* Accountable Executive.  
   * *Outcome:* Production Deployment.

#### **Workflow Summary Table**

| Step | Phase | Key Artifact | Approval Authority |
| :---- | :---- | :---- | :---- |
| **01** | Intake | AI Project Charter | AI Governance Committee |
| **02** | Risk | PIA / AIA Reports | Privacy/Legal Office |
| **03** | Testing | Validation Report | Security / Lead Data Scientist |
| **04** | Launch | Authorization to Operate (ATO) | Executive Sponsor |

#### **Accelerated Path (Low-Risk Systems)**

Projects identified as Low-Risk (e.g., internal-only productivity tools with no PII and no automated decision-making) may follow an accelerated path:

* Stages 2 and 3 are condensed into a single "Review Checklist".  
* Approval can be granted by the Departmental Head rather than the full Committee.

#### **Re-Certification Triggers**

Approvals are not permanent. A workflow re-trigger is required if any of the following occur:

* **Significant Drift:** The model's performance drops below the established baseline.  
* **Scope Creep:** The AI is used for a purpose not defined in the original Intake.  
* **Annual Review:** All "High-Risk" systems must be re-validated every 12 months.

---

## **5\. Roles & Responsibilities**

Clear accountability is the cornerstone of our AI Management System (AIMS). This section defines the key stakeholders and ensures compliance with ISO 42001 and Canadian privacy standards.

### **Key AI Governance Roles**

* **AI Governance Committee (Steering Body)**  
  * *Mandate:* High-level oversight and alignment with corporate strategy.  
  * *Responsibilities:* Approving the AI Ethics Principles, making final "Go/No-Go" decisions for high-impact AI projects, and reviewing annual AI audit reports.  
* **AI Privacy Officer (Person in Charge \- Law 25\)**  
  * *Mandate:* Ensuring the protection of personal information and compliance with Quebec/Federal privacy laws.  
  * *Responsibilities:* Overseeing and approving Privacy Impact Assessments (PIAs), handling requests for explanations regarding automated decisions, and managing data breach notifications related to AI datasets.  
* **CISO / Cyber Security Lead**  
  * *Mandate:* Securing the AI infrastructure and model integrity.  
  * *Responsibilities:* Assessing risks of prompt injection, data poisoning, and model inversion; enforcing access controls on training datasets; and integrating AI into the existing Incident Response Plan.  
* **Lead Data Scientist / ML Engineer**  
  * *Mandate:* Technical development and validation of AI systems.  
  * *Responsibilities:* Implementing Bias and Fairness testing, maintaining model versioning and technical documentation (Model Cards), and monitoring for model drift in production.  
* **Business Owner (Project Sponsor)**  
  * *Mandate:* Defining the business objective and justifying the AI use case.  
  * *Responsibilities:* Ensuring the AI system delivers the intended value, monitoring the human-in-the-loop (HITL) process for operational accuracy, and training staff on specific AI tool usage.

### **RACI Matrix (Operational Alignment)**

This matrix maps Control IDs to the defined roles.

| Activity | AI Gov Committee | Privacy Officer | CISO | Lead Data Scientist | Business Owner |
| :---- | :---- | :---- | :---- | :---- | :---- |
| **Drafting AI Policy (AI-GOV-03)** | A | C | C | I | I |
| **Conducting PIAs (AI-PRIV-01)** | I | A/R | C | I | C |
| **Model Bias Testing (AI-MDL-02)** | I | C | I | R | I |
| **Final Approval (ATO)** | A | C | C | I | R |
| **Managing AI Incidents (AI-MON-03)** | I | C | R | C | I |

**Key:** **R** \= Responsible | **A** \= Accountable | **C** \= Consulted | **I** \= Informed

### **Conflict of Interest & Independence**

To maintain the integrity of our framework:

* The Privacy Officer and CISO maintain the right to veto a deployment if significant risks to individuals or the organization are identified.  
* Internal Audits must be conducted by individuals independent of the development team (Lead Data Scientist).

---

## **6\. Technical & Operational Controls**

### **Data Governance**

This policy ensures that all data used for training, fine-tuning, and prompting AI models is handled with integrity, legality, and security.

#### **Lawful Basis for Processing (Law 25 & PIPEDA)**

Before any dataset is ingested into an AI pipeline, the Privacy Office must verify the legal basis for its use:

* **Consent:** Has the individual provided clear, informed consent for their data to be used in automated decision-making or model training?  
* **Purpose Limitation:** Is the AI application consistent with the original purpose for which the data was collected?  
* **Anonymization:** Whenever possible, data must be anonymized (not just pseudonymized) before being used in training sets to remove it from the scope of Law 25\.

#### **Data Quality & Integrity**

AI outcomes are only as reliable as the input data. We enforce the following quality controls:

* **Completeness:** Datasets must be representative of the diverse Canadian population to prevent Algorithmic Bias.  
* **Accuracy:** Periodic Data Audits are required to ensure training data is not outdated or factually incorrect.  
* **Source Attribution:** We maintain a Data Lineage record for every model, documenting the origin and transformation of all training inputs.

#### **Data Lifecycle in AI**

| Phase | Requirement | Control ID |
| :---- | :---- | :---- |
| **Ingestion** | Verification of data rights and licenses. | AI-DATA-01 |
| **Preparation** | Masking of PII/PHI; removal of toxic content. | AI-DATA-04 |
| **Training** | Encryption at rest and in transit (TLS 1.3). | AI-SEC-01 |
| **Inference** | Zero-Retention policies for sensitive prompts. | AI-DATA-03 |
| **Retirement** | Secure deletion of training checkpoints and logs. | AI-LOG-02 |

#### **Specific Technical Controls**

* **A. Data Minimization:** Strictly follow the principle of least data. If a model can achieve its objective using synthetic data or aggregated datasets, personal information must not be used.  
* **B. Prompt Engineering & Data Leakage (To prevent Training Data Extraction attacks):**  
  * *PII Filtering:* Automated tools must scan and redact sensitive information (names, SINs, health cards) before data is sent to Large Language Models (LLMs).  
  * *Differential Privacy (DP):* For sensitive datasets, we apply mathematical noise ($Epsilon$-based privacy) during fine-tuning or data aggregation. This provides a formal guarantee that individual records cannot be reconstructed from model outputs, satisfying the high bar for Anonymization under Law 25\.  
  * *Output Filtering:* Models are tested to ensure they do not memorize and repeat sensitive training snippets to unauthorized users.  
* **C. Large Language Model (LLM) Governance:**  
  * *Public LLMs:* Staff are prohibited from entering proprietary or sensitive client data into public/unmanaged AI tools (e.g., free versions of ChatGPT).  
  * *Enterprise Instances:* Only approved Enterprise instances with No-Training clauses are permitted for corporate data processing.

#### **Data Stewardship Roles**

* **Data Owner:** Accountable for the classification and business value of the data.  
* **AI Engineer:** Responsible for technical implementation of masking and encryption.  
* **Privacy Officer:** Responsible for ensuring Law 25 compliance and conducting PIAs.

---

## **7\. Testing & Validation**

This policy defines the mandatory testing protocols all AI systems must undergo prior to deployment and during significant updates. No model shall be promoted to production without a completed Technical Validation Report covering the following three pillars:

### **Pre-Deployment Pillars**

* **A. Performance & Accuracy Testing**  
  * *Benchmark Evaluation:* Testing the model against standardized, gold-standard datasets to ensure it meets the minimum performance KPIs (e.g., F1-score, Precision-Recall).  
  * *Out-of-Distribution (OOD) Testing:* Evaluating how the model handles data it was not trained on to identify blind spots and prevent hallucinations.  
  * *Robustness Testing:* Stress-testing the model with noisy or incomplete data to ensure it fails gracefully rather than producing confident, incorrect answers.  
* **B. Fairness & Bias Auditing**  
  * Conduct slicing analysis in alignment with the Canadian Charter of Rights and Freedoms:  
  * *Disparate Impact Analysis:* Testing model performance across protected groups (gender, age, ethnicity, language).  
  * *Linguistic Parity:* Ensuring AI performance is equitable in both English and French, particularly for citizen-facing services.  
  * *Mitigation:* If a bias is detected (e.g., a 20% variance in performance between groups), the model must be retrained or a Bias Shield control must be implemented.  
* **C. Security & Adversarial Testing (Red Teaming)**  
  * *Prompt Injection:* Attempting to bypass system instructions to extract sensitive data or force the model to ignore safety guardrails.  
  * *Data Leakage Check:* Verifying that the model does not repeat PII from the training set (Validation of Differential Privacy controls).  
  * *Adversarial Robustness:* Testing against input perturbations designed to trick the model into misclassification.

### **The Validation Pipeline**

| Step | Testing Type | Responsible Party | Artifact |
| :---- | :---- | :---- | :---- |
| **01** | Unit Testing | ML Engineer | Automated Test Logs |
| **02** | Bias Audit | Data Scientist / GRC | Bias Assessment Report |
| **03** | Red Teaming | Security Team (CISO) | Penetration Test Report |
| **04** | UAT | Business Owner | Acceptance Sign-off |

### **Explainability & Logic Testing**

To satisfy Quebec Law 25 (Section 12.1), validate the Interpretability of the model:

* **Local Explanations:** For every high-impact decision, the system must be able to generate a Reasoning Code or explanation.  
* **Logic Review:** A human expert must periodically review a sample of automated decisions to ensure the underlying logic remains consistent with business policy.

### **Human-in-the-loop (HITL) Validation**

Systems that affect a Canadian's legal or economic status require a verified human oversight mechanism:

* **Intervention Testing:** We simulate scenarios where the AI makes an error to ensure the human operator can effectively override the system.  
* **Threshold Review:** Ensuring that Low Confidence scores automatically trigger a human review workflow rather than a final automated decision.

### **Regression Testing**

Any update to the model (retraining or fine-tuning) requires a full regression suite to ensure that:

* Previously mitigated biases have not re-emerged.  
* Security patches for prompt injections remain active.  
* Performance has not drifted below the approved baseline.

---

## **8\. Monitoring & Drift Detection**

This policy outlines the mandatory monitoring requirements to ensure our AI models remain accurate, safe, and compliant throughout their operational lifecycle.

### **Types of Drift Monitoring**

* **A. Concept Drift (The "Logic" Shift)**  
  * *Definition:* When the statistical properties of the target variable change (e.g., a normal financial transaction in 2024 looks different in 2026).  
  * *Threshold:* A 10% deviation from the validated accuracy baseline triggers an automatic investigation.  
  * *Impact:* Directly affects the Logic of the Decision required under Law 25\.  
* **B. Data Drift (The "Input" Shift)**  
  * *Definition:* When the input data distribution significantly differs from the training dataset (e.g., a sudden shift in the demographic makeup of users).  
  * *Monitoring Method:* Comparison of live data distributions against the Golden Dataset used during Testing & Validation.  
* **C. Technical & Security Monitoring**  
  * *System Health:* Monitoring latency, throughput, and error rates (AIOps).  
  * *Adversarial Detection:* Real-time logging of Out-of-Bounds prompts that may indicate automated injection attacks.  
  * *Cost & Token Usage:* Monitoring for Resource Exhaustion or anomalous spikes in API consumption.

### **Monitoring Metrics & Alerting**

| Metric Category | Key Indicator | Alert Trigger |
| :---- | :---- | :---- |
| **Model Quality** | Accuracy / F1-Score | Drops below 90% of baseline |
| **Fairness** | Demographic Parity Ratio | Variance \> 15% between groups |
| **Security** | Prompt Injection Flag | 3+ consecutive blocked attempts |
| **Data Health** | Feature Null-Rate | 5% unexpected null values |

*   
  **Continuous Bias Monitoring:** Monitoring for bias does not end at deployment. We perform automated periodic checks to ensure the model has not developed learned bias from new production data.  
  * *Frequency:* Monthly for High-Impact systems; Quarterly for Low-Impact.  
  * *Reporting:* Results are logged in the Audit Logs for GRC review.

### **Incident Handling & Escalation**

If a drift threshold is breached, the following Incident Response workflow is activated:

* **Alert:** Notification sent to the Lead Data Scientist and Business Owner.  
* **Triage:** Determine if the drift is Temporary (e.g., a holiday spike) or Structural (e.g., a permanent shift in market behavior).  
* **Action Levels:**  
  * *Level 1:* Continue monitoring with increased frequency.  
  * *Level 2:* Re-calibrate the model using the most recent data.  
  * *Level 3:* Kill Switch – Temporarily disable automated decisions and revert to manual fallback.  
* **Retraining & Re-Validation:** Once a model is retrained to correct drift, it must be treated as a New Version and pass through the Testing & Validation gates again before being re-promoted to production.

---

## **9\. Risk Management & Assessment**

### **Risk Taxonomy**

This taxonomy provides a standardized classification system for identifying and categorizing risks associated with Artificial Intelligence.

* Accountability & Legal Risks (Regulatory non-compliance and legal liability )  
  * *Regulatory Non-Compliance:* Failure to meet Quebec Law 25 transparency requirements or federal privacy expectations.  
  * *Contractual Breach:* Violation of third-party data use agreements or software licenses (e.g., using "non-commercial" open-source models for business).  
  * *Intellectual Property (IP) Infringement:* Risk of the AI generating copyrighted content or being trained on proprietary data without authorization.  
* Ethical & Societal Risks (Impact on human rights, fairness, and brand reputation )  
  * *Algorithmic Bias:* Systematic prejudice in AI outputs that disadvantages specific protected groups (gender, age, ethnicity, etc.).  
  * *Lack of Explainability:* The "Black Box" risk where a decision cannot be justified to a Canadian citizen or regulator.  
  * *Social Harm:* The potential for the system to generate toxic, hateful, or harmful content.  
* Data & Privacy Risks (Focusing on the "fuel" of the AI system )  
  * *Data Leakage/Exfiltration:* Sensitive PII or corporate secrets being "remembered" by the model and leaked to unauthorized users via prompts.  
  * *Inadequate Data Quality:* Training on "garbage" data leading to inaccurate or "hallucinated" outcomes.  
  * *Unauthorized Profiling:* Creating invasive profiles of individuals without a clear legal basis under PIPEDA.  
* Technical & Security Risks (Traditional cybersecurity applied to AI architectures )  
  * *Adversarial Attacks:* Prompt Injection (tricking the LLM into bypassing safety filters ) and Data Poisoning (corrupting training data to create a model "backdoor" ).  
  * *Model Drift:* The degradation of model performance over time due to changes in real-world data patterns.  
  * *Infrastructure Vulnerability:* Security flaws in the hosting environment (e.g., insecure APIs, unpatched GPU clusters).  
* Operational Risks (Impact on day-to-day business continuity )  
  * *Over-Reliance (Automation Bias):* Human operators trusting AI outputs blindly without performing required verification.  
  * *Model Failure:* Total loss of service due to technical glitches or vendor outages.  
  * *Shadow AI:* Employees using unauthorized AI tools (e.g., unmanaged web-based LLMs) to process corporate data.

### **Risk Impact Scoring**

We evaluate the risks in this taxonomy using a 5x5 matrix (Impact vs. Likelihood). Each identified risk must be mapped back to our Control Matrix (**AI-RISK-01**).

| Impact Level | Description |
| :---- | :---- |
| **Critical** | Potential for significant legal action, total loss of public trust, or violation of Charter rights. |
| **High** | Breach of Law 25, significant financial penalty, or widespread bias in results. |
| **Medium** | Minor regulatory friction, operational delays, or isolated instances of inaccurate output. |
| **Low** | Minimal impact on individuals; internal-only performance issues. |

---

## **10\. Impact Assessments**

Before any AI system is moved from development to production, it must undergo a formal Algorithmic Impact Assessment (AIA) and a Privacy Impact Assessment (PIA).

### **Assessment Triggers**

An impact assessment is mandatory if a project meets any of the following criteria:

* **Automated Decision-Making:** The system makes decisions that significantly affect individuals (e.g., hiring, credit, access to services).  
* **Personal Data:** The system processes personal information (PII) as defined by PIPEDA or Law 25\.  
* **High-Risk Taxonomy:** The project falls into a "High" or "Critical" category as defined in our Risk Taxonomy.  
* **Public-Facing:** The AI interacts directly with Canadians (e.g., external chatbots).

### **The Assessment Process**

* **Phase A: Threshold Assessment**  
  * A quick 10-question screening to determine if a full AIA is required. If the system is purely for internal code optimization with no PII, a full AIA may be waived.  
* **Phase B: Technical & Ethical Analysis (Project team documentation)**  
  * *Data Source & Lineage:* Where did the training data come from? Is there a legal basis for its use?  
  * *Bias Mitigation:* What steps were taken to ensure the model does not discriminate against protected groups in the Canadian context?  
  * *Explainability:* Can we explain the "logic" of the output as required by Quebec Law 25 Section 12.1?  
* Phase C: Risk Scoring (Scale of 1–4 using Risk Taxonomy )  
  * *Level 1 (Low):* Minimal impact; standard monitoring.  
  * *Level 2 (Moderate):* Requires specific technical controls and documentation.  
  * *Level 3 (High):* Requires peer review and formal Executive sign-off.  
  * *Level 4 (Very High):* Requires independent third-party audit and "Human-in-the-loop" enforcement.

### **AIA Template Structure**

| Section | Requirement | Focus Area |
| :---- | :---- | :---- |
| **1\. Project Scope** | Describe the intended use case. | Objectives & Stakeholders |
| **2\. Data Governance** | Document data sensitivity. | Law 25 / PIPEDA Compliance |
| **3\. Algorithm Details** | Model type and transparency. | Explainability & Black Box Risk |
| **4\. Mitigation Plan** | List controls for identified risks. | Mapping to Control Matrix |
| **5\. Human Oversight** | Define the Human-in-the-loop. | Accountability & Redress |

#### **Law 25 Specific Requirements**

For all projects impacting Quebec residents, the assessment **must** explicitly answer:

* *Is the decision exclusively automated?* If yes, the "Right to Explanation" workflow must be tested.  
* *Is there a path for correction?* How can a citizen contest a result and have their data corrected?

#### **Maintenance & Review**

Impact Assessments are "living documents" and must be updated if:

* The model is retrained on a significantly different dataset.  
* The intended "Purpose of Use" changes.  
* Annual re-certification is due for Level 3 and 4 systems.

⚠️ **Note:** Do not confuse the AIA with a standard Business Impact Analysis (BIA). While the BIA focuses on business continuity and system availability, the AIA specifically evaluates the socio-technical risks of AI outputs on individuals, community rights, and regulatory standing under Quebec Law 25\.

---

## **11\. Risk Classification & Maturity Models**

### **Risk Classification Model**

| Risk Level | Description | Example AI Systems |
| :---- | :---- | :---- |
| **Low** | Minimal impact systems | Internal productivity copilots |
| **Moderate** | Business-impacting systems | Customer support chatbots |
| **High** | Systems affecting individuals or critical decisions | Hiring AI, credit scoring |
| **Critical** | Safety or rights impacting systems | Healthcare diagnostics, law enforcement analytics |

### **Maturity Model Framework**

| Maturity Level | Characteristics |
| :---- | :---- |
| **Initial** | Ad hoc AI usage with limited governance |
| **Developing** | Basic policies and inventories established |
| **Defined** | Formal governance and risk management implemented |
| **Managed** | Metrics, monitoring, and continuous assessment active |
| **Optimized** | Integrated enterprise-wide AI governance and assurance |

---

## **12\. Model Cards**

This document serves as the standardized record of a model's capabilities, limitations, and the logic governing its outputs.

**Note:** Each project must create a unique instance of this card.

### **Model Card Template**

* **Section A: Model Details**  
  * Model Name: *(e.g., Customer Sentiment Analyzer v2.1)*  
  * Developer: *(Internal Team or Vendor Name)*  
  * Version: *(Git Tag or Registry Version)*  
  * Date of Deployment: *(YYYY-MM-DD)*  
  * Model Type: *(e.g., Transformer, Random Forest, Fine-tuned LLM)*  
* **Section B: Intended Use**  
  * Primary Purpose: What was this model built to do?  
  * Target Users: Who is authorized to use the outputs?  
  * Out-of-Scope Uses: List scenarios where the model must not be used *(e.g., Do not use for automated credit approvals)*.  
* **Section C: Training & Data**  
  * Dataset Description: Summary of data sources *(e.g., "Internal support logs 2024-2025")*.  
  * Data Lineage: Link to the Data Governance Record.  
  * Privacy Protections: Documented use of Differential Privacy or PII masking.  
* **Section D: Ethics & Fairness (Law 25 Alignment)**  
  * Bias Mitigation: Summary of testing results across Canadian demographics.  
  * Explainability Method: How is the "Logic of the Decision" provided to users?  
  * Human-in-the-Loop: Describe the manual review process for high-impact outputs.  
* **Section E: Risks & Limitations**  
  * Known Blind Spots: Scenarios where the model is known to perform poorly.  
  * Environmental Impact: Estimated carbon footprint or energy consumption of training.  
  * Security Posture: Confirmation of Red Team testing against prompt injection.

### **Model Performance Summary (Example Metrics)**

| Metric | Score | Baseline | Status |
| :---- | :---- | :---- | :---- |
| **Accuracy** | 94.2% | 90% | ✅ Passed |
| **Fairness (Demographic Parity)** | 0.96 | \> 0.80 | ✅ Passed |
| **Inference Latency** | 120ms | \< 200ms | ✅ Passed |

### **Maintenance & Version Control**

* **Retraining Cycle:** *(e.g., Every 6 months or when Drift exceeds 10%)*.  
* **Change Log:** Link to GitHub repository for code and configuration history.  
* **Owner:** *(Link to the Accountable Executive)*.

### **Public Disclosure Statement**

For frontend-facing systems, a Simplified Model Card must be published on the corporate website to satisfy transparency requirements. This includes:

1. Notice that an AI system is being used.  
2. A plain-language description of the logic.  
3. Instructions on how to request a manual review of an automated decision.

---

## **13\. Audit Logs & Traceability Standard**

This document defines the mandatory logging and data retention architecture required to ensure the accountability, traceability, and defensibility of all deployed AI systems.

### **Mandatory Log Schema (What We Track)**

Every AI system interaction must generate a secure, structured log entry containing the following attributes:

* **A. Transaction Metadata**  
  * *Timestamp:* ISO 8601 format with UTC offset (YYYY-MM-DDTHH:MM:SSZ).  
  * *System Identity:* Unique Model ID and Version matching the active Model Card.  
  * *Session ID:* Cryptographic identifier linking a series of prompts/responses to a specific user session.  
  * *User Identity:* Internal account ID or hashed identifier of the individual or API calling the system.  
* **B. Core AI Telemetry**  
  * *Input Payload (The Prompt):* The raw input text, image metadata, or data vector provided to the model (post-redaction).  
  * *Output Payload (The Inference):* The verbatim response, classification, or recommendation generated by the model.  
  * *Confidence Score:* The mathematical probability or certainty metric generated by the model for its decision.  
* **C. GRC & Transparency Metrics**  
  * *Guardrail Trigger Status:* Boolean indicators showing if input/output safety filters were activated *(e.g., prompt\_injection\_detected: true/false, pii\_leak\_blocked: true/false)*.  
  * *Explainability Artifact:* The underlying explainability record demonstrating the logic behind that specific output.  
  * *Human Intervention Flag:* Documenting whether the output was applied automatically or routed for human review before execution.

### **Telemetry Schema Reference**

| Log Field | Data Type | Logging Requirement | Compliance Driver |
| :---- | :---- | :---- | :---- |
| timestamp | String | Mandatory for all events | Forensic Timeline |
| model\_version | String | Mandatory for all events | Model Card Standard |
| redacted\_prompt | String | Mandatory for Text-based AI | Data Leakage Prevention (AI-SEC-05) |
| explainability\_vector | JSON / Blob | Mandatory for High-Impact systems | Law 25 Right to Explanation |
| human\_override | Boolean | Mandatory for High-Impact systems | Human Oversight (AI-HUM-01) |

### **Security & Protection of Logs**

Because audit logs contain highly sensitive context, they must be protected with enterprise-grade security controls:

* **Immutability:** Logs must be written directly to a write-once, read-many (WORM) storage repository or a centralized SIEM to prevent alteration or deletion by unauthorized personnel or adversaries.  
* **PII Sanitization:** The logging pipeline itself must feature an automated scrubbing mechanism. No unencrypted SINs, banking info, or raw health identifiers may be written to the long-term log repository.  
* **Access Control:** Strict Role-Based Access Control (RBAC) and Multi-Factor Authentication (MFA) are enforced. Only designated Compliance Officers and Security Forensics staff may view raw log indexes.

### **Log Retention & Disposal Policy**

In alignment with Canadian data retention standards and corporate risk directives:

* **High-Impact Systems:** All inference logs, explainability files, and human override decisions must be retained for a **minimum of 7 years** from the date of creation to support potential legal or regulatory challenges.  
* **Low-Impact Systems:** Standard telemetry logs must be retained for **1 year** for operational and performance analysis.  
* **Secure Destruction:** Upon expiration of the retention window, data must be permanently erased using cryptographically secure erasure methods in compliance with industry best practices.

### **Incident Handling & Escalation**

If the log monitoring pipeline detects anomalous patterns (such as a high volume of blocked prompt injections or systematic model failures), an incident is automatically declared under Control ID **AI-MON-03**:

* **Severity 1 (Active Poisoning/Leakage):** Triggers an immediate automated model quarantine (Kill Switch) and alerts the CISO.  
* **Severity 2 (Systemic Failure):** Routes all downstream transactions to the manual operational fallback pathway.

---

## **14\. AI Regulatory Mapping Matrix (Comprehensive Master Registry)**

*This comprehensive matrix functions as the foundational master file for tracking active controls, mapping them to standard regulatory frameworks, identifying accountability owners, and establishing acceptable artifacts for internal or external audit trails.*

| Control ID | Governance Domain | Control Objective | Example Control Activities | Regulatory / Framework Mapping | Evidence / Artifacts | Owner |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| **AI-GOV-01** | Governance & Accountability | Establish formal AI governance structure | Create AI governance committee and define roles | ISO 42001, NIST Govern, OECD AI Principles | Governance charter, meeting minutes | Executive Leadership |
| **AI-GOV-02** | Governance & Accountability | Define AI accountability model | Assign accountable executives and system owners | ISO 42001, EU AI Act | RACI matrix | CIO / CISO |
| **AI-GOV-03** | Governance & Accountability | Develop enterprise AI policy | Publish AI acceptable use and governance policy | ISO 42001, NIST Govern | Approved AI policy | Governance Office |
| **AI-RISK-01** | Risk Management | Conduct AI risk assessments | Perform risk assessments before deployment | ISO 23894, NIST Map | Risk assessment reports | Risk Management |
| **AI-RISK-02** | Risk Management | Classify AI systems by risk | Categorize AI systems using defined criteria | EU AI Act, DADM | AI classification register | Governance Office |
| **AI-RISK-03** | Risk Management | Perform impact assessments | Complete AI impact and ethical reviews | Quebec Law 25, DADM | Impact assessment documentation | Privacy Office |
| **AI-INV-01** | AI Inventory & Classification | Maintain AI inventory | Maintain centralized registry of AI systems | ISO 42001, NIST Govern | AI inventory database | IT Governance |
| **AI-INV-02** | AI Inventory & Classification | Identify high-risk AI systems | Flag systems affecting rights or safety | EU AI Act | Risk classification records | Compliance |
| **AI-DATA-01** | Data Governance | Ensure lawful data collection | Validate legal basis for data processing | PIPEDA, Law 25 | Privacy assessments | Privacy Office |
| **AI-DATA-02** | Data Governance | Manage training data quality | Validate completeness and accuracy of datasets | ISO 42001, EU AI Act | Data quality reports | Data Governance Team |
| **AI-DATA-03** | Data Governance | Maintain data lineage | Track data origin and transformations | ISO 42001 | Data lineage diagrams | Data Engineering |
| **AI-DATA-04** | Data Governance | Restrict sensitive data exposure | Apply masking and minimization controls | PIPEDA, Law 25 | Data classification reports | Security Team |
| **AI-PRIV-01** | Privacy & Legal Compliance | Conduct Privacy Impact Assessments | Perform PIAs for AI initiatives | PIPEDA, Law 25 | Completed PIA reports | Privacy Office |
| **AI-PRIV-02** | Privacy & Legal Compliance | Provide transparency notices | Notify users about AI usage | Law 25, OECD Principles | Privacy notices | Legal / Privacy |
| **AI-PRIV-03** | Privacy & Legal Compliance | Enable contestability | Allow review of automated decisions | Law 25, DADM | Appeal procedures | Operations |
| **AI-SEC-01** | Security & Cybersecurity | Protect AI infrastructure | Harden systems and enforce secure configurations | ISO 27001, SOC 2 | Security baselines | Infrastructure Team |
| **AI-SEC-02** | Security & Cybersecurity | Control access to models and datasets | Implement RBAC and MFA | ISO 27001 | Access review records | IAM Team |
| **AI-SEC-03** | Security & Cybersecurity | Monitor for prompt injection and abuse | Deploy monitoring and filtering controls | NIST AI RMF | Security monitoring reports | Security Operations |
| **AI-SEC-04** | Security & Cybersecurity | Secure APIs and integrations | Implement API security controls | SOC 2, ISO 27001 | API gateway logs | Application Security |
| **AI-SEC-05** | Security & Cybersecurity | Protect against data leakage | Implement DLP and monitoring | PIPEDA, ISO 27001 | DLP reports | Security Team |
| **AI-HUM-01** | Human Oversight | Ensure human review capability | Require human approval for high-impact decisions | EU AI Act, DADM | Workflow approvals | Business Operations |
| **AI-HUM-02** | Human Oversight | Define escalation procedures | Establish AI incident escalation paths | ISO 42001 | Incident playbooks | Operations |
| **AI-TRAN-01** | Transparency & Explainability | Provide AI disclosures | Inform users when AI is used | Law 25, OECD Principles | Disclosure statements | Legal |
| **AI-TRAN-02** | Transparency & Explainability | Document model explainability | Maintain explanation methodology | EU AI Act, NIST Explainability | Model documentation | Data Science Team |
| **AI-TRAN-03** | Transparency & Explainability | Maintain decision traceability | Record reasoning and outputs where possible | DADM | Audit logs | Engineering |
| **AI-MDL-01** | Model Development & Validation | Validate models before deployment | Perform testing and validation reviews | ISO 42001, NIST Measure | Validation reports | Data Science |
| **AI-MDL-02** | Model Development & Validation | Test for bias and fairness | Conduct fairness and bias analysis | OECD Principles, EU AI Act | Bias testing results | Data Science |
| **AI-MDL-03** | Model Development & Validation | Establish approval gates | Require formal approvals before production | ISO 42001 | Change approvals | Change Advisory Board |
| **AI-MDL-04** | Model Development & Validation | Manage model versioning | Track models and updates | ISO 42001 | Version history logs | MLOps Team |
| **AI-MON-01** | Monitoring & Incident Management | Monitor model performance | Track drift and degradation | ISO 42001, NIST Measure | Monitoring dashboards | MLOps Team |
| **AI-MON-02** | Monitoring & Incident Management | Detect harmful outputs | Monitor toxicity, hallucinations, unsafe content | NIST AI RMF | Content review reports | AI Operations |
| **AI-MON-03** | Monitoring & Incident Management | Manage AI incidents | Define AI-specific incident response | ISO 27001, ISO 42001 | Incident records | Security Operations |
| **AI-MON-04** | Monitoring & Incident Management | Perform periodic reassessments | Reevaluate AI risks on schedule | ISO 23894 | Review schedules | Risk Management |
| **AI-TPRM-01** | Third-Party & Vendor Management | Assess AI vendors | Perform due diligence reviews | ISO 27001, SOC 2 | Vendor assessments | Procurement |
| **AI-TPRM-02** | Third-Party & Vendor Management | Define contractual protections | Include AI and data protection clauses | Law 25, PIPEDA | Contracts | Legal |
| **AI-TPRM-03** | Third-Party & Vendor Management | Monitor vendor compliance | Review attestations and certifications | ISO 42001 | Vendor review records | Third-Party Risk Team |
| **AI-LOG-01** | Logging & Auditability | Maintain AI activity logs | Capture prompts, outputs, and actions | ISO 42001, SOC 2 | Audit logs | Engineering |
| **AI-LOG-02** | Logging & Auditability | Preserve audit evidence | Retain logs according to policy | ISO 27001 | Retention schedules | Compliance |
| **AI-ETH-01** | Ethics & Fairness | Define ethical AI principles | Publish responsible AI commitments | OECD Principles | AI ethics policy | Governance Office |
| **AI-ETH-02** | Ethics & Fairness | Prevent discriminatory outcomes | Conduct fairness reviews | EU AI Act | Fairness assessments | Data Science |
| **AI-ETH-03** | Ethics & Fairness | Evaluate societal impacts | Assess broader operational risks | OECD Principles | Ethical review documentation | Risk Committee |
| **AI-BCP-01** | Business Continuity & Resilience | Ensure AI service resilience | Define backup and recovery plans | ISO 27001 | DR test results | Infrastructure |
| **AI-BCP-02** | Business Continuity & Resilience | Plan for model failure | Establish fallback processes | ISO 42001 | Manual fallback procedures | Operations |
| **AI-TRAIN-01** | Training & Awareness | Train staff on AI governance | Deliver mandatory awareness training | ISO 42001 | Training completion records | HR / Governance |
| **AI-TRAIN-02** | Training & Awareness | Train technical teams on secure AI usage | Conduct secure AI development training | NIST AI RMF | Training materials | Security Team |
| **AI-DOC-01** | Documentation & Recordkeeping | Maintain AI documentation | Document systems, risks, and controls | ISO 42001, EU AI Act | Technical documentation | Governance Office |
| **AI-DOC-02** | Documentation & Recordkeeping | Retain decision records | Preserve assessments and approvals | DADM, ISO 42001 | Record repository | Compliance |

---

**Keep in Mind** 

### **1\. Factual & Regulatory Nuances**

* **The Federal Bill C-27 (AIDA):** Under Section 2 (*Regulatory Mapping*), you notes that Canada has no federal AI legislation. While factually true that no law is *active* or *enforced*, it would look highly proactive to mention **Bill C-27 Part 3 (the Artificial Intelligence and Data Act \- AIDA)**, which has been making its way through the legislative pipeline. Acknowledging that it is pending helps protect the longevity of this GitBook/document.  
* **Quebec Law 25 Consent Exceptions:** In Section 6 (*Lawful Basis for Processing*), note that Quebec Law 25 has highly specific provisions regarding using personal information for commercial profiling. It may be worth noting that using data for AI model *training* versus automated *inference* might require separate, explicit opt-in consent pathways under current CAIP (Canadian Association of Information Privacy) interpretations.

### **2\. Technical Control Enhancements**

* **Differential Privacy Math Validation Epsilon:** Under Section 6 (Specific Technical Controls \-\> B), you mention Epsilon-based privacy. To bolster the technical accuracy, ensure your engineering team formally documents the **Privacy Budget epsilon allocation** per model deployment. If the budget is too high, Law 25's definition of true "Anonymization" will not hold up legally.  
* **The "Exclusively Automated" Trap:** Under Section 10 (*Law law 25 Specific Requirements*), you ask *"Is the decision exclusively automated?"*. Be careful here: regulators have explicitly noted that inserting a superficial human reviewer who just "rubber stamps" the AI output does **not** exempt a company from Section 12.1. The human must have meaningful oversight capabilities. It's recommended to add a phrase like: *"A superficial human-in-the-loop does not escape automated decision obligations."*  
* **Logging Volume & Security (WORM Storage):** In Section 13, you mandate a 7-year retention period for high-impact logs including an explainability\_vector (which is often a heavy JSON payload or data blob). Keeping heavy blobs for 7 years on WORM storage can generate massive cloud hosting costs. Consider explicitly requiring **log tiering** (e.g., hot storage for year 1, cold immutable glacier storage for years 2–7) to balance compliance with cloud resource exhaustion.

