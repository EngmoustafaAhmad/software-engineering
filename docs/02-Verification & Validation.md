# 📘 Software Engineering - Verification & Validation

## 🔹 What is Verification and Validation?

### ✅ Verification
👉 **"Are we building the product right?"**

- Ensures the software follows the **specifications**
- Checks if code and design match the requirements

📌 Example:  
If the requirement is to build a program that adds two numbers  
→ Verification ensures the code actually performs the addition correctly.

---

### ✅ Validation
👉 **"Are we building the right product?"**

- Ensures the software meets **real user needs**

📌 Example:  
The user needs a full calculator  
But you only built an addition program  
→ Validation fails ❌

---

## 🔹 Key Differences

| Verification | Validation |
|-------------|-----------|
| Building the product right | Building the right product |
| Focuses on code and design | Focuses on user needs |
| Usually before execution | Usually after execution |

---

## 🔹 V&V Process

📌 A continuous process applied throughout all development stages.

### 🎯 Objectives:
- Detect defects
- Ensure the system is useful and usable

⚠️ Note:  
Software does NOT have to be 100% error-free  
It must be **good enough** for its intended use.

---

## 🔹 Types of Verification

### 1. Static Verification
👉 Without running the program

- Code reviews  
- Design reviews  
- Software inspections  

---

### 2. Dynamic Verification
👉 By executing the program

- Testing  

---

## 🔹 Software Testing

> Testing shows the presence of errors ❗  
> It does NOT prove their absence

---

### Types of Testing

#### 1. Defect Testing
- Goal: Find errors  
- ✔️ Successful test = finds a defect  

#### 2. Validation Testing
- Goal: Ensure requirements are met  
- ✔️ Successful test = confirms correct implementation  

---

## 🔹 Testing vs Debugging

| Testing | Debugging |
|--------|----------|
| Finds errors | Fixes errors |
| Evaluation phase | Repair phase |

---

## 🔹 Software Inspections

👉 A team reviews code or design to find defects

### Advantages:
- No execution required  
- Can be done early  

---

## 🔹 Inspection vs Testing

| Inspection | Testing |
|-----------|--------|
| No execution required | Requires execution |
| Checks specifications | Checks actual behavior |
| Cannot test performance | Can test performance |

✔️ They complement each other

---

## 🔹 V&V Planning

📌 Start early to:
- Save time  
- Reduce errors  

---

## 🔹 Software Test Plan

Includes:
- Test items  
- Schedule  
- Tools  
- Result recording  

---

## 🔹 Inspection Process

1. System overview  
2. Code distribution  
3. Individual review  
4. Record errors  
5. Fix errors  
6. Re-inspection (if needed)  

---

## 🔹 Important Notes

- Inspections are expensive  
- Very effective for early defect detection  
- Require management support  

---

## 🔥 Summary

- **Verification** → Are we building the product right?  
- **Validation** → Are we building the right product?  

To ensure high quality:
- Use **Inspection (static)**  
- Use **Testing (dynamic)**  
