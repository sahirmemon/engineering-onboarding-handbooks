# Onboarding Handbook

### Welcome & Introductions

We would like to welcome you to Pager Inc. The purpose of this onboarding handbook is to provide you with comprehensive guidance and direction during your onboarding, familiarize you with Pager Inc. systems, designate a coding buddy, and generally set you up for success.

### Team Structure at Pager

Pager engineering consists of five squads, most of them specializing in a different Pager product:

| Squad Name | Slack Channel | Email distro | JIRA Board |
| ----- | ------ | ---- | ---- |
| Management Enterprise (ME) | #squad-management-enterprise | squad-management-enterprise@pager.com | [ME backlog](https://pagerinc.atlassian.net/secure/RapidBoard.jspa?rapidView=64&projectKey=ME&view=planning.nodetail&issueLimit=100) |
| Consumer Squad (CS) | #squad-consumer | squad-consumer@pager.com | [CS backlog](https://pagerinc.atlassian.net/secure/RapidBoard.jspa?rapidView=49&view=planning.nodetail&issueLimit=100) |    
| Users Enterprise (UE) | #squad-users-enterprise | squad-users-enterprise@pager.com | [UE backlog](https://pagerinc.atlassian.net/secure/RapidBoard.jspa?rapidView=79&projectKey=UE&view=planning&selectedIssue=UE-912&epics=visible&issueLimit=100) |    
| Professional Services Squad (PSS) | #squad-professional-services | squad-professional-services@pager.com | [PSS backlog](https://pagerinc.atlassian.net/secure/RapidBoard.jspa?rapidView=87&projectKey=PSS&view=planning&selectedIssue=PSS-18&issueLimit=100) |
| Platform Squad (PS) | #squad-platform | squad-platform@pager.com | [PS backlog](https://pagerinc.atlassian.net/secure/RapidBoard.jspa?rapidView=59&projectKey=PS&view=planning.nodetail&selectedIssue=PS-674&issueLimit=100) |

