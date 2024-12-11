Project Management Data (Synthetic Dataset)
This repository contains a synthetic dataset representing project performance data. The dataset includes details of various tasks within different projects, such as cost variance, schedule variance, and task descriptions. It is meant to simulate the type of data typically used in project management performance analysis.

Dataset Description
The dataset is structured to contain information about multiple projects, each with a set of tasks. For each task, key performance metrics like Cost Variance (CV) and Schedule Variance (SV) are provided. These metrics help in assessing the performance of projects against budget and time constraints.

File Information
File Name: projectmanagementllm_dataset.csv
File Format: CSV
Number of Projects: 2
Number of Tasks: 10 (split across multiple projects)
Columns in the Dataset
project_id: Unique identifier for each project or task record.
project: The name of the project (if applicable).
task: Task identifier associated with the project.
Cost Variance (CV): The difference between the budgeted cost of work performed and the actual cost. Positive values indicate cost savings, while negative values indicate cost overruns.
Schedule Variance (SV): The difference between the budgeted cost of work scheduled and the budgeted cost of work performed. Positive values indicate ahead of schedule, while negative values indicate delays.
description: A short description of the task and its objectives.
Performance Metrics (Not Included in CSV)
In the raw dataset, projects also include aggregated performance metrics such as:

    Budget at Completion (BAC): The total budget for the project.
    Planned Value (PV): The budgeted cost for work scheduled.
    Earned Value (EV): The budgeted cost for work performed.
    Actual Cost (AC): The actual cost incurred to perform the work.
    Cost Performance Index (CPI): A ratio of earned value to actual cost (EV/AC).
    Schedule Performance Index (SPI): A ratio of earned value to planned value (EV/PV).
    Estimate at Completion (EAC): The expected total cost of completing all work.
    Variance at Completion (VAC): The projected difference between BAC and EAC.

Purpose of the Dataset
This dataset was synthetically generated for illustrative purposes. It is ideal for demonstrating project management metrics analysis, earned value management (EVM) practices, and training machine learning models that deal with project performance data.

Please note: This is a synthetic dataset and does not represent actual project data.

License
This dataset is freely available for use in educational, research, or project management demonstrations. Since it is synthetic, there are no restrictions on its usage.
---
license: mit
task_categories:
- table-question-answering
tags:
- projectmanagement
- pmi
- pmp
- evm
- agile
- ipm
---