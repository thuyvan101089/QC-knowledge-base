# 🧠 Chapter 1: Fundamentals of Testing

---

# 1.1 What is Testing?

## 1.1.1 Test Objectives

### 📌 Definition (ISTQB)
The objectives of testing include:
- Evaluating work products
- Verifying requirements
- Validating user needs
- Building confidence in quality
- Detecting defects
- Preventing defects

---

### 🧠 Explanation

Testing không chỉ để tìm bug mà còn:
- Ngăn ngừa lỗi từ sớm  
- Giúp stakeholder quyết định release  

---

### 🧪 Example

Requirement review:
- Phát hiện thiếu case → defect prevention  

---

### 🎯 Exam Focus

👉 Hay hỏi:
- mục tiêu của testing là gì  
- phân biệt detect vs prevent  

---

## 1.1.2 Test Activities and Tasks

### 📌 Definition (ISTQB)
Testing activities include:

- Test planning  
- Test monitoring and control  
- Test analysis  
- Test design  
- Test implementation  
- Test execution  
- Test completion  

---

### 🧠 Explanation

Flow chuẩn:

1. Planning → define scope  
2. Analysis → hiểu requirement  
3. Design → viết test case  
4. Implementation → chuẩn bị test data  
5. Execution → chạy test  
6. Completion → report  

---

### 🧪 Example

Login feature:
- Analysis → đọc spec  
- Design → viết test case  
- Execution → test login  

---

### 🎯 Exam Focus

👉 Nhớ thứ tự activities (rất hay ra thi)

---

## 1.1.3 Test Basis and Testware

### 📌 Definition

- Test basis: tài liệu dùng để viết test  
- Testware: sản phẩm được tạo ra trong testing  

---

### 🧠 Explanation

- Test basis:
  - Requirement  
  - Design doc  

- Testware:
  - Test case  
  - Test script  
  - Test report  

---

### 🧪 Example

Requirement → viết test case → tạo report  

---

### 🎯 Exam Focus

👉 Phân biệt:
- Test basis vs Testware  

---

## 1.1.4 Traceability between Test Basis and Testware

### 📌 Definition
Traceability ensures coverage between requirements and test cases.

---

### 🧠 Explanation

- Requirement phải có test case  
- Test case phải trace ngược lại requirement  

---

### 🧪 Example

Requirement: Login  
→ Test case: login success / fail  

---

### 🎯 Exam Focus

👉 Traceability = coverage  

---

# 1.2 Why is Testing Necessary?

## 1.2.1 Contribution of Testing to Success

### 📌 Definition
Testing contributes to product quality and project success.

---

### 🧠 Explanation

- Detect defects  
- Reduce risk  
- Improve quality  

---

### 🧪 Example

Fix bug before release → tránh lỗi production  

---

## 1.2.2 Quality Assurance and Testing

### 📌 Definition

- QA = process-focused  
- Testing = product-focused  

---

### 🧠 Explanation

- QA → cải tiến quy trình  
- Testing → tìm defect  

---

### 🎯 Exam Focus

👉 QA ≠ Testing (hay ra thi)

---

## 1.2.3 Errors, Defects, Failures

### 📌 Definition

- Error → human mistake  
- Defect → bug in system  
- Failure → incorrect behavior  

---

### 🧠 Flow

Error → Defect → Failure  

---

### 🧪 Example

Wrong logic → defect → crash  

---

## 1.2.4 Root Causes and Effects of Defects

### 📌 Definition
Defects originate from root causes.

---

### 🧠 Explanation

Root causes:
- Poor requirement  
- Bad design  
- Coding mistake  

---

### 🧪 Example

Requirement unclear → dev hiểu sai → bug  

---

# 1.3 Testing Principles

(giữ nguyên 7 principles nhưng gắn đúng section)

---

# 🧠 MINDMAP (STRUCTURE-BASED)

```mermaid
mindmap
  root((Chapter 1))
    1.1 Testing
      Objectives
      Activities
      Test basis
      Traceability
    1.2 Why Testing
      Quality
      QA vs Testing
      Error flow
      Root cause
    1.3 Principles
      7 principles
