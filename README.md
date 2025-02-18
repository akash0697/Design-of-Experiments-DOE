# Design-of-Experiments-DOE
This repository contains a Design of Experiments (DOE) project conducted as part of Business Analytics(SCM 517). The objective was to design and optimize a Lego race car using statistical experiments to maximize the distance traveled. The project follows a structured approach, leveraging Minitab for data analysis and factorial design techniques.

## Repository Contents
- **Legos.pdf** – Project guidelines, constraints, and Bill of Materials (BOM).
- **Lego DOE 313.pptx** – Presentation with the experimental setup, analysis, and results.
- **Anova Minitab.mpx** – Minitab analysis file for statistical modeling.

## Project Objective
- Apply **Design of Experiments (DOE)** principles to optimize a Lego race car.
- Identify the most significant design factors influencing performance.
- Use statistical modeling (**ANOVA, regression**) to analyze experimental results.
- Develop a **cost-performance trade-off analysis** based on BOM.

## Experimental Setup
- **Response Variable (Y):** Distance traveled by the Lego car.
- **Factors Chosen:**
  - **Tire Size (A)** – Affects friction and rolling resistance.
  - **Wind Screen Size (B)** – Influences air resistance.
  - **Axle Length (C)** – Affects structural stability.
  - **Car Slant (D)** – Alters center of gravity.
- **Design Approach:**
  - Full Factorial DOE (**k=4, n=2**)
  - Randomization of Trials
  - Controlled Environment (**No wind, fixed ramp angle**)

## Key Findings
- **Tire size (A)** had the highest impact on distance traveled.
- **Small windscreen and slanted design** reduced drag and improved efficiency.
- **Interaction effects** were significant, especially between **wheel size & slant**.
- **Final optimized model:** Large tires, small windscreen, slanted design, small axle.

## Data Analysis & Model Validation
- **R-squared:** 99.13% – Strong predictive capability.
- **Residuals Analysis:** Normally distributed, ensuring model validity.
- **Cost Analysis:** Best-performing model cost **₹13,200** while maximizing efficiency.

## Final Recommendations
- Use **larger wheels & a smaller windscreen** for optimal distance.
- Consider **trade-offs between cost and performance** in future designs.
- Further testing with additional factors (e.g., surface material) could refine results.

## How to Use This Repository
1. Read **Legos.pdf** for project guidelines and BOM details.
2. Review **Lego DOE 313.pptx** for experimental insights and results.
3. Explore **Anova Minitab.mpx** to analyze statistical models and validate findings.

## License
This project is shared for **educational and research purposes.**

