# Topbox Backend Take Home Test - Problem Statement

## Read the README!

The API schema is explained in the README.  
You can run everything via Docker. You can also run the flask app locally.

## Cloning the Repo

Please do not "fork" the repo using the Github Fork feature. 
Instead, import this project via the [Import a Repository feature](https://github.com/new/import). 
Use this for the Import URL: `https://github.com/topbox-rci/topbox-backend-takehome-test.git`

## Problem Statement

Currently, I can only return _all_ interactions via the `/interactions` endpoint.

As a consumer of our Export API, I need to filter `Interaction` data by `engagementId` and `interactionDate`.

Requirements:
- `engagementId` is mandatory (only data from one engagement may be returned at any given time! Do not mix client data)
- `interactionDate` filters are not mandatory, i.e. startDate and/or endDate are optional for querying on `interactionDate`

## Guidelines

1. The goal for this take-home test is to show us you can do research and add functionality to a REST service.  
1. Unit tests are not needed.  
1. There is no need to add new functionality to other endpoints (the focus is adding new functionality to `/interactions`)

## Turning in your work

1. Copy the publicly-available Github repo (per the instructions above).
2. Email the engineer who sent you the problem statement with a link to your repo, containing the necessary changes for this feature.