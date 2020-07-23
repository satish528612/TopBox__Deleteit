# Topbox Backend Take Home Test - Problem Statement

## Read the README!

The API schema is explained in the README.  
You can run everything via Docker. You can also run the flask app locally.

## Problem Statement

Currently, I can only return all interactions via the `/interactions` endpoint. This could potentially cause data breaches by mixing multiple engagements-worth of data together!

As a consumer of our Export API, I need to filter `Interaction` data by `engagementId` and `interactionDate`.

Requirements:
- `engagementId` is mandatory (only data from one engagement may be returned at any given time! Do not mix client data)
- `interactionDate` filters are not mandatory, i.e. startDate and/or endDate are optional for querying on `interactionDate`

## Guidelines

1. The goal for this take-home test is to show us you can do research and add functionality to a REST service.  
1. Unit tests are not needed.  
1. There is no need to add any new funtionality to the exisiting endpoints

## Turning in your work

1. Fork the publicly-available Github repo.
2. Email the engineer who sent you the problem statement with a link to your forked repo, containing the necessary changes for this feature.