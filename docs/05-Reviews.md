## 🔹 What are Reviews?

- A technical assessment of a work product created during the software engineering process  
- A meeting conducted by technical people  
- A software quality assurance mechanism  
- A training ground  

### ❌ What they are not!
- A project summary or progress assessment  
- A meeting intended solely to impart information  
- A mechanism for political or personal reprisal  

---

## 🔹 Cost Impact of Software Defects

- **Error**: a quality problem found before the software is released to end users  
- **Defect**: a quality problem found after the software is released  

- Design activities introduce 50 to 65% of all software defects  
- Review activities are 75% effective in uncovering design flaws  
- The sooner a defect is found, the cheaper it is to fix  

---

## 🔹 Defect Amplification and Removal

- **Defect amplification**: a defect introduced early and not detected becomes multiple errors later  
- **Defect propagation**: the impact of an undiscovered defect on future development or product behavior  
- **Technical debt**: costs incurred by failing to find and fix defects early or failing to update documentation  

---

## 🔹 Review Metrics (1)

- **Preparation effort (Ep)**: effort required before the review meeting  
- **Assessment effort (Ea)**: effort during the review meeting  
- **Rework effort (Er)**: effort to correct errors found  
- **Work product size (WPS)**: size of the reviewed product  
- **Minor errors (Err_minor)**  
- **Major errors (Err_major)**  

---

## 🔹 Review Metrics (2)

- **Total errors (Err_tot)** = Err_minor + Err_major  
- **Error density** = Err_tot ÷ WPS  

---

## 🔹 Metrics Example 1

- Average defect density = 0.68 errors per page  
- Document size = 40 pages  
- Estimated errors ≈ 27 errors  

- If only 9 errors are found:
  - Either the requirements model is very good  
  - Or the review approach was not thorough enough  

---

## 🔹 Metrics Example 2

- Minor error correction effort = 4 person-hours  
- Major error correction effort = 18 person-hours  
- Minor errors occur about 6 times more frequently than major errors  

- Average effort per error ≈ 6 person-hours  

---

## 🔹 Metrics Example 3

- Requirements-related errors during testing require 45 person-hours  
- Errors during review require 6 person-hours  

- Effort saved per error = 39 person-hours  
- If 22 errors found → total saving = 858 person-hours  

---

## 🔹 Informal Reviews

**Benefits:**
- Immediate discovery of errors  
- Better work product quality  

**Types:**
- Desk check with a colleague  
- Casual meeting  
- Pair programming review  

---

## 🔹 Formal Technical Reviews (FTR)

**Objectives:**
- Uncover errors in function, logic, or implementation  
- Verify that software meets requirements  
- Ensure adherence to standards  
- Achieve uniform development  
- Make projects more manageable  

---

## 🔹 Review Meeting

- 3 to 5 people involved  
- Preparation ≤ 2 hours per person  
- Meeting duration < 2 hours  
- Focus on a specific work product  

---

## 🔹 Review Players

- **Producer**: develops the work product  
- **Review leader**: prepares and facilitates the review  
- **Reviewers**: examine the product  
- **Recorder**: records issues raised  

---

## 🔹 Review Outcome

- Accept without modification  
- Reject (requires correction and another review)  
- Accept provisionally (minor errors to be corrected)  

---

## 🔹 Review Reporting and Record Keeping

- Recorder creates a **review issues list**  
- A **summary report** answers:
  - What was reviewed?  
  - Who reviewed it?  
  - What were the findings and conclusions?  

- A follow-up procedure ensures corrections  

---

## 🔹 Review Guidelines

- Review the product, not the producer  
- Set and maintain an agenda  
- Limit debate and rebuttal  
- Identify problems without solving all of them  
- Take written notes  
- Limit participants  
- Require advance preparation  
- Use checklists  
- Allocate time and resources  
- Train reviewers  
- Review early reviews  

---

## 🔹 Postmortem Evaluations (PME)

- Determine what went right and what went wrong  
- Focus on:
  - Excellences (achievements and positive experiences)  
  - Challenges (problems and negative experiences)  

- Goal: extract lessons and improve processes  

---

## 🔹 Agile Reviews

- Sprint planning: review and prioritize user stories  
- Daily Scrum: informal review for alignment and defect detection  
- Sprint review: follows formal review guidelines  
- Sprint retrospective: acts as a postmortem  
