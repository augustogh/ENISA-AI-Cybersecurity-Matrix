# ENISA-AI-Cybersecurity-Matrix
Cybersecurity threat analysis and matrix for Artificial Intelligence (AI) systems, based on the framework by ENISA (the EU Agency for Cybersecurity). Includes mapping to the CIA triad, affected components, and the ML lifecycle.

Ya que la solicitud original se hizo en español, generaré la descripción en inglés solicitada, pero mantendré el resto de la respuesta en español (como las instrucciones de GitHub) para ser consistente con el idioma de la conversación.

Aquí está la descripción en inglés para el repositorio:

-----

## English Description for the Repository

### Short Description

"Cybersecurity threat analysis and matrix for Artificial Intelligence (AI) systems, based on the framework by **ENISA** (the EU Agency for Cybersecurity). Includes mapping to the CIA triad, affected components, and the ML lifecycle."

### README.md (English Version)

```markdown
# 🛡️ Cybersecurity Threat Matrix for AI Systems (ENISA)

This repository contains the cybersecurity threat matrix for Artificial Intelligence (AI) systems, structured and rationalized based on the framework from the **European Union Agency for Cybersecurity (ENISA)**.

The objective is to provide a reference tool for **risk management** in Machine Learning (ML) projects, allowing users to identify, evaluate, and mitigate vulnerabilities throughout the AI lifecycle.

## 📊 Core Content

The main file is `Amenazas_IA_ENISA_racional.json`, which details each threat with the following metrics:

| Key Column | Description |
| :--- | :--- |
| `Threat Category` | General category to which the threat belongs (e.g., Unintentional Damage, Abuse). |
| `Threat` | Specific name of the threat (e.g., Data Poisoning, Data Quality Failure). |
| `Racional` | Spanish justification and context for the threat, often with references to standards. |
| **Confidentiality** | Impact on Confidentiality (CIA triad). |
| **Integrity** | Impact on Integrity (CIA triad). |
| **Availability** | Impact on Availability (CIA triad). |
| **Artefacts/Data/Models/Actors/Environment** | Component of the AI system affected. |
| **Lifecycle Phases (1 to 12)** | Indicates the phase of the ML project where the threat is relevant (e.g., Training, Deployment). |

## 🛠️ How to Use

This dataset can be utilized by:

1.  **Machine Learning Engineers (MLOps):** To integrate security controls into the model training and deployment stages.
2.  **Risk and Security Analysts:** To perform specific risk assessments for AI systems.
3.  **Researchers:** As a foundation for studies on threat taxonomy in AI cybersecurity.

## 📄 License

This project is licensed under the **MIT License**. See the `LICENSE` file for more details.
```
