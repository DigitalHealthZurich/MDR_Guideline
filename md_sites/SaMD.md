---
layout: default
title: Software as a Medical Device
---

# Does It Qualify as a Software as a Medical Device (SaMD) under MDR 2017/745?

This section provides a structured approach to determining whether software qualifies as a **Software as a Medical Device (SaMD)** under Annex VIII of the Medical Device Regulation (MDR) 2017/745, focusing on its intended purpose, mode of action, and independence from hardware.

---

## Table of Contents
- [Software as a Medical Device](#software-as-a-medical-device)
- [Identify the Intended Medical Purpose](#identify-the-intended-medical-purpose)
- [Determine the Mode of Action](#determine-the-mode-of-action)
- [Verify If the Software Operates Independently](#verify-if-the-software-operates-independently)
- [Apply MDR Classification Rules](#apply-mdr-classification-rules)
- [Regulatory Requirements for SaMD](#regulatory-requirements-for-samd)
- [Additional References](#additional-references)

---

## Software as a Medical Device
Software qualifies as **Software as a Medical Device (SaMD)** if it achieves its medical purpose independently of dedicated hardware. This section provides key steps to determine if a software product meets the MDR definition and classification criteria. The **International Medical Device Regulators Forum (IMDRF)** defines **SaMD** as:

> "Software intended to be used for one or more medical purposes that perform these purposes without being part of a hardware medical device."

SaMD may perform functions such as:
- **Analyzing medical data** (e.g., detecting anomalies in medical imaging)
- **Providing diagnostic or treatment recommendations** (e.g., AI-based disease detection)
- **Supporting clinical decisions** (e.g., risk prediction models)
- **Monitoring patient conditions remotely** (e.g., ECG monitoring apps)

---

## Identify the Intended Medical Purpose
A software product qualifies as a medical device if it serves at least one of the following medical purposes, as defined in **Article 2(1) of MDR 2017/745**:

- **Diagnosis, prevention, monitoring, treatment, or alleviation of disease**
- **Diagnosis, monitoring, treatment, alleviation, or compensation for an injury or disability**
- **Investigation, replacement, or modification of anatomy or a physiological process**
- **Providing information derived from in vitro diagnostic examination of specimens from the human body**

[More information under Article 2(1) of MDR 2017/745](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:32017R0745#d1e32-1-1)

---

## Determine the Mode of Action
SaMD must achieve its intended medical purpose** by processing medical data, rather than through direct physical interaction.

- If the software **analyzes medical data** and provides clinical output influencing diagnosis, treatment, or monitoring → It qualifies as SaMD.
- If the software **only stores, archives, or retrieves data without processing it in a medically relevant way** → It does not qualify as SaMD.

**Example:**  
AI-based image analysis software detecting tumors in radiology scans → **SaMD**  
A patient database system storing records without medical analysis → **Not SaMD**  

---

## Verify If the Software Operates Independently
- If the software **functions on general-purpose hardware (e.g., smartphone, cloud server) without requiring a specific medical device**, it is more likely **SaMD**.
- If the software **controls, influences, or is embedded in a physical medical device**, then it **may not** be classified as **SaMD** but rather as part of a **medical device system**.

**Example:**  
A smartphone app analyzing ECG data for heart rate abnormalities → **SaMD**  
Embedded software inside an ECG machine controlling its hardware → **Not SaMD**  

---
<!--
Move to classification TBD
## Apply MDR Classification Rules
Once software qualifies as **SaMD**, the next step is to classify it based on **risk categories** outlined in **Annex VIII of MDR 2017/745**. Classification depends on:
- The **impact of the software’s output** on patient health.
- The **criticality of the decisions** it supports.

### **Rule 11: Software Classification under MDR**
- **Class I:** Software used for lifestyle and wellness tracking (e.g., step counters, heart rate monitors without medical claims).
- **Class IIa:** Software supporting non-critical diagnostic decisions (e.g., image analysis for routine findings).
- **Class IIb:** Software influencing treatment decisions with significant impact (e.g., decision-making triage systems).
- **Class III:** Software making critical treatment decisions (e.g., autonomous software controlling insulin pumps).

[Read Annex VIII of MDR 2017/745](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:32017R0745#anx_XIII)

---
TBD add links
-->
## Regulatory Requirements for SaMD
Under **MDR 2017/745**, SaMD must comply with the following key requirements:
- **Clinical Evaluation** (Article 61, Annex XIV) → Proof of safety and effectiveness.
- **Cybersecurity & Data Protection** (Annex I, ISO 62304, GDPR) → Ensuring secure data processing and lifecycle management.
- **Post-Market Surveillance (PMS)** (Article 83, Annex III) → Continuous monitoring of software performance.

---

## Additional References
- **[MDR 2017/745 - Qualification - Rule 11 of Annex VIII](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:32017R0745#anx_XIII)**
- **[MDCG 2019-11: Guidance on Software Qualification](https://health.ec.europa.eu/system/files/2021-10/md_mdcg_2019_11_guidance_samd_en_0.pdf)**
- **[IMDRF Software as a Medical Device Framework](https://www.imdrf.org/documents/software-medical-device-key-documents)**
- **[IEC 62304 Standard for Medical Device Software](https://www.iso.org/standard/38421.html)**
