# AI Poverty Social Good Project

## 1. The Problem and Who It Affects
Poverty in the Bay Area is driven by a significant wealth gap and extremely high cost of living, which makes it difficult for many residents to afford basic needs. This disproportionately affects low- to moderate-income workers like Jennifer, an African American receptionist at San Jose City Hall. Despite having a stable job, she struggles with high housing costs, limited savings, and restricted access to education and career advancement opportunities. These challenges are further intensified by systemic and racial inequalities that limit economic mobility and reinforce long-standing disparities

## 2. The AI Capability Used And Why It Fits
The project uses AI capabilities such as natural language processing (NLP) and recommendation systems. NLP allows the system to understand user inputs about financial situations and personal needs, while recommendation systems match users with relevant resources. This fits well because poverty-related challenges are complex and individualized, and AI can quickly analyze multiple factors (income, location, barriers) to provide tailored support more efficiently than manual searches.

## 3. The Workflow — What Goes In, What The AI Does, What Comes Out, And Who Acts On It
The system begins with user inputs such as financial information, location, and available resource data. The AI then processes this information to identify needs, barriers (e.g., housing affordability, education access), and eligibility for support programs. The output includes personalized recommendations like housing assistance, budgeting strategies, or job opportunities. Finally, the user acts on these recommendations by applying for programs or accessing services.
Screenshots from the file (pages 2–3) show examples of this workflow: a prompt being input into the system, the AI-generated response summarizing the issue, and a structured output describing Jennifer’s situation and challenges.

## 4. One Failure Case Tied To A Lab Output
A key failure case appears in the lab outputs where the AI produces overly long and inconsistent responses across multiple runs (e.g., “Run 1, Run 2, Run 3” on pages 7–12). The variation in format and level of detail makes it difficult for users to extract clear, actionable information. This is considered a failure because the system is intended to simplify access to resources, not overwhelm users with excessive or inconsistent outputs.
![description](<img width="996" height="283" alt="Screenshot 2026-05-06 at 7 14 07 PM" src="https://github.com/user-attachments/assets/52dcf804-bbcd-426a-bf06-34a649b81ecd" />)

## 5. The Oversight Decision And The One Change, Each With Its Tradeoff Stated
The oversight decision is to include human review or stricter system constraints for high-impact outputs to ensure clarity, accuracy, and fairness. The tradeoff is that adding oversight may slow down response time and reduce scalability. One key change is refining prompts and system instructions to require shorter, more structured responses. This improves usability and consistency for users, but the tradeoff is that it may reduce the depth and nuance of the information provided.
