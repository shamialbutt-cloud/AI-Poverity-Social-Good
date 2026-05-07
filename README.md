# AI Poverty Social Good Project

## 1. The Problem and Who It Affects
Poverty in the Bay Area is driven by a significant wealth gap and extremely high cost of living, which makes it difficult for many residents to afford basic needs. This disproportionately affects low- to moderate-income workers like Jennifer, an African American receptionist at San Jose City Hall. Despite having a stable job, she struggles with high housing costs, limited savings, and restricted access to education and career advancement opportunities. These challenges are further intensified by systemic and racial inequalities that limit economic mobility and reinforce long-standing disparities

## 2. The AI Capability Used And Why It Fits
The project uses AI capabilities such as natural language processing (NLP) and recommendation systems. NLP allows the system to understand user inputs about financial situations and personal needs, while recommendation systems match users with relevant resources. This fits well because poverty-related challenges are complex and individualized, and AI can quickly analyze multiple factors (income, location, barriers) to provide tailored support more efficiently than manual searches.

## 3. The Workflow — What Goes In, What The AI Does, What Comes Out, And Who Acts On It
The system begins with user inputs such as financial information, location, and available resource data. The AI then processes this information to identify needs, barriers (e.g., housing affordability, education access), and eligibility for support programs. The output includes personalized recommendations like housing assistance, budgeting strategies, or job opportunities. Finally, the user acts on these recommendations by applying for programs or accessing services.
Screenshots from the file (pages 2–3) show examples of this workflow: a prompt being input into the system, the AI-generated response summarizing the issue, and a structured output describing Jennifer’s situation and challenges.

## Shamial's Outputs

Code 1:
<img width="986" height="453" alt="Screenshot 2026-05-06 at 7 25 22 PM" src="https://github.com/user-attachments/assets/d322aa8b-2d85-4f66-84c3-ed230d641965" />

Code 2:
<img width="988" height="552" alt="Screenshot 2026-05-06 at 7 25 44 PM" src="https://github.com/user-attachments/assets/e89a0b34-a4a4-4673-b5fd-8aed2503adec" />

Code 3:
<img width="981" height="544" alt="Screenshot 2026-05-06 at 7 26 06 PM" src="https://github.com/user-attachments/assets/edafb691-3aa1-4792-b346-9f6da9215d21" />
<img width="987" height="404" alt="Screenshot 2026-05-06 at 7 26 16 PM" src="https://github.com/user-attachments/assets/031e00ad-a73c-48b9-8f47-7e2b9b445862" />
<img width="987" height="317" alt="Screenshot 2026-05-06 at 7 26 38 PM" src="https://github.com/user-attachments/assets/2402ca51-4470-48d6-8b4e-e67cd11c4154" />
<img width="987" height="454" alt="Screenshot 2026-05-06 at 7 26 43 PM" src="https://github.com/user-attachments/assets/df442f40-d4d2-4d42-8774-398ac9cf7213" />
<img width="987" height="457" alt="Screenshot 2026-05-06 at 7 26 51 PM" src="https://github.com/user-attachments/assets/8e753e5e-8f34-44a5-9389-c5b7d0014cc6" />



## 4. One Failure Case Tied To A Lab Output
A key failure case appears in the lab outputs where the AI produces overly long and inconsistent responses across multiple runs (e.g., “Run 1, Run 2, Run 3” on pages 7–12). The variation in format and level of detail makes it difficult for users to extract clear, actionable information. This is considered a failure because the system is intended to simplify access to resources, not overwhelm users with excessive or inconsistent outputs.
Shamial's Failure:
<img width="996" height="283" alt="Screenshot 2026-05-06 at 7 14 07 PM" src="https://github.com/user-attachments/assets/6282db31-bf33-40cf-9e34-6c5f0ae730b3" />

## 5. The Oversight Decision And The One Change, Each With Its Tradeoff Stated
The oversight decision is to include human review or stricter system constraints for high-impact outputs to ensure clarity, accuracy, and fairness. The tradeoff is that adding oversight may slow down response time and reduce scalability. One key change is refining prompts and system instructions to require shorter, more structured responses. This improves usability and consistency for users, but the tradeoff is that it may reduce the depth and nuance of the information provided.
