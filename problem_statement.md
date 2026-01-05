**Business Problem and Context**

Home Credit’s business model is built around providing unsecured consumer credit to people who are underserved by traditional banks. Across the markets where Home Credit operates, a large share of adults have little or no formal credit history, and many do not regularly use formal financial services. This structural reality defines Home Credit’s growth opportunity, but it also creates a fundamental risk management challenge.

Because many applicants are credit-invisible or thin-file, traditional credit scoring methods that depend on bureau data and banking history provide limited predictive power. As a result, Home Credit must make lending decisions with incomplete information about a borrower’s likelihood of repayment. This uncertainty is compounded by the fact that Home Credit operates across diverse countries and products. Loan sizes, customer profiles, and repayment behavior vary significantly by market and product type, and the research shows that there is no single, stable average loan amount or default rate that can be applied consistently across the portfolio.

**Why This Is a Business Problem**

This variability has direct business consequences. When borrower risk cannot be estimated reliably, credit decisions tend to drift toward one of two costly outcomes. If risk is underestimated, default rates rise above expectations, increasing credit losses and eroding profitability. If risk is overestimated, lending standards become overly conservative, excluding creditworthy customers and slowing growth in precisely the underserved segments that represent Home Credit’s core market opportunity. In both cases, the company faces inefficient use of capital and reduced ability to scale sustainably.

**Business Value of a Solution**

The business value of addressing this problem lies in improving the consistency and accuracy of risk assessment across markets and products. A more reliable approach to evaluating borrower risk would allow Home Credit to better align approvals, pricing, and portfolio exposure with actual repayment behavior. This would support tighter control of defaults while preserving access to credit for customers who can repay, strengthening both financial performance and the company’s financial inclusion objectives.

**Analytics Approach**

Achieving this outcome requires an analytics approach that directly links historical borrower behavior to future repayment outcomes. The problem is well suited to supervised learning, framed as a classification task in which the objective is to predict whether a loan will default within a defined observation window. By learning from labeled historical loan performance data, such models can estimate the probability of default in a way that is consistent with established credit risk practices, while remaining flexible enough to accommodate differences across markets and products.

**Success Metrics**

Success should be evaluated in business terms rather than purely technical ones. Stakeholders should expect to see a closer alignment between predicted and observed default rates, reduced unexpected credit losses at the portfolio level, and stable or improved approval rates for creditworthy customers. Equally important, model performance should remain consistent across countries and loan types, demonstrating that the approach adds value beyond any single market.

**Scope**

The scope of the project is intentionally focused on analytical development. Deliverables include data preparation, model development, and validation of a supervised default-prediction model using available Home Credit loan performance data. Changes to lending policy, pricing, or production system integration are out of scope for the initial phase, but could be considered later once analytical value has been demonstrated. Future extensions may include segmentation by product or market and regression-based estimation of expected loss components.

**Project Details**

The work will be executed by Home Credit’s analytics and data science teams in close collaboration with credit risk stakeholders. The project will proceed through standard phases of exploratory analysis, model development, validation, and stakeholder review, with clear milestones at each stage to ensure that analytical results translate into actionable business insight.