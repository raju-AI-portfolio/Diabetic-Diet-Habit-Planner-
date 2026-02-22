# 🩺 Diabetic Diet & Habit Planner  
### AI-Powered No-Code Health Assistant using AWS PartyRock

---

## 📌 Project Overview

**Diabetic Diet & Habit Planner** is a no-code Generative AI application built using **AWS PartyRock**.  

The app analyzes a doctor’s prescription and automatically generates:

- ✅ A 7-Day Customized Meal Plan  
- ✅ Culturally Appropriate Food Habits  
- ✅ Lifestyle Recommendations (Exercise, Sleep, Hydration, Stress)  
- ✅ Structured Diet Plan Guidance  

The goal is to help **Type 2 Diabetes patients** convert medical prescriptions into actionable diet and lifestyle strategies — without requiring manual consultation.

---

## 🎯 Objective

To build a **no-code AI-powered healthcare assistant** that:

- Reads and understands clinical prescriptions  
- Extracts key medical and lifestyle instructions  
- Converts them into structured weekly meal plans  
- Provides sustainable dietary habits  
- Suggests lifestyle improvements for diabetes management  

---

## 🚨 Problem Statement

Patients with Type 2 Diabetes often:

- Struggle to interpret medical prescriptions  
- Receive generic diet advice from online sources  
- Lack access to affordable diet consultation  
- Face difficulty converting prescriptions into daily meal routines  

This project solves the problem using AI-powered automation.

---

## 🛠️ Tech Stack

- **Platform:** AWS PartyRock  
- **Model Used:** Claude 3.5 Sonnet v2  
- **Model Parameters:**
  - Temperature: 0.5  
  - Top-p: 0.4  
- **Deployment:** Browser-based (No-Code Application)  

---

## 🧠 How the Application Works

```
User Pastes Doctor Prescription
            ↓
Claude 3.5 Sonnet Model Processes Input
            ↓
AI Generates Structured Outputs:
    • Diet Plan
    • 7-Day Meal Plan
    • Food Habits
    • Lifestyle Advice
```

The app uses **LLM chaining inside PartyRock** by connecting the prescription input to multiple AI-generated output widgets.

---

# 🚀 Implementation Steps

---

## 🔹 Step 1: Launch PartyRock Studio

1. Visit:
   https://partyrock.aws/apps

2. Click:
   Generate App

3. Select:
   Build Manually

---

## 🔹 Step 2: Set App Title

- Click edit icon
- Name the app:

```
Diabetic Diet & Habit Planner
```

- Save and return to canvas

---

## 🔹 Step 3: Add Text Input Widget

Add a Text Widget:

- Title:
  ```
  Doctor Prescription Input
  ```

- Instruction:
  ```
  Paste your prescription here
  ```

This widget accepts prescription details as input.

---

## 🔹 Step 4: Add AI Output Widgets

Create **4 Generated Text Widgets**:

### 1️⃣ Diet Plan Generator
Prompt Objective:
Generate a structured diabetic diet plan from prescription.

---

### 2️⃣ 7-Day Meal Plan
Prompt Objective:
Generate a weekly culturally appropriate diabetic meal plan.

---

### 3️⃣ Food Habits
Prompt Objective:
Suggest sustainable food habits for long-term diabetes management.

---

### 4️⃣ Lifestyle Advice
Prompt Objective:
Provide recommendations for:
- Exercise
- Sleep
- Hydration
- Stress management
- Glucose monitoring

---

### ⚙️ Advanced Settings for Each Widget

```
Model: Claude 3.5 Sonnet v2
Temperature: 0.5
Top-p: 0.4
```

Use `@Prescription Input` to link the input widget.

---

## 🧪 Sample Input

```
Diagnosis: Type 2 Diabetes Mellitus (T2DM)

Tab. Metformin 500 mg – twice daily
Tab. Glimepiride 1 mg – before breakfast
Low-carb diabetic diet
Daily brisk walk 30–45 minutes
Monitor blood glucose regularly
Avoid sugary foods and alcohol
```

---

## 📤 Sample Output Structure

The app generates 4 structured sections:

```
A. Diet Plan Generator Response
B. 7-Day Meal Plan
C. Food Habits Recommendations
D. Lifestyle Advice
```

---

## 🌍 Business & Social Impact

- Promotes preventive healthcare  
- Reduces dependency on manual diet consultations  
- Improves diabetes self-management  
- Makes AI healthcare accessible without coding  
- Demonstrates real-world GenAI healthcare use case  

---

## 🔮 Future Enhancements

- Add calorie tracking integration  
- Include BMI & weight-based customization  
- Multi-language support  
- Integration with glucose monitoring apps  
- PDF download option for meal plan  
- Support for other chronic diseases  

---

## 🧠 Key Learning Outcomes

- Building No-Code GenAI applications  
- Prompt Engineering using Claude 3.5  
- Healthcare-focused AI solution design  
- Widget chaining in AWS PartyRock  
- Real-world clinical-to-actionable AI transformation  

---

## ⚠️ Disclaimer

This application is built for **educational purposes only**.  
It does not replace professional medical advice.  
Always consult a licensed healthcare professional before making dietary or medical decisions.

---

## 📜 License

Educational Use Only.
