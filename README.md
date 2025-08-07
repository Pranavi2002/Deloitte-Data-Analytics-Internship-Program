# Deloitte Australia Data Analytics Virtual Internship (Forage)

This repository presents the work I completed during the **Deloitte Australia Data Analytics Virtual Internship** hosted on [Forage](https://www.theforage.com/). The simulation focused on analyzing business data for a fictional client, **Daikibo Industrials**, and making data-driven recommendations.

---

## ✅ Task 1: Telemetry Data Analysis (Tableau)

Daikibo Industrials shared one month of machine telemetry data from their global factories. I analyzed this data to help identify patterns in machine breakdowns.

### 🔍 Objective
Determine:
- Which factory experienced the highest number of machine breakdowns?
- Which machine types were most frequently associated with breakdowns?

### 📊 Solution
Created an interactive Tableau dashboard to visualize machine health, breakdown frequency, and identify root causes.

![Telemetry Dashboard](screenshots/Task-1_Output.png)

### 💡 Key Findings
- **Factory Seiko (Osaka)** had the **highest machine failure rate**.
- Specific machine types were identified as high-risk in that location.

---

## ✅ Task 2: Gender Pay Equality Classification (Excel)

Daikibo faced numerous internal complaints related to **gender-based salary inequality**. The Forensic Tech team developed an algorithm to compute an **Equality Score** for various job roles across factories.

### 🧮 Objective
Classify each job role's **Equality Score** (ranging from -100 to +100) into one of the following:

| Equality Score Range                      | Equality Class           |
|-------------------------------------------|--------------------------|
| Exactly **10** or **-10**                 | Fair                     |
| Between **-20 to -11** or **11 to 20**    | Unfair                   |
| Less than **-20** or greater than **20**  | Highly Discriminative    |

### 📂 Tools Used
- Microsoft Excel
- `IF()` and `OR()` logic for classification

### ✅ Sample Formula
```excel
=IF(OR(C2=10, C2=-10), "Fair", IF(OR(C2<-20, C2>20), "Highly Discriminative", "Unfair"))
```

This formula evaluates the Equality Score and assigns the correct class.

---

## 🛠 Skills Applied
*** Data Cleaning and Classification (Excel)
*** Dashboard Design and Data Visualization (Tableau)
*** Business Data Analysis
*** Logical Functions and Conditional Formatting

---

## 🏁 Outcome
This virtual internship enhanced my skills in using data to drive business insights, strengthened my ability to classify and visualize key metrics, and improved my hands-on experience with real-world analytics tools.

---

## 👩‍💻 Author
### Pranavi Kolipaka
Feel free to connect: 
- [LinkedIn] (https://www.linkedin.com/in/vns-sai-pranavi-kolipaka-489601208/) 
- [GitHub] (https://github.com/Pranavi2002)