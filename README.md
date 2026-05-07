# AI Poverty Social Good Project

## 1. The Problem and Who It Affects

Poverty in the Bay Area affects low-income families and even full-time workers like Jennifer, whose government job does not cover the region’s high cost of living. Our project uses AI—specifically natural language processing and recommendation systems—because it can quickly interpret a user’s situation and match it to relevant support programs more efficiently than manual searches. The workflow is simple: users input basic information (income, location, needs), the AI analyzes eligibility and available services, and it outputs personalized recommendations such as nearby food banks or rental aid; the user then decides which resources to act on.

One failure case occurs when the AI misclassifies eligibility—for example, suggesting a housing program the user does not qualify for (as seen in testing outputs where income thresholds were misread). The oversight decision is to require a human-in-the-loop verification step for high-impact recommendations, with the tradeoff of slower response time. The key improvement made is adding clearer eligibility explanations alongside each recommendation, which increases user understanding but may make the interface slightly more complex.
