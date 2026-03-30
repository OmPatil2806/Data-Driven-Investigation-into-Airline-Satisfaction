# ✈️ When Passengers Stop Flying: A Data-Driven Investigation into Airline Satisfaction

> **Explanatory Data Analysis | M512A Data Visualisation & Communications**  
> **Author:** Om Dipak Patil · **GH Number:** GH1044372  
> **Client:** Airline Management Board (COO & Head of Customer Experience)

---

## 📌 Project Description

With only **43% of passengers leaving satisfied**, this report investigates the root causes behind a quantifiable airline satisfaction crisis. This is not a scientific paper — every chart and narrative has been calibrated for senior decision-makers who need unambiguous, actionable evidence rather than statistical abstractions.

The report answers one core business question:  
> *"Where should the airline invest to fix dissatisfaction most efficiently?"*

---

## 📂 Repository Structure

```
📦 Data-Driven-Investigation-into-Airline-Satisfaction
├── 📓 GH1044372_M512A_Data_Visualisation_Communications.html   # Full analysis notebook
├── 📁 insights/
│   ├── insight1.png        # Economy Class satisfaction breakdown
│   ├── insight4.png        # The 20-Minute Delay Rule
│   ├── insight9.png        # Seat Comfort vs Food & Wi-Fi
│   └── same_seat.png       # Same Seat, Different Expectations
└── 📄 README.md
```

---

## 🗂️ Dataset

| Attribute | Detail |
|---|---|
| **Source** | [Airline Passenger Satisfaction — Kaggle](https://www.kaggle.com/) |
| **Rows** | 25,976 passengers |
| **Features** | 25 variables (demographics, service ratings, delays, satisfaction) |
| **Target Variable** | `satisfaction` — Satisfied / Neutral or Dissatisfied |

---

## 🔍 Key Insights

### 📊 Insight 1 — Economy Class Is Driving the Crisis
> *Just 43% of passengers are satisfied — and Economy Class is almost entirely responsible.*

Economy class passengers report dramatically lower satisfaction across all service dimensions. The airline's largest passenger segment is also its most dissatisfied — a structural revenue risk that cannot be ignored.

![Insight 1 – Economy Class Satisfaction](https://github.com/OmPatil2806/Data-Driven-Investigation-into-Airline-Satisfaction/blob/main/insights/insight1.png?raw=true)

---

### ⏱️ Insight 2 — The 20-Minute Rule: Passengers Forgive Short Delays
> *Passengers tolerate delays under 20 minutes — but every minute beyond that costs the airline in satisfaction scores.*

The data reveals a clear inflection point at the 20-minute delay threshold. Below it, passengers remain largely forgiving. Beyond it, satisfaction drops sharply and consistently, making on-time performance a high-ROI operational target.

![Insight 2 – The 20-Minute Delay Rule](https://github.com/OmPatil2806/Data-Driven-Investigation-into-Airline-Satisfaction/blob/main/insights/insight4.png?raw=true)

---

### 💺 Insight 3 — Seat Comfort & Legroom Beat Food and Wi-Fi
> *The airline is investing in the wrong upgrades.*

When mapped against satisfaction outcomes, **seat comfort and legroom** outperform food quality and in-flight Wi-Fi as satisfaction drivers — yet these physical comforts receive less investment attention. Fix the seat, and you move the needle.

![Insight 3 – Seat Comfort vs Food & Wi-Fi](https://github.com/OmPatil2806/Data-Driven-Investigation-into-Airline-Satisfaction/blob/main/insights/insight9.png?raw=true)

---

### 🪑 Insight 4 — Same Seat, Different Expectations
> *Leisure travellers in Business Class are the most disappointed — paying a premium and feeling cheated.*

The same physical seat generates vastly different satisfaction outcomes depending on the passenger's travel purpose. Business travellers and leisure travellers carry entirely different expectations — and the airline's current service model serves neither segment fully.

![Insight 4 – Same Seat, Different Expectations](https://github.com/OmPatil2806/Data-Driven-Investigation-into-Airline-Satisfaction/blob/main/insights/same_seat.png?raw=true)

---

## 📋 Additional Insights Covered in the Report

| # | Insight |
|---|---|
| 5 | Leisure travellers in Business Class are the most disappointed |
| 6 | Seat comfort & legroom outperform food and Wi-Fi as satisfaction drivers |
| 7 | High ratings ≠ high impact — the services passengers rate highest matter least |
| 8 | The premium gap is closing — Business Class pays more but feels less |
| 9 | Fix seat comfort and you lift three service scores simultaneously |

---

## 🎯 Business Recommendations

Based on the analysis, three high-impact investments are prioritised:

1. **🛜 Repair Economy Wi-Fi** — Digital connectivity is a necessity for younger loyal travellers, not a luxury. Failing here is a future revenue crisis.
2. **⏰ Reduce Delays Below 20 Minutes** — The 20-minute threshold is a clear, measurable operational target tied directly to satisfaction scores.
3. **🪑 Upgrade Economy Seating** — Physical comfort is the strongest driver of satisfaction and the most underleveraged opportunity in the current product.

---

## 🛠️ Technical Stack

| Tool | Purpose |
|---|---|
| `pandas` / `numpy` | Data loading, cleaning, preprocessing |
| `matplotlib` / `seaborn` | Static visualisations |
| `plotly` | Interactive charts |
| `Jupyter Notebook` | Explanatory narrative structure |

**Design philosophy:** Charts follow principles from [datavizproject.com](https://datavizproject.com) — no chart junk, single highlight colour with grey context, simplified axes, and clarity over complexity.

---

## ⚠️ Limitations

- **Self-selection bias** — Survey respondents may not represent all passengers
- **Cross-sectional data** — No longitudinal tracking of individual passenger journeys
- **No financial data** — Satisfaction impact on revenue cannot be directly quantified

---

## 🔭 Future Work

- [ ] Predictive satisfaction model (ML classifier)
- [ ] Longitudinal data integration
- [ ] NPS score integration
- [ ] Financial impact modelling per satisfaction driver
- [ ] Segmented dashboards per passenger type

---

## 📄 Report Access

The full explanatory analysis notebook is available here:  
📓 [`airline_satisfaction_analysis.ipynb`](https://github.com/OmPatil2806/Data-Driven-Investigation-into-Airline-Satisfaction/blob/main/airline_satisfaction_analysis.ipynb)

---

## 👤 Author

**Om Dipak Patil**  
GH Number: GH1044372  
Module: M512A Data Visualisation & Communications  

---

*"The evidence is undeniable. Decision-making is now the responsibility of the leadership board."*
