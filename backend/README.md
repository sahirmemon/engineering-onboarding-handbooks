# Onboarding Handbook

### Welcome & Introductions

We would like to welcome you to Pager Inc. The purpose of this onboarding handbook is to provide you with comprehensive guidance and direction during your onboarding, familiarize you with Pager Inc. systems, designate a coding buddy, and generally set you up for success.

### Team Structure at Pager

Pager engineering consists of five squads, most of them specializing in a different Pager product:

| Squad Name | Slack Channel | Email distro | JIRA Board |
| ----- | ------ | ---- | ---- |
| Management Enterprise (ME) | #squad-management-enterprise | squad-management-enterprise@pager.com | [ME backlog](https://pagerinc.atlassian.net/secure/RapidBoard.jspa?rapidView=92&projectKey=EA&view=planning.nodetail&selectedIssue=EA-232&epics=visible&issueLimit=100) |
| Consumer Squad (CS) | #squad-consumer | squad-consumer@pager.com | [CS backlog](https://pagerinc.atlassian.net/secure/RapidBoard.jspa?rapidView=49&view=planning.nodetail&issueLimit=100) |    
| Users Enterprise (UE) | #squad-users-enterprise | squad-users-enterprise@pager.com | [UE backlog](https://pagerinc.atlassian.net/secure/RapidBoard.jspa?rapidView=79&projectKey=UE&view=planning&selectedIssue=UE-912&epics=visible&issueLimit=100) |    
| Professional Services Squad (PSS) | #squad-professional-services | squad-professional-services@pager.com | [PSS backlog](https://pagerinc.atlassian.net/secure/RapidBoard.jspa?rapidView=87&projectKey=PSS&view=planning&selectedIssue=PSS-18&issueLimit=100) |
| Platform Squad (PS) | #squad-platform | squad-platform@pager.com | [PS backlog](https://pagerinc.atlassian.net/secure/RapidBoard.jspa?rapidView=59&projectKey=PS&view=planning.nodetail&selectedIssue=PS-674&issueLimit=100) |

