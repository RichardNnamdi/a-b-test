In the competitive landscape of digital marketing, driving high-intent engagement to a website is essential. However, translating that engagement into actionable leads is equally critical. I faced this exact challenge in an ongoing marketing campaign, where despite attracting the right audience and achieving substantial engagement metrics — such as views on the pricing page, clicks on testimonials, and demo video watches — demo form submissions (i.e demo requests) remained disappointingly low.

To tackle this, I proposed a solution to embed demo forms directly on the website’s product display landing page, enhancing visibility and prompting immediate action from visitors. This approach replaced the existing method where visitors had to click a demo CTA button that opened a submission modal.

Here’s a detailed explanation of the problem, the solution, the testing methodology, implementation, and the results.

The Business Problem
The primary goal was to increase the number of demo form submissions to generate more leads. The existing setup required visitors to click on a demo CTA button, which then opened a modal form for submission. While other engagement metrics were promising, the conversion rate for demo form submissions was suboptimal.

The Solution
To address this, I suggested embedding the demo form directly on the landing page. The rationale was simple: increased visibility and reduced friction would encourage more visitors to submit the form. This change aimed to create a seamless experience, prompting visitors to act without the extra step of opening a modal.

Testing the Solution
To evaluate the effectiveness of this change, I employed both frequentist and Bayesian statistical methods. Here’s a breakdown of the approach:

Frequentist Methods
Two-Proportion Z-Test: This test compares the conversion rates of the control group (original setup) and the treatment group (embedded form).
Chi-Squared Test: This assesses the independence of the conversion rates between the two groups.
Fisher’s Exact Test: This provides an exact p-value for small sample sizes, ensuring robustness in our results.
Bayesian Methods
Posterior Distributions: Using Bayesian statistics, I calculated the posterior distributions for the conversion rates of both the control and treatment groups.
Credible Intervals: These intervals provide a range of plausible values for the conversion rates, offering a probabilistic interpretation.
Probability of Improvement: This metric indicates the likelihood that the embedded form outperforms the modal form.
Implementation
To protect sensitive information, I won’t be sharing the actual website traffic data used in the A/B testing analysis. However, to illustrate the process, i’ll demonstrate the methodology using a Python script that generates realistic, simulated data.

[Link to medium article]([https://medium.com/@richardnnamdi12/driving-business-growth-through-data-driven-insights-a-success-story-in-end-to-end-customer-4db38507fd81](https://medium.com/@richardnnamdi12/a-b-testing-triumph-how-we-a-b-tested-our-way-to-more-demo-requests-d5d9e10733bf))
