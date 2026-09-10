# Deployment Guide

> **Student template:** complete this document from the deployment you actually perform. Do not write an imaginary “perfect” procedure.

## 1. Deployment identification

- Application: The Developer Excuse Generator
- Release / version: v1
- Target environment: github
- Repository / project: https://github.com/leoboh/projet-1-ekod-anglais
- Branch used for deployment: main
- Date: 10
- Author: leo

## 2. Purpose and scope

What are you deploying, and what is included in this release?

I'm deploying an application named "The Developer Excuse Generator". This application is a web-based tool that generates excuses for developers. The release includes the source code and it's for the "main" branch of the repository.

## 3. Prerequisites

What must already be available, configured or confirmed before deployment can begin?

- IAM roles
- Environment variables
- All documents and files needed for the application ( ex : deployement-guide / package)
- Database access

## 4. Files and configuration involved

Which files or configuration values matter for this deployment?

| Item | Purpose | What must be checked? |
| .env | Environment variables | Ensure that the values ​​align well with the environment |
| .gitlab-ci.yml | Defines the deployment pipeline stages. | Ensure the deployment points to the correct branch/environment |
| README | helping for started the application | that all the files are indeed present for run the application |
|  |  |  |

## 5. Deployment procedure

Record the real procedure in the order you performed it.

| Step | Action | Expected result | Actual result / evidence |
| 1 | | clone repository  | git clone | obtaining the files | my repo "https://github.com/leoboh/projet-1-ekod-anglais"
| 2 | check files | ls | files are present | - 
| 3 | push a new commit | see the the link of the url in my deployement in github | the link is here | -
| 4 | Acces to the link of the application | test button | the button is not working on mine | - |
| 5 |  |  |  |
| 6 |  |  |  |
| 7 |  |  |  |
| 8 |  |  |  |

## 6. Post-deployment verification

What must be checked after deployment before you can call the release successful?

| Check | Expected result | Actual result | Pass / fail |
| --- | --- | --- | --- |
| the application starts and responds | the application start | the application start | Pass |
| no errors | no errors | no errors | Pass | 
| functional core user journeys (login, payment, account creation, etc.) | functional core user journeys | functional core user journeys | pass |
|  |  |  |  |

## 7. Evidence

Record the evidence that another person could use to confirm what happened.

- Project URL:
- Deployed application URL:
- Release / version observed:
- Pipeline / deployment result:
- Commit or reference:
- Other useful evidence:

## 8. Problems or deviations

Did anything happen differently from the planned procedure?

Yes, GitLab has changed its sign-up procedure. They have added a requirement to provide a bank card to verify the user's identity.

## 9. Documentation improvement

After completing the deployment, what should be added, removed or clarified in this guide before another person uses it?

Add a new commentary for github users to understand the deployment process. 
Delete my repository from the guide. 
