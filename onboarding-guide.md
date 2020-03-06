# Onboarding Handbook

### Welcome & Introductions

We would like to welcome you to Pager Inc. The purpose of this Onboarding handbook is to provide you with comprehensive guidance and direction during your onboarding, familiarize you with Pager Inc. systems, designate a coding buddy, and generally set you up for success.

### Team Structure at Pager

Pager engineering consists of five squads, most of them specializing in a different Pager product: 
Enterprise Users (UE) - Command Center
Enterprise Management (ME) - Enterprise Admin
Consumer (CS) - Mobile/Web SDK
Professional Services Squad (PSS) - Client liaison & client feature development
Platform (PS) - Infrastructure

With the exception of platform squad, each squad contains engineers from frontend (web and/or mobile), backend, machine learning/data as well as QA. Here is the [org chart](https://docs.google.com/drawings/d/14hRZNhhM9m**t88lR9jOoqDkvewiQDf3Rc0wW7n3iyDI/edit) for our squads. 
If interested, see [this medium article](https://medium.com/scaled-agile-framework/exploring-key-elements-of-spotifys-agile-scaling-model-471d2a23d7ea) for more information about squad structure. 

During your first week, you will be meeting your team members, as well as team leads, who will provide you with important overview of their respective areas of expertise. 

**Coding Buddy:** [Insert name]
One of the key figures during your first few weeks is your coding buddy. Your coding buddy will be your initial source of information about various systems, tools and practices at Pager. In addition to being your go-to person for code related questions, you can expect your coding buddy to help you pick up your first coding assignments. This will help you dive into coding as quickly as possible, without overwhelming you.

**Your Direct Manager:** [Insert name]
Your manager will meet with you on your first day to welcome you to Pager, get to know you, understand your personal and professional goals. The purpose of the first meeting is to introduce you to this document, and set initial expectations. You will have a second meeting with your manager at the end of your first week, to check-in on your onboarding progress and introduce you to your 30-60-90 day plan.


**Frontend Lead:** Mi Ji Kim
Mi Ji will introduce you to our frontend code, talk about applications such as Command Center and Enterprise Admin. This is an opportunity for you to better understand one of the central applications of our ecosystem and how it ties in with the various backend services. 

**Backend Leads:** Ryan Hall (ME), Elba Sanchez (CS), Diego Baquero (UE), Jugal Shah (PSS)
Ryan will provide you with an overview of our application architecture, introduce you to various aspects of our microservices, and talk about the architectural vision and direction we would like to move towards. 

**Mobile Lead:** Fabian Celdeiro
Fabian will provide you with an overview of Android and iOS applications, as well as help you understand how to install a test application, how to login and test.

**Platform Lead:** Jeremiah Bowen
Jeremiah will provide you with a high level overview of Pager’s infrastructure, environments and platform tools as they pertain to software engineering. This is a great opportunity for you to understand the operational environment that you will be placed in.

**QA Manager:** Jesmin Aktar
Jesmin will introduce you to her team members, as well as go over the QA process. This is an excellent opportunity to make some friends in the QA team. 

**Director of engineering:** Shay Weiss
Introductory meeting with Shay Weis. Shay will provide you with information about engineering vision and get to know you a little better.

### Frontend Repositories

Main frontend product repos:
[Command Center](https://github.com/pagerinc/web-command-center): Chat application that allows clinical and non-clinical staffs to chat with patients
[Enterprise Admin](https://github.com/pagerinc/enterprise-admin): Admin tool for command center user/org/role management
[Dashboard(to be deprecated)](https://github.com/pagerinc/web-dashboard): This product contains two core functionalities. 1) Old admin tool for command center user management. This functionality will eventually be moved to Enterprise Admin and deprecated in dashboard, 2) Repository for patient chat history and patient information
[SDK Core](https://github.com/pagerinc/web-sdk-core): Headless JS library for Pager
[Web Widget](https://github.com/pagerinc/web-sdk-widget): The web widget UI client for Pager, using the Pager SDK Core
[Pager UI Kit](https://github.com/pagerinc/pager-ui-kit): Reusable component library, consumed primarily by Enterprise Admin

All frontend repos are prefixed with Web. Ancillary repos supporting our main products and documentation can be found within Pager github by searching the keyword ‘Web’. If you have any quesitons about a specific app, you can reach out to the owner of the app listed here. 

### Tools and Processes

At pager we use a number of tools that help us keep track of our work, documentation, application metrics and logs. This section lists those tools, and how to access them.

Please make sure to enable 2FA where available.
Tools
**Jira and Confluence:** <https://pagerinc.atlassian.net> 
Use your Pager gmail account to login.

**GoogleCloud Dashboard:** <https://console.cloud.google.com> 
Use your Pager gmail account to login.

**Sentry:** <https://sentry.pager.com/auth/login/pager/>
Follow instructions in the invitation email to set up your password. Please make sure to set up two factor authentication.

**NewRelic:** <https://login.newrelic.com/>
Follow instructions in the invitation email to set up your password.

**SumoLogic:** <https://service.sumologic.com/ui/>
Follow instructions in the invitation email to set up your password. Please make sure to set up two factor authentication.

**MixPanel:** <https://mixpanel.com/>
Follow instructions in the invitation email to set up your password.

**PagerDuty:** <https://pagerinc.pagerduty.com/>
Use your Pager credentials to login.

**Github:** <https://github.com>
You will need to create a new github account tied to your pager.com email.

### Documentation
Below you will find documentation that will help you gain quicker understanding about Pager, and how things are organized. If you have any questions, comments, or ideas please feel free to comment on the confluence documents, this will help us make the documentation better!

**Frontend specific:**
[Gitflow overview, sprint cycle and sprint planning philosophy](https://pagerinc.atlassian.net/wiki/spaces/EN/pages/280100901/Web+Team+Information)
[How to release code](https://pagerinc.atlassian.net/wiki/spaces/EN/pages/280068238/How+to+release+code+-+Frontend+Web+deployment+process): frontend specific release process 
[How to publish & access privately scoped modules](https://pagerinc.atlassian.net/wiki/spaces/EN/pages/140935943/How+to+publish+access+privately+scoped+modules): Guideline to publish latest code to npm
[Folder for all architecture decisions (RFCs)](https://pagerinc.atlassian.net/wiki/spaces/EN/pages/245399689/Architecture+Design+Decisions)

**Non frontend specific:**
[Release management](https://pagerinc.atlassian.net/wiki/spaces/EN/pages/227180588/Release+Management): overview of Pager’s release process
[Tech talks and training](https://pagerinc.atlassian.net/wiki/spaces/EN/pages/161579009/Tech+Talks+and+Trainings): various tech talks, and training materials
[Environments and logins](https://docs.google.com/spreadsheets/d/1rfgglp1RsgLZktJNXWiuAD2om0yjdva8S**KZvZu2F6E/edit#gid=1177611621): a document containing links to various qa and staging environments, along with login information.
[Backend dev process](https://pagerinc.atlassian.net/wiki/spaces/EN/pages/101515522/Backend+Development+process): lightweight document outlining the basics of the the backend development process, branching and forking strategy and RFC process.
[Tips on tickets and tasks](https://pagerinc.atlassian.net/wiki/spaces/EN/pages/154435585/Ticket+Creation+Process): some helpful tips about ticket creation and estimation

### What to expect and accomplish during first week

Starting a new job can be filled with the feeling of uncertainty. Below checklist is aimed at guiding you through your first week at Pager, and helping you keep track of all the things that need to happen during this important period. 

**General meetings:**
IT Orientation with Mike Bogart
Security Orientation with Alexander Miller
Pager Orientation with Ryon Burell 

**Frontend specific meetings:**
Meet your Manager
Meet your Coding Buddy
Command Center shadowing
Partake in web-weekly and demo (Friday 11am - 12pm)
End of the first week meeting with your manager

**Non-frontend specific meetings:**
Platform overview with Jeremiah Bowen [self-scheduled]
Application architecture overview with Ryan Hall [self-scheduled]
Mobile applications overview with Fabian Celdeiro [self-scheduled]
Introduction to QA Team with Jesmin Aktar [self-scheduled]
Sprint Planning meeting
Sprint Retrospective meeting

**Action items:**
Set up NPM account and get access to Pager org.
Set up local environments
Get access to:
Jira
GitHub
GoogleCloud dashboard (Terraform managed, at least `Viewer` role)
Sentry
NewRelic
SumoLogic
MixPanel
PagerDuty (Terraform managed)
Review frontend specific documentation
Download example pager app on your device
Compile a document with questions that you have
Make an improvement to the onboarding documentation

We are excited that you are joining our team, and wish to provide you with an easy and productive onboarding experience. Should you encounter any questions or difficulties at any time, do not hesitate to reach out to your direct manager or designated coding buddy. We are here to help!

Welcome to Pager!




