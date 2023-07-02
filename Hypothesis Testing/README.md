# EDA - Hypothesis Testing
Welcome to the Hypothesis Testing Readme! This document serves as a guide to understanding the concept of hypothesis testing and its application in statistical analysis. Whether you are a student, researcher, or data analyst, this readme will provide you with a solid foundation for conducting hypothesis tests and interpreting their results.

Hypothesis testing is a fundamental concept in statistics that allows us to make inferences and draw conclusions about a population based on a sample. It involves formulating two competing hypotheses, the null hypothesis (H₀) and the alternative hypothesis (H₁), and using statistical evidence to determine which hypothesis is more plausible.

In this readme, we will cover the basic steps involved in hypothesis testing, including:

    1. Formulating the null and alternative hypotheses.
    2. Choosing an appropriate significance level.
    3. Selecting a statistical test.
    4. Collecting and analyzing the data.
    5. Interpreting the test results.
    6. Drawing conclusions and making decisions.

By understanding and following these steps, you will be able to apply hypothesis testing to a wide range of scenarios, including medical research, social sciences, quality control, and much more.

    Formulating the null and alternative hypotheses.
    
Formulating the null and alternative hypotheses is a critical step in hypothesis testing. These hypotheses define the competing explanations or claims about the population that you want to investigate. The null hypothesis (H₀) represents the default or conventional position, while the alternative hypothesis (H₁) represents an alternative or contradictory claim. The hypotheses are formulated based on the research question or problem at hand.

Here are some guidelines for formulating the null and alternative hypotheses:

Null Hypothesis (H₀): The null hypothesis represents the absence of an effect, relationship, or difference. It states that there is no significant change or difference in the population parameter or variables under investigation. The null hypothesis is often denoted as "H₀."

Example: "There is no significant difference in the mean heights of two different plant species."

Alternative Hypothesis (H₁): The alternative hypothesis contradicts the null hypothesis and represents the claim or effect you are investigating. It states that there is a significant change, relationship, or difference in the population parameter or variables. The alternative hypothesis is often denoted as "H₁."

Example: "There is a significant difference in the mean heights of two different plant species."

Directional vs. Non-directional Hypotheses: Alternative hypotheses can be either directional or non-directional. In a directional (one-tailed) hypothesis, you specify the expected direction of the effect or difference. In a non-directional (two-tailed) hypothesis, you do not specify the direction but simply state that there is a difference or effect.

Directional: "The mean height of plant species A is significantly greater than the mean height of plant species B."
Non-directional: "There is a significant difference in the mean heights of plant species A and B."
Remember that the null hypothesis is assumed to be true until statistical evidence suggests otherwise. The alternative hypothesis is the claim that you are testing and seeking evidence for. The choice of null and alternative hypotheses depends on the research question, the variables being investigated, and the specific goals of your study.

It's important to note that the formulation of hypotheses is often guided by prior knowledge, existing theories, or exploratory data analysis. Well-defined and carefully formulated hypotheses contribute to the clarity and validity of your hypothesis testing process.

    Choosing an appropriate significance level.

Choosing an appropriate significance level, also known as the alpha level (α), is an important decision in hypothesis testing. The significance level determines the threshold for accepting or rejecting the null hypothesis based on the evidence provided by the data. It represents the maximum probability of making a Type I error, which is the rejection of the null hypothesis when it is actually true.

Here are some considerations for choosing the significance level:

Commonly Used Significance Levels: The most commonly used significance levels are 0.05 (5%) and 0.01 (1%). These values provide a balance between Type I and Type II errors. However, other significance levels, such as 0.10 (10%) or more stringent values like 0.001 (0.1%), can also be chosen based on the specific context and the consequences of errors.

Nature of the Research Problem: The choice of significance level should be influenced by the nature of the research problem, its importance, and the consequences of making incorrect conclusions. For critical or high-stakes decisions, a lower significance level may be appropriate to minimize the risk of Type I errors.

Existing Standards or Guidelines: Some fields or research communities have established standards or guidelines for choosing the significance level. For example, in medical research, a significance level of 0.05 is often used as a common threshold.

Sample Size and Power Analysis: The choice of significance level can be influenced by the sample size and the desired statistical power. With larger sample sizes, smaller effect sizes can be detected, allowing for a more stringent significance level.

Consideration of Multiple Comparisons: If you are conducting multiple hypothesis tests simultaneously, such as in a study with multiple variables or treatments, it's important to consider the issue of multiple comparisons. In such cases, adjusting the significance level using methods like Bonferroni correction or false discovery rate (FDR) control may be necessary to maintain an appropriate overall significance level.

Ultimately, the choice of significance level involves a trade-off between the risk of Type I and Type II errors, the research context, and the specific requirements of the study. It is crucial to carefully consider these factors and make an informed decision.

