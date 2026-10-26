# Day 4: Static vs. Dynamic Testing & The 3 Box Methods

## 1. Static vs. Dynamic Testing
* **Static Testing (Evaluation without Execution):** Analyzing software artifacts (requirements, design, source code) without executing the code. Focuses on reviews, walkthroughs, inspections, and analysis.
  * *Goal:* Catch errors early on paper before they ever reach the code.
  * *Analogy:* Proofreading a recipe for spelling mistakes.
* **Dynamic Testing (Validation with Execution):** Evaluating the actual system by compiling and running the code.
  * *Goal:* Identifying runtime errors, crashes, and functional bugs under realistic conditions.
  * *Analogy:* Baking the recipe and eating it to ensure it tastes right.

## 2. Testing Techniques (Based on Inner Code Visibility)

### A. Black Box Testing (Behavioral)
* **Definition:** Testing without any knowledge or visibility of the internal code, design, or architecture.
* **Focus:** Input vs. Output. Focuses entirely on requirements, user journeys, and expected behavior.
* **Who does it:** Manual QA Testers, Business Analysts, and Clients. No coding experience needed.
* **Application:** UI Testing, Functional testing, Acceptance Testing.

### B. White Box Testing (Structural)
* **Definition:** Testing with complete visibility into the internal logic, database structures, and source code.
* **Focus:** Logic and coverage. Tests specific paths, loops, branches, and code security.
* **Who does it:** Developers and SDETs. Requires coding proficiency.
* **Application:** Unit Testing, Integration Testing, Statement & Branch coverage.

### C. Gray Box Testing (Hybrid)
* **Definition:** Testing with limited/partial knowledge of internal system design.
* **Focus:** Combining external usability with high-level architectural knowledge (databases, API contracts).
* **Who does it:** QA Automation Engineers, Integration Testers.
* **Application:** API Testing, Web Services, and Database validations.
