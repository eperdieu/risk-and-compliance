# risk-assessment-and-compliance

This repo holds work I completed during CIT-45100: Risk Assessment and Compliance at Purdue University Indianapolis. The course focused on government and industry frameworks, threat modeling, security control design, and real-world risk analysis applied to a fictional healthcare organization called Health Network.

## Project Overview

The semester project involved a full risk assessment of Health Network across three parts. I built out the threat model, asset inventory, data flow diagrams, and security control catalog for a healthcare network handling patient data, payment processing, and medical messaging.

## Project Structure

The work was completed across three parts over the semester.

**Part 1** covered the initial asset inventory, process map, and threat identification. I compared Microsoft Threat Modeling Tool and AWS Threat Composer side by side, evaluating each tool's advantages and limitations for modeling Health Network's architecture.


**Part 2** expanded the threat model using AWS Threat Composer with full STRIDE classification, data flow diagrams built in Lucidchart, and mitigation mapping across 10 identified threats covering SQL injection, DDoS, ransomware, physical theft, and insider threats.


**Part 3** finalized the security control catalog with six controls across preventive, detective, and corrective phases, a control interaction diagram, gap analysis identifying residual risks, and a MITRE ATT&CK mapping for a LockBit ransomware scenario against Health Network.

## What's Covered

| Deliverable | Description |
|-------------|-------------|
| Asset Inventory | Classified assets across Health Network's production environment |
| Asset Classification Diagram | Data flow and trust boundary diagram built in Microsoft Threat Modeling Tool |
| Data Flow Diagrams | Interaction diagrams showing data movement across HNetPay, HNetExchange, and HNetConnect |
| Threat Model | 10 STRIDE-classified threats modeled in AWS Threat Composer with mitigations mapped |
| Process Map | HNetConnect patient search flow with SQL injection and information disclosure risks identified |
| Security Control Catalog | Preventive, detective, and corrective controls with implementation steps, risk mitigation, and testing criteria |
| Control Interaction Diagram | Visual showing how controls layer across attack phases |
| MITRE ATT&CK Mapping | LockBit ransomware techniques mapped to Health Network using ATT&CK Navigator |
| MITRE ATT&CK Technique Breakdown | Detailed analysis of each technique including targeted assets, detections, and controls |
| Framework Comparison | NIST, ISO, and supply chain security model analysis |
| Case Study Analysis | Breach post-mortem and compliance critique (Everbridge) |
| Awareness Campaign Evaluation | Critique of real cybersecurity awareness material |

## Tools & Frameworks

![OWASP Threat Dragon](https://img.shields.io/badge/OWASP-Threat_Dragon-purple?logo=owasp&logoColor=white)
![Microsoft TMT](https://img.shields.io/badge/Microsoft-Threat_Modeling_Tool-0078D4?logo=microsoft&logoColor=white)
![AWS Threat Composer](https://img.shields.io/badge/AWS-Threat_Composer-FF9900?logo=amazonaws&logoColor=white)
![Lucidchart](https://img.shields.io/badge/Lucidchart-Diagrams-F97A1F)
![NIST](https://img.shields.io/badge/NIST-CSF-0033A0)
![STRIDE](https://img.shields.io/badge/STRIDE-Threat_Modeling-grey)

## Notes

All work was performed on a fictional healthcare organization for educational purposes. No real patient or payment data was involved.
