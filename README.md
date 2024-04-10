# InterviewCaseEngThrive_Public
Fictitious sample data for an interview case

# EngThrive Data Analytics

## Background
- Engineering Thrive is a new program at Microsoft focused on improving developer productivity and satisfaction across Microsoft by identifying key drivers and operationalizing a consistent set of metrics to assess performance and evaluate the impact of new initiatives.

- One of the initial metrics that have been identified is something known as "Time to First Pull Request (TTFPR)".  It is defined as the elapsed time in days from when a new employee is hired and when they successfully complete a pull request.

- **You** are the senior data scientist that has been asked to implement this metric. Using the available data, conduct some exploratory analysis to characterize its behavior.  A complementary goal is to help establish procedures and benchmarks for evaluating performance across the company.

## Datasets
- **NewEmployees**: A list of new full time employees hired at Microsoft from 4/2023 - 9/2023 and meta data containing various details on their organization, role, internal identifiers, etc.

- **AADId_VSId_Map**: A mapping that links a given employee to their identifier(s) used in AzureDevOps

- **PullRequests**: Telemetry containing all of the Pull Requests created by our new employees since 4/2023

## Task
- You have an initial 90 minutes to implement the metric with the sample data set and create a short presentation with the results of your exploratory analysis and your proposal for how can use the metric to evaluate the impact of new initiatives.

- You may find the following questions helpful in helping you navigate the data and address some potential conceptual issues.  Note that these are optional and you may choose to focus on alternative questions/issues

  - What aspects of a development organization's business processes does TTFPR measure?

  - Should we restrict the class of employees that should be included?

  - Which statistic or statistics would you use to measure and describe the central tendency?

  - From 4/2023 to 9/2023, has there been a change in TTFPR?  Is the change statitically significant?

  - Does seniority of the new hire affect TTFPR?

  - Suppose one of the orgs, introduced a new program designed to accelerate TTFPR.  The program was introduced in January of 2024 and fully integrated by the end of February.  It is now August of 2024.  You have been asked to lead a study to address whether this program has had a positive impact on TTFPR.  How might you go about this study?

- A colleague is in the (virtual) office with you and is available to help get un-stuck and review draft outputs. They're seriously available to help if you want to confirm your approach or need help overcoming a hurdle!

- Final outputs: Code review of findings (slides or markdown file preferred) (15 minutes)