Except Platform Squad, each squad contains engineers from frontend (web and/or mobile), backend, machine learning/data as well as QA. Here is the [org chart](https://docs.google.com/drawings/d/14hRZNhhM9m_t88lR9jOoqDkvewiQDf3Rc0wW7n3iyDI/edit) for our squads.
If interested, see [this medium article](https://medium.com/scaled-agile-framework/exploring-key-elements-of-spotifys-agile-scaling-model-471d2a23d7ea) for more information about squad structure.

During your first week, you will be meeting your team members, as well as team leads, who will provide you with an important overview of their respective areas of expertise.

**Your Direct Manager:** [Insert name]\
Your manager will meet with you on your first day to welcome you to Pager, get to know you, understand your personal and professional goals. The purpose of the first meeting is to introduce you to this document, and set initial expectations. We value you and your experience at Pager. We plan to do everything at our disposal to help you grow  as you help grow us. Your manager will walk you through the [Engineering Career Ladder](https://docs.google.com/drawings/d/13-xyAbH8qmyRwgQu7hKC-5cnS6VUcb4pmUiMVIeKbYY) and your respective [Individual Contributor Performance Ruberic](https://docs.google.com/spreadsheets/d/1yoCXujJQ07FcHjKGPYO10RJM9nDKRyD9VLeJGpsZgGM/edit?usp=sharing0). You will have a second meeting with your manager at the end of your first week, to check-in on your onboarding progress and introduce you to your [30-60-90](https://docs.google.com/spreadsheets/d/1gQHA8cq6R8VS-mKz2Qe2OwoRHE8hGOsJPph4h9x9EfQ/edit?usp=sharing) day plan. Once you and your manager go through these you will also set up your weekly one on ones. 

**Coding Buddy:** [Insert name]\
One of the key figures during your first few weeks is your coding buddy. Your coding buddy will be your initial source of information about various systems, tools and practices at Pager. In addition to being your go-to person for code related questions, you can expect your coding buddy to help you pick up your first coding assignments. This will help you dive into coding as quickly as possible, without overwhelming you.

**Frontend Lead:** Mi Ji Kim\
Mi Ji will introduce you to our frontend code, talk about applications such as Command Center and Enterprise Admin. This is an opportunity for you to better understand one of the central applications of our ecosystem and how it ties in with the various backend services.

**Backend Leads:** Ryan Hall (ME), Elba Sanchez (CS), Diego Baquero (UE), Jugal Shah (PSS)\
Ryan will provide you with an overview of our application architecture, introduce you to various aspects of our microservices, and talk about the architectural vision and direction we would like to move towards.

**Mobile Lead:** Fabian Celdeiro\
Fabian will provide you with an overview of Android and iOS applications, as well as help you understand how to install a test application, how to login and test.

**Platform Lead:** Jeremiah Bowen\
Jeremiah will provide you with a high level overview of Pager’s infrastructure, environments and platform tools as they pertain to software engineering. This is a great opportunity for you to understand the operational environment that you will be placed in.

**QA Manager:** Jesmin Aktar\
Jesmin will introduce you to her team members, as well as go over the QA process. This is an excellent opportunity to make some friends in the QA team.

**Director of Engineering:** Shay Weiss\
Introductory meeting with Shay Weis. Shay will provide you with information about engineering vision and get to know you a little better.

### Tools and Processes

At Pager, we use a number of tools that help us keep track of our work, documentation, application metrics and logs. This section lists those tools, and how to access them.

Please make sure to enable 2FA where available.

**Github:** <https://github.com>\
You will need to create a new github account tied to your pager.com email.

**Jira and Confluence:** <https://pagerinc.atlassian.net>\
Use your Pager gmail account to login.

**GoogleCloud Dashboard:** <https://console.cloud.google.com>\
Use your Pager gmail account to login.

**Sentry:** <https://sentry.io/auth/login/pager-oj/>\
Follow instructions in the invitation email to set up your password. Please make sure to set up two factor authentication.

**NewRelic:** <https://login.newrelic.com/>\
Follow instructions in the invitation email to set up your password.

**SumoLogic:** <https://service.sumologic.com/ui/>\
Follow instructions in the invitation email to set up your password. Please make sure to set up two factor authentication.

**MixPanel:** <https://mixpanel.com/>\
Follow instructions in the invitation email to set up your password.

**PagerDuty:** <https://pagerinc.pagerduty.com/>\
Use your Pager credentials (Jumpcloud SSO) to login after your manager onboard you on this platform

**Github:** <https://github.com>\
You will need to create a new github account tied to your pager.com email.

**Greenhouse:** <https://app.greenhouse.io/>\
Use you Google SSO to sign in and ask Gavin Clarke of the recruiting team for permissions


### Command line utilities

These are the command line utilities you will likely to need to do your job

**brew:** <https://brew.sh/>\
If you use Mac, you are likely to need brew to install other utilities

**node:** <https://nodejs.org/en/download/>\
Node js is the main platform we are using now

**git:**
Don't need to download anything, simply run `brew install git` , git will be installed

**gcloud:** <https://cloud.google.com/sdk/docs#install_the_latest_cloud_tools_version_cloudsdk_current_version>\
Google Cloud cli

**psql:** <https://www.postgresql.org/download/>\
You need the psql client to run SQL query, but you are welcome to use other GUI (e.g pgadmin) if you want

**mongo:** <https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/>\
You need the mongo shell client to run mongo query, but you are welcome to use other GUI (e.g Mongo 3T) if you want

**docker:** <https://docs.docker.com/docker-for-mac/install/>\
You need the docker to run our containers

**kubectl:** <https://kubernetes.io/docs/tasks/tools/install-kubectl/>\
You need the kubectl interact with the Kubernetes cluster. This can be installed using brew as well: `brew install kubectl`

**sops:** <https://formulae.brew.sh/formula/sops>\
You need the sops to encrypt/decrypt the passwords


**Download the mobile app:**\
Send your email address to Fabian Celdeiro, who is the mobile manager.
He will add you to the list. Once you get an invitation go to this website. https://appcenter.ms/apps
Download the test app according to you are iPhone or Android


We are excited that you are joining our team, and wish to provide you with an easy and productive onboarding experience. Should you encounter any questions or difficulties at any time, do not hesitate to reach out to your direct manager or designated coding buddy. We are here to help!

Welcome to Pager!
