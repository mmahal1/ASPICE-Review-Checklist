# Automotive SPICE (ASPICE) Review Checklist

**An Excel-based checklist for internal process reviews, gap analysis, and engineering self-assessments.**

This repository contains `ASPICE_Complete_Review_Checklist.xlsx`, a practical working aid for reviewing engineering practices, documenting evidence, assigning findings, and tracking corrective actions.

> **Scope and version:** The checklist wording is derived from **Automotive SPICE PAM 3.1** base practices. It is **not** an ASPICE PAM 4.0 checklist and is **not** an official VDA assessment instrument. ASPICE 4.0 changes process names, structure, and assessment content; do not assume this workbook maps directly to PAM 4.0.

## What's included

- **System engineering:** SYS.1–SYS.5
- **Software engineering:** SWE.1–SWE.6
- **Supporting processes:** SUP.1, SUP.8, SUP.9, SUP.10
- **Management and acquisition:** MAN.3 and ACQ.4
- **Capability Level 2 review aids:** GP2
- **Summary dashboard:** Counts of Pass, Fail, Open, N/A and not-yet-rated checks, with calculated pass rates
- **Finding tracking:** Severity, comments, owners, due dates, and evidence / work-product references
- **Legend:** Usage instructions and an example finding

## How to use

1. Download `ASPICE_Complete_Review_Checklist.xlsx` and open it in Microsoft Excel.
2. Read the **Legend** worksheet first, including the PAM 3.1 scope note.
3. Enter the project/system and review scope/baseline in **Summary**.
4. Open the relevant process worksheets and review each check against actual project evidence.
5. Record a **Result** (`Pass`, `Fail`, `Open`, or `N/A`), along with evidence and findings where appropriate.
6. For findings, enter **Severity**, **Comment / Finding**, **Owner**, and **Due date**.
7. Return to **Summary** to review completion status and open issues. Save a dated copy for each review/baseline.

**Rating guidance:** `Pass` = fulfilled and evidenced; `Fail` = gap requiring correction; `Open` = not yet resolved/verified; `N/A` = not applicable with justification. The workbook's pass rate is a **tracking metric**, not an Automotive SPICE capability rating.

## Intended audience

Systems and software engineers, requirements engineers, quality assurance teams, process improvement specialists, project managers, and internal reviewers working on automotive development projects.

## Important limitations

- This is an **independent review aid**, not an official VDA publication, certification, formal assessment method, or guarantee of ASPICE conformance.
- The checks are interpretations derived from PAM 3.1 base practices; they do not replace the full process assessment model, assessment indicators, or professional assessor judgment.
- The included **GP2** sheet supports internal review but does not by itself establish Capability Level 2.
- Review results depend on project scope, objective evidence, reviewer judgment, and applicable customer or organizational requirements.
- Check the current applicable Automotive SPICE version and assessment requirements before using the workbook for customer or supplier assessments.

## Download

Open [`ASPICE_Complete_Review_Checklist.xlsx`](./ASPICE_Complete_Review_Checklist.xlsx) and select **Download raw file** on GitHub, or download the repository as a ZIP from **Code → Download ZIP**.

## Feedback and contributions

Suggestions, corrections, and additional review checks are welcome through GitHub Issues or Pull Requests. Please identify the relevant process, checklist ID, and the rationale for any proposed change.

## License

No license has been selected yet. If you want others to redistribute or modify this checklist, add a suitable `LICENSE` file after deciding which permissions you want to grant.

---

**Disclaimer:** This project is independently maintained and is not affiliated with or endorsed by VDA or Automotive SPICE rights holders. The checklist is provided as a review aid; users remain responsible for validating its suitability for their projects.
