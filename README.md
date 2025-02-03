# Inferential Statistics - Medicon Dose Testing Case Study

## **Context**
Medicon, a pharmaceutical company, has manufactured the **sixth batch (40,000 units)** of COVID-19 vaccine doses. The vaccine has already undergone **clinical trials** and has been administered to approximately **200,000 people** across the first five batches.

Now, before releasing the **sixth batch**, Medicon's **quality assurance team** needs to evaluate:
- The **time of effect** (i.e., time taken for the dose to completely cure COVID-19).
- The **quality assurance** (i.e., whether the dose is satisfactory or not).

This is **not a clinical trial** but a **quality assurance** study to ensure batch consistency and effectiveness before proceeding with mass production.

---

## **Problem Statement**
The previous analysis has determined that a dose is **10 times more likely to be satisfactory than unsatisfactory**.

As a Data Scientist in the **quality assurance team**, your goal is to analyze the collected data, apply **inferential statistical methods**, and provide actionable insights to help Medicon make informed decisions about the vaccine batch.

---

## **Key Questions & Analysis**
### **Q1: Probability Distribution for Unsatisfactory Doses**
Medicon’s quality assurance team has selected **100 volunteers**, each receiving **one dose**. You need to determine:
1. **The probability distribution for the number of unsatisfactory doses.**
2. **The probability that exactly 3 doses will not do a satisfactory job.**
3. **The probability that at most 3 doses will be unsatisfactory out of 100.**

### **Q2: Probability Analysis for a Purchase Order**
The **New York City administration** is purchasing **200 doses** for healthcare workers who tested positive for COVID-19. The task is to determine:
1. **The probability that at least 30 doses will not do a satisfactory job out of 200 doses.**

### **Q3: Effectiveness Testing Using Sample Data**
The quality assurance team has collected **50 volunteers**, each receiving **one dose**. The dataset **'doses.csv'** contains the **time of effect** (in hours) for these 50 doses. Based on this sample, analyze:
1. **The probability that the time of effect is less than 11.5 hours.**
2. **The 90th percentile of the time of effect for the doses.**
3. **The 95% confidence interval for the population mean (time of effect).**

---

## **Methodology**
To address the key questions, we will apply **inferential statistics** methods including:
- **Binomial probability distribution** (for satisfactory vs. unsatisfactory dose probability analysis).
- **Cumulative probability distributions**.
- **Percentile analysis**.
- **Confidence interval estimation**.

---

## **Dataset Information**
The dataset **'doses.csv'** contains information about the time of effect (in hours) for a sample of 50 vaccine doses.

**Columns:**
- `time_of_effect`: The time taken (in hours) for the dose to fully cure COVID-19.
- `drug_serial_number` - A unique identifier for each drug dose.

---

## **Technologies Used**
- **Python** (NumPy, SciPy, Pandas, Matplotlib, Seaborn)
- **Statistical Analysis** (Inferential statistics, confidence intervals, hypothesis testing)
- **Data Visualization** (Histogram, probability distributions, confidence interval plots)

---

## **Expected Outcomes**
- Determine the probability distribution for unsatisfactory doses.
- Compute key probability estimates to assess batch quality.
- Estimate population characteristics using inferential statistics.
- Provide actionable insights for Medicon’s quality assurance team.

---

## **How to Use This Repository**
1. Clone the repository:
   ```bash
   git clone https://github.com/Sourena-Mohit/Medicon-Dose-Testing-Case-Study.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Medicon-Dose-Testing-Case-Study
   ```

---

## **Contributing**
Contributions are welcome! If you have improvements or insights, feel free to submit a pull request.

## **License**
This project is licensed under the **MIT License**.

---

