# 🧠 Chapter 1: Fundamentals of Testing

---

# 🎯 1. What is Testing?

## 📌 Definition
Testing is a set of activities to detect defects and ensure the system meets requirements and user needs.

## 🧠 Explanation
Testing is not just executing test cases. It includes:
- Reviewing requirements  
- Designing test cases  
- Executing tests  
- Reporting defects  

👉 Goal: **Reduce risk, not eliminate all bugs**

## 🧪 Example
Login feature:
- Valid input → success  
- Invalid password → error  

---

# ❓ 2. Why is Testing Necessary?

## 📌 Definition
Testing helps reduce risk and improve software quality.

## 🧠 Explanation
- Humans make mistakes  
- Systems are complex  
- Failures can cause:
  - Financial loss  
  - Security issues  

## 🧪 Example
Bank app calculates wrong balance → serious issue  

---

# 🔥 3. 7 Principles of Testing

## 1. Testing shows presence of defects
→ Cannot prove no bugs exist  

## 2. Exhaustive testing is impossible
→ Cannot test all combinations  

## 3. Early testing
→ Start early to save cost  

## 4. Defect clustering
→ Bugs concentrate in few modules  

## 5. Pesticide paradox
→ Repeating tests finds fewer bugs  

## 6. Context dependent
→ Different systems → different testing  

## 7. Absence of errors fallacy
→ No bugs ≠ good product  

---

# 🔄 4. Verification vs Validation

- Verification → Build the product right  
- Validation → Build the right product  

## 🧪 Example
- Verification → follow spec  
- Validation → user finds it useful  

---

# ⚠️ 5. Error – Defect – Failure

- Error → human mistake  
- Defect → bug in code  
- Failure → system behaves incorrectly  

👉 Flow:
Error → Defect → Failure  

---

# 🔄 6. Testing Process

1. Planning  
2. Analysis  
3. Design  
4. Execution  
5. Closure  

---

# 🧠 MINDMAP (IMPORTANT)

```mermaid
mindmap
  root((Testing Fundamentals))
    Testing
      Definition
      Detect defects
      Ensure quality
    Purpose
      Reduce risk
      Increase confidence
    Principles
      Presence of defects
      Exhaustive impossible
      Early testing
      Defect clustering
      Pesticide paradox
      Context dependent
      Absence fallacy
    V&V
      Verification
      Validation
    Error Flow
      Error
      Defect
      Failure
    Process
      Planning
      Analysis
      Design
      Execution
      Closure
