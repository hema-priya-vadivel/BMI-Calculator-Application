# 🧮 BMI Calculator

A simple and elegant **Java Swing desktop application** that calculates your **Body Mass Index (BMI)** based on your height (in feet and inches) and weight (in kilograms). This tool also categorizes your BMI result (e.g., underweight, normal, overweight or obese).

## 🔧 Features

- Input height in **feet** and **inches**
- Input weight in **kilograms**
- Calculates **BMI** instantly on button click
- Displays a clear health message based on BMI range
- Includes **Clear** and **Exit** buttons
- Easy-to-use GUI built with Java Swing

## 📐 BMI Formula

**BMI = weight (kg) / [height (m)]²**

- Height is entered in **feet and inches**.
- The app converts it to meters using the formula:

  **Height (m)** = (feet × 0.3048) + (inches × 0.0254)

**🟢 Example:**  
---

### 🧪 Sample Input / Output 01:  5 feet 5 inches, 60 kg

- Height in meters = (5 × 0.3048) + (5 × 0.0254) = **1.651 m**
- BMI = 60 / (1.651²) ≈ **22.0** → ✅ *Normal*

---

### 🧪 Sample Input / Output 02: 5 feet 3 inches, 54 kg

- Height in meters = (5 × 0.3048) + (3 × 0.0254) = **1.6002 m**
- BMI = 54 / (1.6002²) ≈ **21.1** → ✅ *Normal*

---

## 💬 BMI Result Categories

- Below 18.5 – Underweight

- 18.5 to 24.9 – Normal

- 25.0 to 29.9 – Overweight

- 30.0 and above – Obese

## 🖼️ BMI Calculator GUI

<br>
<img src="https://github.com/hema-priya-vadivel/BMI-Calculator-Application/blob/master/assets/image-1.png" alt="BMI Calculator GUI - 1" width="400">
<br>
<img src="https://github.com/hema-priya-vadivel/BMI-Calculator-Application/blob/master/assets/image-2.png" alt="BMI Calculator GUI - 2" width="400">
<br>

## 🚀 How to Use

### ✅ Option 1: Clone and Run the Source Code

1. Clone the repository:
   
    ```bash
    git clone https://github.com/hema-priya-vadivel/BMI-Calculator-Application.git
    
2. Open the project in your Java IDE (e.g., IntelliJ IDEA, Eclipse, NetBeans).

3. Navigate to the source file and compile and run bmi.java.

4. Once the application window opens:

   - Enter your **height** in **feet** and **inches**
   - Enter your **weight** in **kilograms**
   - Click the **Calculate** button to view your **BMI** and see whether you are **Underweight**, **Normal**, **Overweight**, or **Obese**
   - Click **Clear** to reset all fields
   - Click **Exit** to close the application

### ✅ Option 2: Download & Run the Application

- [Download for Mac (.dmg)](https://github.com/hema-priya-vadivel/BMI-Calculator-Application/blob/master/releases/download/BMICalculator-macOS-1.0.dmg)



