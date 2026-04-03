# AI Text Detection Study - Statistical Analysis

**Analysis Date:** 2026-04-03 12:51:05  
**Data Source:** `responses/Response-2026-03-21.csv`

---

✓ Text ID mapping saved to: `text_id_mapping.md`

## 1. Descriptive Statistics

**Number of participants:** 7

### Participant Demographics

- **Mean teaching experience:** 5.71 years (SD = 3.09)
- **Range:** 2 - 10 years

**Departments represented:**

- English Linguistics: 3
- Language Competence: 1
- IfA: 1
- English Studies (Linguistics): 1
- English Literary Studies: 1

### Text Information

- **Total number of texts:** 10
- **AI-generated texts:** 5
- **Human-written texts:** 5

### Response Information

**Total responses collected:** 70

**Classifications:**
- Classified as AI: 26
- Classified as Human: 44

### Confidence Ratings

- **Mean:** 3.44 (SD = 0.94)
- **Median:** 4
- **Range:** 1 - 5

### Response Times

- **Mean:** 73.10 seconds (SD = 43.48)
- **Median:** 69.75 seconds
- **Range:** 12.02 - 206.24 seconds

---

## 2. Accuracy Analysis

**Overall accuracy:** 75.71%

### Participant-Level Accuracy

- **Mean:** 75.71% (SD = 21.49%)
- **Range:** 40.00% - 100.00%

### Accuracy by Text Origin

- **AI-generated:** 62.86% (22/35 correct)
- **HUMAN-generated:** 88.57% (31/35 correct)

### Confusion Matrix

| Actual \ Classified | AI | Human | Total |
|---------------------|----:|------:|------:|
| **AI** | 22 | 13 | 35 |
| **HUMAN** | 4 | 31 | 35 |
| **Total** | **26** | **44** | **70** |

### Diagnostic Measures

- **Sensitivity (True Positive Rate):** 62.86%
- **Specificity (True Negative Rate):** 88.57%

---

## 3. Hypothesis Testing

### Hypotheses

- **H₀ (Null Hypothesis):** Accuracy = 50% (chance level)
- **H₁ (Alternative Hypothesis):** Accuracy ≠ 50%

### One-Sample t-Test Results

- **t-statistic:** t(6) = 3.166
- **p-value:** 0.0194
- **Mean accuracy:** 75.71%
- **95% Confidence Interval:** [59.79%, 91.64%]

### Interpretation

**Result:** REJECT H₀ (p < 0.05)

**Conclusion:** Participants performed significantly **better than chance**.

### Effect Size

- **Cohen's d:** 1.196
- **Interpretation:** large effect

---

## 4. Correlation Analysis

### Participant-Level Correlations

**Accuracy vs. Confidence:**
- Pearson r = 0.755, p = 0.0499

**Accuracy vs. Response Time:**
- Pearson r = -0.200, p = 0.6677

**Accuracy vs. Teaching Experience:**
- Pearson r = 0.455, p = 0.3053

### Response-Level Analysis

**Confidence by Correctness:**

- **Correct responses:** M = 3.70 (SD = 0.85)
- **Incorrect responses:** M = 2.65 (SD = 0.79)

**Independent t-test:** t = 4.533, p = 0.0000

---

## 5. Text Difficulty Analysis

Texts ranked by difficulty (lowest accuracy first):

| Text ID | Origin | Accuracy (%) | Confidence | Response Time (ms) |
|--------:|:-------|-------------:|-----------:|-------------------:|
| 6 | AI | 43.0 | 3.14 | 86489 |
| 2 | HUMAN | 57.0 | 3.00 | 75882 |
| 8 | AI | 57.0 | 3.00 | 72645 |
| 9 | AI | 57.0 | 2.86 | 69885 |
| 7 | AI | 71.0 | 3.00 | 65538 |
| 1 | HUMAN | 86.0 | 4.14 | 45986 |
| 10 | AI | 86.0 | 3.57 | 50485 |
| 3 | HUMAN | 100.0 | 4.00 | 67822 |
| 5 | HUMAN | 100.0 | 4.29 | 71796 |
| 4 | HUMAN | 100.0 | 3.43 | 124508 |

---

## 6. Visualizations

Generating visualizations...

- ✓ `accuracy/histogram.png`
- ✓ `accuracy/boxplot.png`
- ✓ `accuracy/by_origin.png`
- ✓ `accuracy/confusion_matrix.png`
- ✓ `confidence_time/confidence_distribution.png`
- ✓ `confidence_time/confidence_by_correctness.png`
- ✓ `confidence_time/response_time_distribution.png`
- ✓ `confidence_time/response_time_by_correctness.png`
- ✓ `correlations/experience_vs_accuracy.png`
- ✓ `correlations/confidence_vs_accuracy.png`
- ✓ `by_text/accuracy_by_text.png`

---

## Summary

Analysis complete! All results have been saved to: `analysis_Response-2026-03-21_20260403_125105`

### Generated Files

**Reports:**
- `analysis_results.md` - This comprehensive analysis report
- `text_id_mapping.md` - Reference guide mapping text IDs to titles

**Visualizations:**
- `accuracy/` - Accuracy distribution and performance metrics
- `confidence_time/` - Confidence and response time analyses
- `correlations/` - Relationship analyses between variables
- `by_text/` - Item-level difficulty analysis