It's worth noting that the significance level is not a direct measure of practical significance or the magnitude of an effect. It only serves as a threshold for decision-making in hypothesis testing.

    Selecting a statistical test.
    
Selecting the appropriate statistical test for hypothesis testing depends on various factors, such as the research question, the type of data, the number of groups being compared, and the assumptions associated with each test. Here are some guidelines to help you choose the right statistical test:

Nature of the Research Question: Consider the nature of your research question and the variables involved. Determine whether you are comparing means, proportions, correlations, differences between groups, or relationships between variables. This will help you narrow down the types of statistical tests that are suitable for your analysis.

Type of Data: Identify the type of data you are working with. Common types include:

Continuous Data: If you are comparing means or analyzing quantitative variables, you might consider tests such as t-tests, analysis of variance (ANOVA), or regression analysis.
Categorical Data: If you are comparing proportions or analyzing categorical variables, tests like chi-square tests or Fisher's exact tests may be appropriate.
Ranked or Ordinal Data: If you have ranked or ordinal data, non-parametric tests like the Wilcoxon rank-sum test or the Kruskal-Wallis test can be used.
Number of Groups: Consider the number of groups being compared or the design of your study. For example:

Two Groups: If you are comparing two groups, tests like the independent t-test or paired t-test (for related samples) can be used for continuous data. For categorical data, you can use the chi-square test or Fisher's exact test.
More than Two Groups: If you have more than two groups, ANOVA or non-parametric alternatives like the Kruskal-Wallis test can be used for continuous data. For categorical data, you can use chi-square tests or logistic regression.
Assumptions: Take into account the assumptions associated with each statistical test. Some tests assume normality of the data, equal variances, or independence of observations. Violation of these assumptions may require alternative tests or data transformations. It is important to assess whether your data meets the assumptions of the chosen test.

Sample Size: Consider the sample size available for your analysis. Some tests, such as t-tests and ANOVA, have specific assumptions related to sample size. For smaller sample sizes or non-normal data, non-parametric tests may be more appropriate.

Consulting Statistical Resources: Consult statistical textbooks, online resources, or statistical software documentation to explore the available statistical tests and their appropriate use for different scenarios.

Remember, the choice of a statistical test should align with the research question, the type of data, and the assumptions associated with each test. It is essential to understand the requirements and limitations of each test to ensure accurate and meaningful results.

    Collecting and analyzing the data.

 Collecting and analyzing the data is a crucial step in hypothesis testing. Here are some steps to guide you through this process:

Data Collection Planning: Determine the variables you need to collect for your analysis. Plan your data collection process carefully, ensuring that you capture relevant information in a systematic and unbiased manner. Consider factors such as sample size, sampling methods, data quality assurance, and ethical considerations.

Data Preparation: Clean and organize your data to ensure its quality and suitability for analysis. This may involve tasks such as checking for missing data, handling outliers, transforming variables if necessary, and creating new variables or derived measures.

Descriptive Statistics: Start by exploring and summarizing your data using descriptive statistics. Calculate measures such as mean, median, standard deviation, and percentages to gain an understanding of the central tendency, variability, and distribution of your variables. Visualizations, such as histograms, box plots, and scatter plots, can provide additional insights.

Selecting the Appropriate Statistical Test: Based on your research question, type of data, and hypotheses, select the appropriate statistical test (as discussed earlier). Ensure that the assumptions associated with the chosen test are met or take appropriate steps to address violations.

Performing the Statistical Test: Apply the chosen statistical test to your data. This may involve using software packages like R, and Python (with libraries such as stats models and scipy. stats), or dedicated statistical software (e.g., SPSS, SAS). Follow the specific syntax or functions to conduct the analysis correctly.

Interpreting the Results: Analyze the output of the statistical test. Look for relevant statistical measures such as p-values, test statistics, confidence intervals, and effect sizes. Interpret these results in the context of your research question and hypotheses. Determine whether the results provide evidence to support or reject the null hypothesis.

Consideration of Practical Significance: While statistical significance is important, also consider the practical significance or real-world implications of the findings. Even if a result is statistically significant, it may not be practically significant if the effect size is negligible or not practically meaningful.

Sensitivity Analysis: Perform sensitivity analysis, if applicable, to assess the robustness of your results. This involves examining the impact of different assumptions or scenarios on the conclusions.

Reporting and Visualization: Summarize and report your findings in a clear and concise manner. Present your results through tables, figures, or charts, and provide an interpretation of the key findings. Be transparent about the limitations and assumptions of your analysis.

Remember to maintain proper documentation throughout the data collection and analysis process. This documentation will help ensure reproducibility and facilitate further analysis or review by others.

It's worth noting that data analysis can be a complex task, and it's advisable to seek guidance from experts or refer to statistical textbooks, online resources, or statistical software documentation to ensure the proper execution of the analysis.

    Interpreting the test results.

