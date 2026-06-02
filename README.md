# Data Converter

> Turn messy real-world bank statements into structured accounting-ready data.

Built and tested against real-world bank statement conditions including:

• Scanned PDFs
• OCR-damaged documents
• Multi-page statements
• Bank-specific layouts
• Multiline transaction descriptions
• Formatting inconsistencies

Data Converter is a Windows desktop tool for extracting transactions from PDF bank statements and preparing them for accounting workflows.

It was built against real-world statement problems: scanned PDFs, OCR-damaged documents, multi-page statements, bank-specific layouts, multiline descriptions, and messy transaction formatting.

This public release is intended for community testing, feedback, and early adoption.

---

## What it does

```text
Bank statement PDF
        ↓
Data Converter
        ↓
Structured transactions
        ↓
Accounting-ready export
```

Data Converter helps convert bank statement PDFs into structured transaction data suitable for review, cleanup, bookkeeping, and accounting export workflows.

It is designed around one practical goal:

> Preserve financial truth from messy documents.

---

## Why it exists

Bank statements look simple until you try to automate them.

Real-world statements can include:

- scanned pages
- OCR corruption
- inconsistent spacing
- multiline descriptions
- bank-specific statement layouts
- old statement formats
- transaction grouping issues
- balance continuity problems
- huge multi-page PDFs

Data Converter was created to reduce manual transaction extraction work and make financial document processing more reliable.

---

## Current public release

**Version:** 9.0.5 public release  
**Platform:** Windows  
**Release type:** Community testing build

The public release includes the installer and public documentation only.

---

## What is included

- Windows installer
- Public README
- Privacy notice
- Public release documentation

---

## What is not included

For privacy, security, and certification reasons, this public repository does **not** include:

- bank statement datasets
- sample customer statements
- OCR source libraries
- certification corpuses
- internal reports
- private test documents
- confidential parser research

Please do not upload or share real bank statements publicly in GitHub issues.

---

## Installation

1. Download the latest release from the GitHub Releases page.
2. Run `DataConverter_Setup.exe`.
3. Open Data Converter from Windows.
4. Select a PDF bank statement.
5. Review the extracted transactions before using them in accounting software.

---

## Important privacy warning

Bank statements contain sensitive personal and financial information.

Do not post real bank statements, screenshots, account numbers, balances, customer names, addresses, or transaction histories in public GitHub issues.

If you need to report a bug, describe the problem using a redacted example.

Example:

```text
Bank: Example Bank
Statement type: Business account
Issue: Multiline transaction description was split into two rows
Expected: One transaction row
Actual: Two transaction rows
Sensitive data removed: Yes
```

---

## Designed for messy real-world PDFs

Data Converter has been tested against a large internal validation set of real-world PDF conditions, including:

- clean digital PDFs
- scanned documents
- OCR-heavy PDFs
- older bank layouts
- long statements
- noisy formatting
- statement variants across banks

The private validation corpus is not included in this public repository.

---

## Accounting workflow philosophy

Data Converter is built around review-first accounting workflows.

The goal is not to blindly post transactions into accounting systems.

The goal is to help users move from:

```text
messy bank statement
```

to:

```text
reviewable structured transaction data
```

Human review remains important, especially for ambiguous payments, transfers, tax payments, loan payments, credit card settlements, payroll, and other transactions where the bank movement may not tell the full accounting story.

---

## Known limitations

Data Converter may require manual review when documents include:

- very poor scan quality
- handwritten notes over transaction tables
- missing pages
- rotated or skewed scans
- password-protected PDFs
- unusual bank layouts
- newly changed bank statement formats
- transactions that require accounting judgment

No PDF extraction system should be treated as a replacement for accounting review.

---

## Community testing

This release is open for community testing.

Helpful feedback includes:

- installer problems
- app startup issues
- PDF loading issues
- extraction failures
- formatting problems in exported data
- unclear error messages
- Windows compatibility issues

Please remove all sensitive financial information before sharing any example.

---

## Suggested issue format

```text
Version:
Windows version:
PDF type: digital / scanned / unknown
Bank or statement type, if safe to share:
What happened:
What you expected:
Was sensitive data removed before sharing? yes / no
```

---

## Project direction

Data Converter is the first layer of a broader financial data workflow:

```text
PDF bank statements
        ↓
trusted transaction extraction
        ↓
classification and review
        ↓
accounting-ready export
```

The long-term goal is to make messy financial documents easier to transform into reliable, reviewable financial data.

---

## Disclaimer

Data Converter is provided for assistance and workflow support only.

Users are responsible for reviewing extracted data before relying on it for bookkeeping, tax, audit, compliance, or accounting decisions.

