# LandingPage-A-B-Test-Hypothesis-Conversion-Analysis-with-Python
This project analyzes the effectiveness of a redesigned landing page through A/B testing, comparing conversion rates between the original and new versions. The goal was to determine whether the new design leads to a statistically significant improvement in user engagement.

## 🎯 Objective

To identify whether a redesigned landing page significantly improves conversion rates compared to the original, using A/B testing principles within a prescriptive analytics framework.

---

## 🧪 Methodology

- **Data Validation**: Checked consistency between `group` and `landing_page` columns.
- **Exploratory Data Analysis**: Compared conversion trends across control and treatment groups.
- **Hypothesis Testing**: Conducted a two-sample z-test to evaluate statistical significance.
- **Decision Logic**: Interpreted p-value vs business impact to decide on rollout.

---

## 📊 Dataset Overview

| Column         | Description                                 |
|----------------|---------------------------------------------|
| `user_id`      | Unique identifier per visitor               |
| `group`        | Group assignment: control or treatment      |
| `landing_page` | Page version shown to user                  |
| `converted`    | Binary indicator of successful conversion   |

---

## 📈 Results Snapshot

- **Control Conversion Rate**: 11.96%  
- **Treatment Conversion Rate**: 12.08%  
- **P-value**: 0.19  
- **Conclusion**: The results are **not statistically significant** at α = 0.05. The observed uplift does not justify a rollout without further testing or optimization.

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**, **SciPy**
- **Jupyter Notebook**
- **Z-test**, **Confidence Intervals**, **A/B Testing Frameworks**

---

## 🧠 Skills Applied

- Prescriptive Analytics
- Experimental Design
- Statistical Testing & Inference
- Data Cleaning & EDA
- Business Communication via Insights

---

## 📌 Key Takeaways

This project demonstrates how structured experimentation with statistical backing can inform business decisions. It highlights the importance of balancing statistical significance with practical impact in product and UX design workflows.

---

## 📫 Contact

For feedback or collaboration:

**Rishikesh More**  
📧 more.rishikesh.18@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/more-rishikesh-p07)

