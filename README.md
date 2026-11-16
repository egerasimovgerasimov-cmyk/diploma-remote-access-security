# A Software and Hardware Model for Protecting Remote Access to Enterprise Resources

**Graduation thesis** · programme 10.02.05 "Information Security of Automated Systems"

**English** | [Русский](README.ru.md)

- **Author:** Egor Gerasimov, group 9OIB211
- **Institution:** Altai Industrial and Economic College (KGBPOU APEK), Barnaul, Russia
- **Year:** 2025
- **Supervisor:** A. M. Parkhatskaya
- **Reviewer:** N. Yu. Togusov
- **Full text:** [diploma-gerasimov-2025.docx](diploma-gerasimov-2025.docx) (in Russian)

---

## What the thesis is about

Remote access to corporate systems is one of the main attack vectors against
financial institutions. The thesis builds a protection model for remote access
that combines software and hardware controls and maps them to Russian
regulatory requirements: FSTEC orders, Bank of Russia rules, Federal Law 152-FZ
(personal data) and 187-FZ (critical information infrastructure).

**Object of study** — remote access to corporate resources at Sberbank of
Russia.
**Subject of study** — a protection model based on GOST R ISO/IEC 27001 and
FSTEC orders.
**Goal** — design a remote-access protection model built on software and
hardware tools.

## What was done

1. **Analysis.** Characterised the business domain and the bank's
   organisational structure, analysed information-security risks, justified the
   task set, selected organisational and engineering measures, and reviewed the
   security appliances used by the bank.
2. **Design.** Proposed a **Zero Trust** model: strong multi-factor
   authentication (password + JaCarta GOST hardware token or SberID + biometrics
   for critical operations), GOST-compliant VPN, network segmentation and
   micro-segmentation, device control and session monitoring. The chapter also
   defines the information model of protected data, organisational and legal
   measures, an implementation plan and the list of design decisions.
3. **Economic case.** Implementation costs of ₽250 M capital and ₽120 M
   operating over three years (₽370 M total) against roughly ₽1.2 bn of
   cumulative savings over the same period — about ₽400 M per year from reduced
   attack losses, lower fines and SOC automation.

## Structure

```
Introduction
Part 1. Analysis
  1.1 Business domain and enterprise characteristics
  1.2 Information security risk analysis
  1.3 Task set and justification
  1.4 Selection of protective measures
  1.5 Review of security tools at Sberbank
Part 2. Design
  2.1 Concept of the software and hardware protection model
  2.2 Model architecture
  2.3 Remote-access security model (Zero Trust)
  2.4 Tools and their justification
  2.5 Information model of protected data and access control
  2.6 Organisational and legal measures
  2.7 Implementation plan
  2.8 Summary of design decisions
Part 3. Economic efficiency
Conclusion
References
Appendices A, B, C
```

## Topics covered

Zero Trust · multi-factor authentication · GOST VPN · JaCarta GOST · HSM ·
network segmentation · device control · SIEM (IBM QRadar) · GOST R ISO/IEC
27001 · FSTEC orders 17, 21, 239 · 152-FZ · 187-FZ · risk assessment

## Reading the thesis

Download [diploma-gerasimov-2025.docx](diploma-gerasimov-2025.docx) and open it
in Microsoft Word, LibreOffice or R7 Office. The text is in Russian, about 70
pages including appendices with diagrams, risk tables and calculations.

## Note

The work was carried out during a pre-graduation internship; information about
the bank comes from public sources and course materials. The text is published
as the author's portfolio piece. When citing, please reference the author and
the title.
