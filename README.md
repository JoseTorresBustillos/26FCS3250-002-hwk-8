# Overview

The goal of this assignment is to assess your understanding on how to write user stories. The user story format—typically written as:

```
As a [type of user], I want [some goal] so that [some reason]
```

—did originate from Agile methodologies, specifically from Extreme Programming (XP) and later became a core practice in Scrum and other Agile frameworks.

# Instructions 

Write 4 (four) user stories for the following scenario. 

A system that allows companies to hire employees to fill vacancies. A job description can be created and a link must be provided for posting on platforms such as LinkedIn and similar. Candidates apply for a job by filling out a form and sending documents such as CVs and letters of recommendation, for example. A hiring committee evaluates all candidates for a position. The system should allow the hiring committee to discard candidates who do not meet the requirements. In these cases, an email should automatically be sent to the candidate saying that they are no longer being considered. The remaining candidates are interviewed and a decision is then made. Analytical reports can be obtained for any completed hiring process.

Submit your answers by updating this file, rewriting the provided templates. 

## User Story #1

Context: "A job description can be created and a link must be provided for posting on platforms such as LinkedIn and similar" 

```
As an HR staff member, I want to create a job description and obtain a shareable application link so that I can advertise a vacancy on LinkedIn and similar platforms.

Given that I have entered the job description and requirements for a vacancy, when I publish the job posting, then the system saves the posting and generates a link that I can copy and share. When a candidate opens that link, then the system displays the corresponding job description and provides access to its application form.
```

## User Story #2

Context: "Candidates apply for a job by filling out a form and sending documents such as CVs and letters of recommendation, for example"

```
As a candidate, I want to submit an application form and supporting documents so that the hiring committee can consider me for a vacancy.

Given that I have opened the application form for an available vacancy, when I complete all required fields, attach the required documents such as my CV and letters of recommendation, and submit the form, then the system saves my application and documents under that vacancy and displays a submission confirmation. Given that a required field or document is missing, when I attempt to submit, then the system identifies the missing information and does not accept the incomplete application.
```

## User Story #3

Context: "A hiring committee evaluates all candidates for a position. The system should allow the hiring committee to discard candidates who do not meet the requirements. In these cases, an email should automatically be sent to the candidate saying that they are no longer being considered. The remaining candidates are interviewed and a decision is then made." 

```
As a hiring committee member, I want to evaluate all applicants against the job requirements, reject unqualified candidates, and record interviews and a hiring decision so that the committee can select a suitable employee and notify rejected applicants.

Given that candidates have applied for a vacancy, when I open its candidate list, then the system displays every application and its supporting documents for evaluation against the job requirements.

Given that an evaluated candidate does not meet the requirements, when I mark that candidate as rejected, then the system records the rejection, removes the candidate from further consideration, and automatically sends an email stating that the candidate is no longer being considered.

Given that a candidate meets the requirements and remains under consideration, when the committee interviews that candidate and records the interview outcome, then the system saves the outcome with that candidate's application. Given that the remaining candidates have been interviewed, when the committee records its final hiring decision, then the system saves the decision for the vacancy and marks the hiring process as completed.
```

## User Story #4

Context: "Analytical reports can be obtained for any completed hiring process"

```
As an HR staff member, I want to generate an analytical report for any completed hiring process so that I can assess its outcomes and improve future hiring efforts.

Given that a hiring process is marked as completed, when I select that process and request an analytical report, then the system generates and displays a report for that process showing the total number of applicants, the number rejected, the number interviewed, and the final hiring outcome. Given that a hiring process is still in progress, when I attempt to request its completed-process report, then the system explains that the process must be completed before that report is available.
```

# Rubric

+1 User Story #1

+1 User Story #2 

+2 User Story #3 

+1 User Story #4