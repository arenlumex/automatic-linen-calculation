# Automatic Linen Calculation

Backend service that receives reservation events and keeps the linen (sheets, towels, bathmats, handtowels, dishtowels, sofa beds) of open Main Cleaning tasks up to date. React + TypeScript front end for viewing tasks, linen, and recalculation history.

Status: project foundation only. Business logic, API, database, and UI are not implemented yet.

## Input data

`data/` contains the four source files (`listings.json`, `reservations.json`, `tasks.json`, `events.json`) and the task specification (`TMS-Linen-Test-Task.pdf`). The source files are never modified.

## Documentation to be completed

Setup, database initialization, seeding, testing, run commands, and documented limitations will be added as each stage is implemented.
