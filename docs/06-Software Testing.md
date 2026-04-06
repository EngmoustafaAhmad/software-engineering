# Chapter 19 – Software Testing (Component Level)

## 🔹 Strategic Approach to Testing

- Conduct effective technical reviews to eliminate errors before testing  
- Testing begins at the component level and moves outward to system integration  
- Different techniques are used at different stages  
- Testing is done by developers and (for large projects) an independent test group  
- Testing and debugging are different activities  

---

## 🔹 Verification and Validation

- **Verification**: ensures software correctly implements a specific function  
  - “Are we building the product right?”  

- **Validation**: ensures software meets customer requirements  
  - “Are we building the right product?”  

---

## 🔹 Organizing for Testing

- Developers test individual components  
- Independent Test Group (ITG) is involved after architecture is complete  
- ITG removes bias of developers testing their own work  
- Developers and ITG collaborate throughout the project  

---

## 🔹 Testing the Big Picture

- **Unit Testing**: focuses on individual units (components, classes)  
- **Integration Testing**: focuses on design and architecture  
- **Validation Testing**: checks requirements against built software  
- **System Testing**: tests the complete system  

---

## 🔹 Criteria for Done

- Not done when time or money runs out  
- Statistical quality assurance uses test samples and metrics  
- Metrics and models help determine when testing is complete  

---

## 🔹 Test Planning

- Define requirements clearly before testing  
- State testing objectives  
- Understand users and create profiles  
- Develop rapid cycle testing plans  
- Build software that can test itself  
- Use technical reviews before testing  
- Review test strategy and test cases  
- Apply continuous improvement  

---

## 🔹 Test Recordkeeping

- Test cases include:
  - Description  
  - Requirement reference  
  - Expected output  
  - Pass/fail result  
  - Date executed  
  - Comments for failures  

---

## 🔹 Role of Scaffolding

- Testing requires a framework  
- **Driver**: main program that runs test cases  
- **Stub**: dummy module replacing called components  

---

## 🔹 Cost Effective Testing

- Exhaustive testing is not practical  
- Testing cannot prove correctness  
- Focus on critical or error-prone modules  

---

## 🔹 Test Case Design

Test cases should cover:
- Module interface  
- Local data structures  
- Independent control paths  
- Boundary conditions  
- Error-handling paths  

---

## 🔹 Error Handling

Test for:
- Incorrect error descriptions  
- Mismatched error messages  
- System interruptions before handling  
- Incorrect exception processing  
- Insufficient error information  

---

## 🔹 Traceability

- Each test case must map to requirements  
- Includes functional and nonfunctional requirements  
- Regression testing retests affected components  
- Failures often due to missing traceability or incomplete coverage  

---

## 🔹 White Box Testing

Ensures:
- All independent paths are executed  
- All logical decisions are tested (true/false)  
- Loops tested at boundaries  
- Internal data structures validated  

---

## 🔹 Basis Path Testing

- Cyclomatic Complexity:
  - V(G) = E − N + 2  
  - V(G) = P + 1  

- Determines number of independent paths  
- Test cases must execute all independent paths  

---

## 🔹 Control Structure Testing

- **Condition testing**: tests logical conditions  
- **Data flow testing**: tests variable usage  
- **Loop testing**: tests loop constructs  

---

## 🔹 Loop Testing

### Simple Loops:
- Skip loop  
- One pass  
- Two passes  
- m passes (m < n)  
- n−1, n, n+1 passes  

### Nested Loops:
- Start from innermost loop  
- Keep others at minimum values  
- Expand testing outward  

---

## 🔹 Black Box Testing

Finds errors in:
- Missing or incorrect functions  
- Interface errors  
- Data structure errors  
- Performance issues  
- Initialization/termination errors  

- Applied in later testing stages  

---

## 🔹 Black Box Questions

- How to test functionality?  
- How to test behavior and performance?  
- What inputs create good test cases?  
- Sensitivity to input values?  
- Boundary isolation?  
- Data rate and volume handling?  

---

## 🔹 Interface Testing

- Ensures correct data input/output format and order  
- Uses drivers and stubs  
- May include debugging code  

---

## 🔹 Object-Oriented Testing (OOT)

- Expand testing to include analysis and design  
- Change unit and integration testing strategies  
- Design test cases for OO characteristics  

---

## 🔹 Boundary Value Analysis (BVA)

- Test values at boundaries:
  - a, b, just below and above  
- Test min and max values  
- Apply to inputs and outputs  
- Test data structure limits  

---

## 🔹 OOT – Class Testing

- Equivalent to unit testing  
- Focus on class operations and state behavior  
- Use operation sequences and permutations  

---

## 🔹 OOT – Behavior Testing

- Use state diagrams  
- Test transitions between states  
- Ensure full coverage of behavior  

---
