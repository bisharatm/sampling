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

The number of your chosen topic: `1`

Describe the purpose of your survey:
```
write your answer here...

The purpose of this survey is to identify the drivers of high turnover among entry- and lower-level employees at A Large Tech Company, and to gather actionaable suggestions for reducing turnover and improving employee statisfaction.
```

Describe your target population, sampling frame, sampling units, and observational units:
```
write your answer here...

Target population: All entry- and lower-level employess across all  departments and those employess who recently left (last 12 months).

Sampling frame: HR database to get current employess filtered by entry- and lower-level positions and past employess who recently left.

Sampling units: Indiviual employees.

Observational units: Individual employees.
```

Your 5-10 question survey:
```
1. Overall, how satisfied are/were you with your job at this company?
Options: Very dissatisfied | Dissatisfied | Neutral | Statisfied | Very statisfied

2. How supported do/did you feel by your manager in your role?
Options: Not at all supported | Somewhat supported | Neutral | Well supported | Very well supported

3. Do/did you feel you have clear opportunities for career advancement here?
Options: Yes | No | Not sure

4. How likely are you to still be working here in 6 months?
Options: Very unlikely | Unlikely | Likey | Very likely | Not sure

5. How do/did you feel about  the compensation and benefits at the company?
Options: Under market | Up to market | Above market | Not sure

6. What are the most important areas where having high satisfaction would encourage you (or would have encouraged you) to stay? (select four)
Options:
- Pay and benefits
- Opportunities for promotion
- Quality of supervision
- Manager support
- Workload and work-life balance
- Onboarding and training
- Recognition for good work
- Clarity of role and responsibilities
- Team culture
- Other (please specify)

```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
Note: I refered to the following resource to find answers for the questions in this section: https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&Id=796234

1. Sample type: This is a two-stage stratified sampling. Stratification was done on the basis of geopgrahical areas including several Census Metropolitan Areas (CMAs) either individually or grouped, resulting in 27 strata in total. The sampling used a two-stage design. In the first stage, the sampling units are groups of telephone numbers associated with households. In the final stage the units are individuals within the identified household. One eligible individual per household is randomly selected to be interviewed.

2. Sample size: Field sample of ~50000 units across Canada was used. Approximately 40000 invitation letters to the questionnaire were sent to selected housholds. (~24000 completions were expected, but the actual completions were 16149.)

3. Target population: All persons aged 15 years and above living in the ten provinces of Canada, excluding full-time institutional residents.

4. Sampling frame: Landline and cellular telephone numbers from Census and other administrative sources combined with Statistics Canada's dwelling frame to obtain the sampling frame whose records are groups of one or more telephone numbers associated with a residential address.

5. Survey mode(s): Data was collected directly from respondents either through an electronic questionnaire or through computer assisted telephone interviewing. Respondents can chose to do the survey in either English or French. Proxy reporting was not allowed.

6. Timeline: Data was collected from 04-Sep-2018 to 28-Dec-2018, and the reference period was the preceding 12 months.

7. Response rate: The overall response rate was 41.9%

8. Weights: A person level weight WGHT_PER is used to calcualte popluation estimates.

9. Data processing: Processing used Statistics Canada’s standardized processing environment with automated and manual edits. Compuster Assisted Telephonic Interview (CATI) system enforced valid ranges, flow edits and immediate on-screen checks.

10. Cleaning, imputation, etc: Nearly all imputations were done by selecting the "nearest" donor record which was selected after scoring each donor based on matching similar or identical characteristics with the target (or recepient) record. In cases where this could not be done, then mean imputation among pool of donors was used. Imputation was done in multiple steps: income variables, formal volunteering variables, informal volunterring varaibles, donation variables, solicitation methods, etc. Personal and family income information was not directly asked in the survey, but was obtained by linking to tax data for respondents who consented to linking (~82%), and for the rest this was imputed.

11. Sources of error: The data is subject to sampling error, and reslutantly the estimates have sampling variablity. To account for this variablity properly, bootstrap method was used. Additionally, there are non-sampling errors such as imperfect coverage, non-response, response errors, processing errors, etc.

12. Limitations, known biases, etc: Coverage bias due to exclusion of certain households (i.e., those without telephone numbers or those with telephone numbers but not covered by the sampling frame) if they differ from the target population. The overall response rate of ~41.9% is a limitation and raises a concern for non-response bias.

13. Link to documentation and any additional sources used: https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&Id=796234
```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 19/10/2025`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [x] Create a branch called `assignment-2`.
- [x] Ensure that the repository is public.
- [x] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [x] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