Except Platform Squad, each squad contains engineers from frontend (web and/or mobile), backend, machine learning/data as well as QA. Here is the [org chart](https://docs.google.com/drawings/d/14hRZNhhM9m_t88lR9jOoqDkvewiQDf3Rc0wW7n3iyDI/edit) for our squads. 
If interested, see [this medium article](https://medium.com/scaled-agile-framework/exploring-key-elements-of-spotifys-agile-scaling-model-471d2a23d7ea) for more information about squad structure. 

During your first week, you will be meeting your team members, as well as team leads, who will provide you with an important overview of their respective areas of expertise. 

**Your Direct Manager:** [Insert name]\
Your manager will meet with you on your first day to welcome you to Pager, get to know you, understand your personal and professional goals. The purpose of the first meeting is to introduce you to this document, and set initial expectations. You will have a second meeting with your manager at the end of your first week, to check-in on your onboarding progress and introduce you to your 30-60-90 day plan.

**Coding Buddy:** [Insert name]\
One of the key figures during your first few weeks is your coding buddy. Your coding buddy will be your initial source of information about various systems, tools and practices at Pager. In addition to being your go-to person for code related questions, you can expect your coding buddy to help you pick up your first coding assignments. This will help you dive into coding as quickly as possible, without overwhelming you.

**Designer:** Merry Chen\
Merry Chen is the company designer. As a frontend developer the interaction with the design team is a must.

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

**Director of engineering:** Shay Weiss\
Introductory meeting with Shay Weis. Shay will provide you with information about engineering vision and get to know you a little better.

### Frontend Repositories

Main frontend product repos:\
[Command Center](https://github.com/pagerinc/web-command-center): Chat application that allows clinical and non-clinical staffs to chat with patients\
[Enterprise Admin](https://github.com/pagerinc/enterprise-admin): Admin tool for command center user/org/role management\
[Dashboard(to be deprecated)](https://github.com/pagerinc/web-dashboard): This product contains two core functionalities. 1) Old admin tool for command center user management. This functionality will eventually be moved to Enterprise Admin and deprecated in Dashboard, 2) Repository for patient chat history and patient information\
[SDK Core](https://github.com/pagerinc/web-sdk-core): Headless JS library for Pager\
[Web Widget](https://github.com/pagerinc/web-sdk-widget): The web widget UI client for Pager, using the Pager SDK Core\
[Pager UI Kit](https://github.com/pagerinc/pager-ui-kit): Reusable component library, consumed primarily by Enterprise Admin

All frontend repos are prefixed with `web`. Ancillary repos supporting our main products and documentation can be found within Pager github by searching the keyword ‘Web’. If you have any questions about a specific app, you can reach out to the owner of the app listed here. 

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
Follow instructions in the invitation email to set up your password. Please make sure to set up two-factor authentication.

**NewRelic:** <https://login.newrelic.com/>\
Follow instructions in the invitation email to set up your password.

**SumoLogic:** <https://service.sumologic.com/ui/>\
Follow instructions in the invitation email to set up your password. Please make sure to set up two factor authentication.

**MixPanel:** <https://mixpanel.com/>\
Follow instructions in the invitation email to set up your password.

### Slack Channels
At Pager, we use Slack as our instant messaging communications tool. There are a number of slack channels designated for specific purposes, including but not limited to the following: 

**`web-chapter`:** 
Channel dedicated to all things web-related. All web teams utilize this channel for news, posting Pull Requests for review, etc.

**`general`:**
Miscellaneous channel for sharing general announcements, non-work related posts, articles, memes, or other fun or informative topics not related to any specific area of Pager.

**`squad-{{team name here}}`:**
All teams have their own slack channels for sharing team related communication, meeting invites, news, etc. that start with the word "squad" followed by a hyphen and the team name. 

**`skunkworks`:**
Channel dedicated to the platform team and things related to Pager's build processes and CI/CD tools.

**`nyc-office`:**
Channel dedicated to discussing all things related to Pager's NYC office, including office news, events, closures, building maintenance items, and other information relevant to onsite employees in NYC.

**`engineering-product`:**
Channel for general announcements for the engineering and product teams. This is where work from home requests and other availability notifications are communicated to the team at large. 

**`mayday`:**
Channel where incidents from Sentry and PagerDuty are posted to track escalation and resolution.

**`product-bugs`:**
Channel to post and track production bugs

**`random`:**
Channel to post random things!

**`eng-war-room`:**
Channel used to post critical emergencies and other urgent communication. Team members should have alerts for this channel on at all times.

### Command Center Environment URLs
There are various levels of environments used in Pager for development, testing, and production. The environment levels, from lowest to highest, are qa, staging, and production. There are also three different client versions of the site dependent on which client the site is being used for, each having their own abbreviation. Sura is abbreviated as "sra", Horizon as "hrz", and a multi-tenant client abbreviated "pgr". Pgr is a generic version used by a variety of clients. The url structure for each of these environments are as follows: 

**LL (Lower Level Environments) - QA and Staging**
{{client abbreviation}}-{{environment level}}-command-center.pagerinc.com
- e.g: 
    - https://pgr-stage-command-center.pagerinc.com/
    - https://hrz-stage-command-center.pagerinc.com/

**Production Level URLs**
- https://sra-command-center.pager.com/
- https://command-center.pager.com/
- https://hrz-command-center.pager.com/
- https://pgr-rr-command-center.pager.com/

**Confluence**
- [This gathers information](https://pagerinc.atlassian.net/wiki/spaces/PRODUCT/pages/605421622/Hands+on+Pager+s+product) on how to install and use several parts of Pager’s product.

### Front End Development and QA Workflow
For any Frontend user story being worked on, the engineer needs to make a local branch off of the `develop` branch. Branch names related to JIRA tickets should use the following naming convention: {{Story number}}_{{short description}} (i.e. UE-932_refactor). All changes should be made on a local branch and then committed to their remote branch on github. Then, a Pull Request should be made, which will trigger the CI/CD checks to run. PR links should be posted in the `#web-chapter` slack channel for review. Once the appropriate amount of approvals is given, and the CI/CD checks pass, QA should be notified that the story pertaining to the PR is ready to test. Requests for testing should be posted in the #squad-qa slack channel. Once the story passes QA, the PR is ready to be merged into the `develop` branch.

### System requirements to start the development server

1. [Node.js](https://nodejs.org/) (version >= 10.0.0 && <= 12.16.2). It’s recommend the use of [nvm](https://github.com/nvm-sh/nvm)

2. Inside your code editor:
- [ESLint](https://eslint.org/)
- [Prettier](https://prettier.io/)

### Documentation
Below you will find documentation that will help you gain quicker understanding about Pager, and how things are organized. If you have any questions, comments, or ideas please feel free to comment on the confluence documents, this will help us make the documentation better!

**Frontend specific:**
- [Gitflow overview, sprint cycle and sprint planning philosophy](https://pagerinc.atlassian.net/wiki/spaces/EN/pages/280100901/Web+Team+Information)
- [How to release code](https://pagerinc.atlassian.net/wiki/spaces/EN/pages/280068238/How+to+release+code+-+Frontend+Web+deployment+process): frontend specific release process
- [How to publish & access privately scoped modules](https://pagerinc.atlassian.net/wiki/spaces/EN/pages/140935943/How+to+publish+access+privately+scoped+modules): Guideline to publish the latest code to npm
- [Folder for all architecture decisions (RFCs)](https://pagerinc.atlassian.net/wiki/spaces/EN/pages/245399689/Architecture+Design+Decisions)
- [How to set up the local environment](https://pagerinc.atlassian.net/wiki/spaces/EN/pages/650477570/How+to+set+up+the+local+environment)

**Non frontend specific:**
- [Release management](https://pagerinc.atlassian.net/wiki/spaces/EN/pages/227180588/Release+Management): overview of Pager’s release process
- [Tech talks and training](https://pagerinc.atlassian.net/wiki/spaces/EN/pages/161579009/Tech+Talks+and+Trainings): various tech talks, and training materials
- Environments and logins: documents containing links to various qa and staging environments, along with login information.
  - https://docs.google.com/spreadsheets/d/1rfgglp1RsgLZktJNXWiuAD2om0yjdva8S_KZvZu2F6E/
  - https://docs.google.com/spreadsheets/d/1K8Jcpuy5c7-GK1Zr0kdk3AUdKCZby4_pEu7cK3pxlcA/
  - https://docs.google.com/spreadsheets/d/1IxwdVQ4s799EqBr6TEN91OX8QtPcPmtqeCnneQ1Yx4s/
- [Backend dev process](https://pagerinc.atlassian.net/wiki/spaces/EN/pages/101515522/Backend+Development+process): a lightweight document outlining the basics of the backend development process, branching and forking strategy and RFC process.
- [Tips on tickets and tasks](https://pagerinc.atlassian.net/wiki/spaces/EN/pages/154435585/Ticket+Creation+Process): some helpful tips about ticket creation and estimation

### What to expect and accomplish during first week

Starting a new job can be filled with the feeling of uncertainty. Below checklist is aimed at guiding you through your first week at Pager, and helping you keep track of all the things that need to happen during this important period. 

**General meetings:**
- [ ] IT Orientation with Erika Williams
- [ ] Security Orientation with Alexander Miller
- [ ] Pager Orientation with Ryon Burell 

**Frontend specific meetings:**
- [ ] Meet your Manager
- [ ] Meet your Coding Buddy
- [ ] Command Center shadowing
- [ ] Partake in web-weekly and demo (Friday 11:30am - 12:30pm EST)
- [ ] End of the first week meeting with your manager

**Non-frontend specific meetings:**
- [ ] Platform overview with Jeremiah Bowen [self-scheduled]
- [ ] Application architecture overview with Ryan Hall [self-scheduled]
- [ ] Mobile applications overview with Fabian Celdeiro [self-scheduled]
- [ ] Introduction to QA Team with Jesmin Aktar [self-scheduled]
- [ ] Sprint Planning meeting
- [ ] Sprint Retrospective meeting

**Action items:**
- [ ] Set up NPM account and get access to Pager org.
- [ ] Set up local environments
- [ ] Get access to (ask any manager in Engineering):
    - [ ] Jira
    - [ ] GitHub
    - [ ] GoogleCloud dashboard (Terraform managed, create a PR [forking the repo], adding your email to the right team [here](https://github.com/pagerinc/infra/blob/master/modules/teams/main.tf))
    - [ ] Sentry
    - [ ] NewRelic
    - [ ] SumoLogic
    - [ ] MixPanel
- [ ] Review frontend specific documentation
- [ ] Download example pager app on your device (Reach out to mobile lead Fabian Celdeiro for instructions)
- [ ] Compile a document with questions that you have
- [ ] Make an improvement to the onboarding documentation
- [ ] Join the following Slack channels:
    - [ ] `#web-chapter` (private, ask to be invited)
    - [ ] `#squad-{{your squad's name}}` (i.e. #squad-users-enterprise)
    - [ ] `#eng-war-room` (private, ask to be invited)
    - [ ] `#skunkworks`
    - [ ] `#product-bugs`
    - [ ] `#engineering`
    - [ ] `#engineering-product` (private, ask to be invited)
    - [ ] `#releases`

We are excited that you are joining our team, and wish to provide you with an easy and productive onboarding experience. Should you encounter any questions or difficulties at any time, do not hesitate to reach out to your direct manager or designated coding buddy. We are here to help!

Welcome to Pager!
