# 🏡 The Badge Effect: Measuring the Impact of Price Signals on Airbnb Engagement

This project evaluates whether displaying a **"Good Price" badge** on Airbnb listings increases user engagement and accelerates decision-making.

## 📌 Project Overview

We designed a controlled A/B survey experiment to measure how price signals (in the form of a badge) influence user interest in a listing. The study combines real human survey responses with synthetic responses generated using a large language model (LLM) to increase sample size and robustness.

### ✨ Research Question

**Does highlighting a listing's favorable pricing through a "Good Price" badge increase user engagement and reduce booking decision time?**

---

## 📁 Project Structure

ab_test_airbnb_project/
│
├── airbnb_v1_5_explore.ipynb # Main Jupyter Notebook for data cleaning and analysis
├── Team 4 Submission.pdf # Project report detailing methodology, results, and recommendations
├── README.md # Project documentation

---

## 📊 Key Metrics

- **Click Likelihood** (0–10 scale)
- **Save to Favorites** (binary)
- **Time to Decision** (minutes)
- **Ratings on Price, Location, Photo, Reviews**

---

## 🧪 Methodology

- **Control Group**: Users view a listing *without* the Good Price badge
- **Treatment Group**: Users view the same listing *with* the badge
- Responses collected via Qualtrics + LLM augmentation
- Analysis includes:
  - Balance checks on demographics
  - Treatment effect estimation (with/without controls)
  - Difference-in-differences on perceived price ranking

---

## 📈 Key Findings

- **+0.49 increase** in click likelihood with badge
- **-45.2 hours reduction** in decision time with badge
- Badge effect varies by income and budget segment

---

## 💡 Business Recommendations

1. **Display the badge on the main feed**, not just within listing pages
2. **Segment users by budget/income** to tailor pricing signals
3. **Use the badge as a conversion nudge** for high-intent but hesitant users

---

## 🧪 Limitations

- Small human sample size (n = 76)
- Demographic skew: majority female and aged 20–29
- Artificial listing context (not a real browsing session)

---

## 👨‍💻 Authors

Team 4:  
- Pleng Witayaweerasak  
- Yitian Xu  

CMU, A/B Testing Class — Spring 2025