Interpreting the test results is a crucial step in hypothesis testing as it allows you to draw conclusions about the data and make informed decisions. Here are some guidelines to help you interpret the results of a statistical test:

Look at the Test Statistic: Examine the test statistic reported in the output of the statistical test. The test statistic measures the strength of the evidence against the null hypothesis. Different tests have different test statistics (e.g., t-statistic, F-statistic, chi-square statistic). Assess whether the test statistic is large or small relative to its sampling distribution under the null hypothesis.

Consider the P-value: The p-value is a measure of the strength of evidence against the null hypothesis. It represents the probability of obtaining results as extreme as the observed results, assuming the null hypothesis is true. A smaller p-value indicates stronger evidence against the null hypothesis. Generally, a p-value less than the chosen significance level (alpha) leads to rejecting the null hypothesis.

If the p-value is less than alpha: Reject the null hypothesis. The data provides evidence to support the alternative hypothesis.
If the p-value is greater than or equal to alpha: Fail to reject the null hypothesis. The data does not provide strong enough evidence to support the alternative hypothesis.
Examine Confidence Intervals (if applicable): If the statistical test provides confidence intervals, analyze them alongside the p-value. Confidence intervals give a range of plausible values for the population parameter. If the null hypothesis value lies outside the confidence interval, it supports rejecting the null hypothesis.

Consider the Effect Size: Assess the effect size, which quantifies the magnitude of the difference or relationship between variables. Common effect size measures include Cohen's d, eta-squared, odds ratio, or correlation coefficient. Larger effect sizes indicate more substantial practical or substantive significance.

Contextualize the Findings: Interpret the results in the context of the research question and the specific domain. Consider the implications of the findings and whether they align with existing theories, previous research, or practical significance. Think about how the results contribute to the overall understanding of the topic.

Acknowledge Limitations: Recognize the limitations and assumptions associated with the statistical test and the data analysis. Be transparent about any potential sources of bias, confounding variables, or issues with data quality that may affect the interpretation of the results.

Seek Expertise: If you are unsure about the interpretation or implications of the results, consult with a subject matter expert or a statistician who can provide guidance and help ensure accurate interpretation.

Remember that interpreting the results of a statistical test requires a combination of statistical knowledge, domain expertise, and critical thinking. It is important to avoid overgeneralization or misinterpretation of the findings and to consider the results in the broader context of the research question and existing knowledge in the field.

    Drawing conclusions and making decisions.

Drawing conclusions and making decisions based on the results of a hypothesis test is an important step in the data analysis process. Here are some guidelines to help you in this process:

Evaluate the Evidence: Consider the results of the hypothesis test, including the test statistic, p-value, and effect size. Assess whether the evidence supports or contradicts the null hypothesis. Look for consistency across different statistical measures and consider the magnitude of the effect size.

Compare with the Significance Level: Compare the p-value with the chosen significance level (alpha) that you defined at the beginning of the analysis. If the p-value is smaller than alpha, it suggests that the evidence against the null hypothesis is statistically significant. If the p-value is larger than or equal to alpha, it indicates that the evidence is not strong enough to reject the null hypothesis.

Consider Practical Significance: Even if the results are statistically significant, it is essential to assess their practical significance or real-world importance. Ask yourself whether the observed effect size or difference is large enough to be practically meaningful or relevant to the research question or decision-making process.

Interpretation in the Context of the Research Question: Interpret the results in the context of the research question, objectives, and existing knowledge. Consider whether the findings align with previous research, theoretical frameworks, or expectations. Assess the implications of the results for the specific problem or decision at hand.

Consider Limitations: Acknowledge the limitations of the study and potential sources of bias or confounding factors that could affect the interpretation of the results. Be transparent about any assumptions or caveats associated with the statistical test or data analysis process.

Communicate the Findings: Summarize the conclusions drawn from the analysis in a clear and concise manner. Communicate the results to stakeholders or the intended audience using appropriate language and visualizations. Present the evidence, interpretation, and any recommended actions or further investigations that arise from the analysis.

Make Informed Decisions: Based on the conclusions drawn from the hypothesis test, use the results to inform decision-making processes. Consider whether the evidence supports accepting or rejecting the null hypothesis. Determine the potential implications and consequences of the decisions based on the findings.

Iterate and Refine: Data analysis is an iterative process. If the results lead to rejecting the null hypothesis, consider further investigations, additional analyses, or modifications to the research design. Revisit the research question and refine the analysis plan if needed.

Remember that hypothesis testing provides a framework for making decisions based on statistical evidence. However, it is important to consider the results in conjunction with other information, expertise, and practical considerations to ensure that decisions are well-informed and appropriate for the specific context.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

 ## Hypothesis Testing
    1. Significance Level
    2. Blinkit vs Instamart
    3. Poverty and Dietary Calcium
    4. Association between Eye Color and Hair Color
    5. Biased Die
    6. Checking variation in heights
    7. Checking Assumptions of Anova
