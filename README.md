# 🔗 Label Setu

### AI-Assisted Legal Metrology Compliance Checker for Packaged Commodities

> **Label Setu** is an AI-assisted compliance platform designed to help Legal Metrology enforcement officials analyze packaged commodity labels, identify mandatory declarations, detect potential violations, and generate explainable compliance assessments.

---

## 🏆 Smart India Hackathon

**Problem Domain:** Legal Metrology & Consumer Protection  
**Solution:** AI-Assisted Packaged Commodity Label Compliance  
**Application:** Enforcement & Inspection Support

Label Setu aims to reduce the time and manual effort required to inspect packaged commodity labels while providing structured, evidence-based and explainable compliance results.

---

## 💡 The Problem

Legal Metrology enforcement officials need to verify whether packaged commodities display mandatory declarations such as:

- Manufacturer / Packer / Importer details
- Net quantity
- Maximum Retail Price (MRP)
- Date-related declarations
- Consumer care information
- Batch / Lot information
- Readability and declaration requirements

Manual inspection of these declarations can be time-consuming and prone to inconsistency, especially when processing a large number of products.

---

## 🚀 Our Solution

**Label Setu** combines OCR, NLP, and a deterministic Legal Metrology rule engine to transform a product-label image into a structured compliance assessment.

### 🔄 How it works

```text
       📷 Product Label Image
                │
                ▼
        ┌─────────────────┐
        │    EasyOCR      │
        │ Text + BBoxes   │
        │ + Confidence    │
        └────────┬────────┘
                 │
                 ▼
        ┌─────────────────┐
        │ NLP & Extraction│
        │ spaCy + Patterns │
        └────────┬────────┘
                 │
                 ▼
        ┌─────────────────┐
        │ Legal Metrology │
        │   Rule Engine   │
        └────────┬────────┘
                 │
                 ▼
        ┌─────────────────┐
        │ Compliance      │
        │ Assessment      │
        └────────┬────────┘
                 │
        ┌────────┴─────────┐
        ▼                  ▼
   👮 Officer UI      🗄️ MongoDB Atlas