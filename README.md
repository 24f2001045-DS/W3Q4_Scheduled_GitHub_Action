# W3Q4_Scheduled_GitHub_Action
Cron Job
# Scheduled GitHub Action

This repository demonstrates a scheduled GitHub Actions workflow that:

- Runs once per day using cron syntax
- Includes a step containing the email 24f2001045@ds.study.iitm.ac.in
- Creates a new commit during each run
- Is located inside the `.github/workflows/` directory

## Schedule

The workflow runs daily at:

04:30 UTC (10:00 AM IST)

Cron expression used:

30 4 * * *

## Manual Trigger

The workflow also supports manual execution using `workflow_dispatch`.
