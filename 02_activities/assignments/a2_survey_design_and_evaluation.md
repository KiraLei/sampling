# Assignment: Questionnaire Design and Sample Evaluation

## Requirements

The goal of this assignment is to practice developing and evaluating sampling materials.

### Part A - Survey Design:

Select one of the scenarios below and design a survey to meet the need(s) outlined in the prompt.

1.	In two to three sentences, describe the purpose of your survey
2.	Describe your target population, sampling frame, sampling units, and overall sampling strategy.
3.	Write a 5-10 question survey to address your chosen scenario below.

##### Scenarios
1.	You work in the Human Resources Department at a large tech company. Over the past few months, the company has been experiencing a high turnover rate across many of its departments, specifically within the entry- and lower-level positions. The company wishes to understand why this turnover is happening, and what changes need to occur to improve employee satisfaction.
2.	You work for a Canadian national political party during a federal election. Throughout the campaign period, your party has seen relatively high approval ratings, but an opposing party is also polling favorably and may still have a chance to win the election. You are one month away from the election and you want to understand what voters want from your party and its leader in order to maintain your lead and eventually win the election.
3.	You are a student researcher in the sociology department at the University of Toronto. You are working on a research project that concerns the relationship between music taste and age. This involves both comparisons between different people of different ages and comparisons of the same individual at different ages during their lifetime. You wish to understand to what extent age influences music taste, specifically as it relates to perceptions of popular music. Your results will be written into an academic paper that you hope to publish.

### Part B - Survey Evaluation:

For the **Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33)**, conducted by Statistics Canada find any and all available documentation for the data gathered and identify and describe the survey features indicated below.

1. Sample type
2. Sample size
3. Target population
4. Sampling frame
5. Survey mode(s) 
6. Timeline
7. Response rate
8. Weights
9. Data processing
10. Cleaning, imputation, etc
11. Sources of error
12. Limitations, known biases, etc
13. Link to documentation and any additional sources used


# Your Changes

## Part A - Survey Design: 

The number of your chosen topic: `#`

Describe the purpose of your survey:
```
The purpose of this survey is to understand the reasons behind the high turnover rate among entry- and lower-level employees at the company. It aims to identify areas where employee satisfaction can be improved to reduce resignations.
```

Describe your target population, sampling frame, sampling units, and observational units:
```
The target population includes all current and recently departed entry- and lower-level employees across departments. The sampling frame will be the internal HR database of current and past employees who left within the past 12 months. The sampling units are individual employees selected from the database. The sampling strategy will be stratified random sampling by department to ensure representation across the company.
```

Your 5-10 question survey:
```

1. How satisfied were you with your overall experience working at the company?

Very satisfied

Somewhat satisfied

Neutral

Somewhat dissatisfied

Very dissatisfied

2. What were your main reasons for leaving (or considering leaving) the company? (Select all that apply)

Low salary

Lack of growth opportunities

Poor management

Work-life balance

Company culture

Other (please specify)

3. Did you feel that your work was valued by your team and supervisors?

Always

Often

Sometimes

Rarely

Never

4. How would you rate communication within your team and department?

Excellent

Good

Fair

Poor

Very poor

5. Would you recommend the company as a good place to work to others?

Yes

No

Not sure

6. Were there enough opportunities for career development or promotion?

Yes

No

Somewhat

7. What changes would you suggest to improve employee retention?

8. How long did you work at the company before leaving?

Less than 6 months

6 months to 1 year

1 to 2 years

More than 2 years

9. What department did you work in?

Engineering

Marketing

Customer Service

HR

Other

10. Please share any additional comments about your experience.
```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
## Part B - Survey Evaluation:

1. **Sample type**:  
   Stratified probability sampling with a cross-sectional design. The sampling design included stratification at the province and Census Metropolitan Area (CMA) level.

2. **Sample size**:  
   Approximately 50,000 units were selected; around 40,000 invitation letters were sent, and about 24,000 responses were completed.

3. **Target population**:  
   All individuals aged 15 years and older living in the ten Canadian provinces, excluding those residing in institutions for more than six months.

4. **Sampling frame**:  
   A composite frame combining landline and cellular telephone numbers from the Census, administrative data, and Statistics Canada’s dwelling frame.

5. **Survey mode(s)**:  
   Data was collected through two modes: Computer-Assisted Telephone Interviewing (CATI) and a self-administered electronic questionnaire. Respondents could choose between English and French.

6. **Timeline**:  
   Data collection took place from **September 4 to December 28, 2018**. The survey is conducted every 5 years.

7. **Response rate**:  
   The overall response rate was **41.9%**.

8. **Weights**:  
   Person-level weighting factors were applied to adjust for the probability of selection, non-response, and to ensure that the weighted sample reflected the Canadian population. Bootstrap weights were also created for variance estimation.

9. **Data processing**:  
   Processing included automatic and manual edits, consistency checks (e.g., age vs. date of birth), and flow control logic. CATI software enforced input validation, and Statistics Canada staff reviewed and finalized the data.

10. **Cleaning, imputation, etc**:  
   Donor imputation was used for missing values, comparing characteristics of respondents to find the "nearest" donor. For income variables, linkage to administrative tax data (T1FF) was used. Where linkage was not possible, mean imputation was applied. A nine-step imputation process was used for variables such as income, volunteering, and donations.

11. **Sources of error**:  
   - **Sampling error**: Results are based on a sample and subject to variability. Bootstrap methods were used to estimate this.
   - **Coverage error**: Households without phones were excluded. Imperfect coverage may result in bias.
   - **Non-sampling error**: Includes processing errors, response errors, and non-response.

12. **Limitations, known biases, etc**:  
   - Potential bias from excluding institutionalized populations and phoneless households.
   - Self-reporting may introduce recall bias or social desirability bias.
   - Despite weighting and adjustments, some populations may be underrepresented (e.g., marginalized groups).
   
13. **Link to documentation and additional sources**:  
   - https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&SDDS=4430&lang=en
```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 29/06/2025`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
