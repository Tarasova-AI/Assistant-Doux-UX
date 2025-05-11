# The Interactive Journey: Logic, Safeguards, and Stress-Aware Design
*How the prototype guides parents with clarity and care*

---

### 🔄 Overall flow logic

The prototype uses a conditional logic flow (if/then) designed in Tally. It walks users step-by-step while protecting against drop-off, stress-induced error, and cognitive overload.

---

### 🟢 Q1 – Open-text description

**Prompt:** "Please describe what you observe."
- ➕ *Required field (min. 30 characters)*
- ❗ Prevents incomplete or rushed inputs

---

### 🔵 Q1b – Confirmation “Continue”

- ➕ Acts as conscious validation to move forward
- 🛑 Prevents “click-through” without engagement

---

### 🟠 Q2 – Symptom checklist

**Prompt:** "Select any symptoms you observe"
- 🔘 Checkboxes, multiple selections allowed
- ➕ *Not required* — user may skip

---

### 🟣 Q2b – Second validation “Continue”

- ➕ Confirms prior step
- ➕ Triggers logic branch if no symptoms are selected

---

### 🔴 Q3 – Control question: "None of these symptoms?"

- ➕ Helps catch missed inputs due to stress or uncertainty
- 🧠 Encourages re-evaluation before dismissal

---

### 🔐 UX Protections

| Problem                                      | UX Solution                                                         |
|---------------------------------------------|----------------------------------------------------------------------|
| Empty or vague input                        | Required 30-character minimum on Q1                                 |
| Click-through without reading               | Dual “Continue” confirmations to slow and verify user input         |
| Unintended skip of symptom list             | Q3 control question activates if Q2 left blank                      |
| Confusion under stress                      | Short sentences, clear wording, no medical jargon                   |
| Multilingual access barriers                | Full content in FR / EN / RU, adapted for cultural understanding   |

---

### 💡 Why it works

- Prevents impulsive skipping
- Detects hesitation without punishing the user
- Uses language that supports, not diagnoses
- Designed for use in waiting rooms, at home, or on mobile — no login, no tracking

---
