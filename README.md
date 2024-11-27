# **Inferential Statistics Case Study**

## **Business Context**
A leading pharmaceutical company has tested five batches of a vaccine, with 300,000 doses already administered. The sixth batch, consisting of 60,000 doses, requires quality assurance testing to determine its effectiveness and curing time.

Previous data indicates that each dose is twice as likely to be satisfactory as unsatisfactory. This analysis focuses on inferring the quality of the sixth batch, rather than conducting a clinical trial.

---

## **Objective**
To analyze random samples from the sixth batch to infer its quality and curing time by performing probability calculations and descriptive statistical analysis.

---

## **Tasks**

### **Task 1: Analyze 10 Randomly Selected Doses**
1. **Determine the Probability Distribution of Unsatisfactory Doses**:
   - Each dose is twice as likely to be satisfactory as unsatisfactory.
   - Use the **Binomial Distribution** for calculations.

2. **Probability Calculations**:
   - **Exactly 3 out of 10 doses are unsatisfactory**:  
     \( P(X = 3) \)
   - **At most 3 out of 10 doses are unsatisfactory**:  
     \( P(X \leq 3) \)
   - **More than 8 out of 10 doses are satisfactory**:  
     \( P(X > 8) \)

---

### **Task 2: Analyze 20 Doses Requested by NYC Administration**
1. **Probability Calculations**:
   - **At least 11 out of 20 doses are unsatisfactory**:  
     \( P(X \geq 11) \)
   - **At most 5 out of 20 doses are unsatisfactory**:  
     \( P(X \leq 5) \)
   - **At least 13 out of 20 doses are satisfactory**:  
     \( P(X \geq 13) \) (for satisfactory doses)

---

### **Task 3: Analyze the Time of Effect for 50 Doses**
1. **Use the Time of Effect Data**:
   - **Probability that the time of effect is less than 11.5 hours**:  
     \( P(T < 11.5) \)
   - **Probability that the time of effect is more than 10 hours**:  
     \( P(T > 10) \)

2. **Calculate the 90th Percentile of the Time of Effect**:  
   - Identify the value below which 90% of the data lies.

---

## **Dataset Description**
The dataset, `doses.csv`, includes the following feature:
- **Drug Serial Number**: Unique serial number for each dose.

