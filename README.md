# Onboarding Handbook

### Welcome & Introductions

We would like to welcome you to Pager Inc. The purpose of this onboarding handbook is to provide you with comprehensive guidance and direction during your onboarding, familiarize you with Pager Inc. systems, designate a coding buddy, and generally set you up for success.

The onboarding handbook is split by domain:
 - [Backend](backend/README.md)
 - [Frontend](frontend/README.md)

### Here's the common ones

 ### Documentation
Below you will find documentation that will help you gain quicker understanding about Pager, and how things are organized. If you have any questions, comments, or ideas please feel free to comment on the confluence documents, this will help us make the documentation better!

- [Pager Technology Overview](https://docs.google.com/presentation/d/1cPI4CoKAFByFV_KG2-F-eg1F6ZytK9iSaeSYDPL4Y6w) Overview of all Pager's engineering organization and technology
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

**Meetings:**
- [ ] IT Orientation with Erika Williams
- [ ] Security Orientation with Alexander Miller
- [ ] Pager Orientation with Ryon Burell
- [ ] Meet your Manager
- [ ] Meet your Coding Buddy
- [ ] Command Center shadowing
- [ ] Partake in chapter weekly and demo (if your chapter has demo)
- [ ] End of the first week meeting with your manager
- [ ] Platform overview with Jeremiah Bowen [self-scheduled]
- [ ] Application architecture overview with Ryan Hall [self-scheduled]
- [ ] Mobile applications overview with Fabian Celdeiro [Video](https://drive.google.com/file/d/1-JCXO_VoilM6r5UomoRJ67c71LsbLI57/view?usp=sharing)
- [ ] Introduction to QA Team with Jesmin Aktar [self-scheduled]
- [ ] Sprint Planning meeting
- [ ] Sprint Retrospective meeting

**Action items:**
- [ ] Set up NPM account and get access to Pager org (enable 2FA for Authorization and Publishing).
- [ ] Set up local environments
- [ ] Get access to (ask any manager in Engineering):
    - [ ] Jira
    - [ ] Greenhouse
    - [ ] GitHub
    - [ ] GoogleCloud dashboard (Terraform managed, create a PR [forking the repo], adding your email to the right team [here](https://github.com/pagerinc/infra/blob/d6da5570959a23a27fec32d22a17bd8387a8c67d/modules/teams/main.tf))
    - [ ] Sentry
    - [ ] NewRelic
    - [ ] SumoLogic
    - [ ] MixPanel
- [ ] Compile a document with questions that you have
- [ ] Make an improvement to the onboarding documentation
- [ ] Join the following Slack channels:
    - [ ] #chapter-{{your chapter name}} (i.e. #squad-web)
    - [ ] #squad-{{your squad's name}} (i.e. #squad-consumer)
    - [ ] #squad-mayday-{{your squad's name}} (i.e. #squad-mayday-consumer)
    - [ ] #eng-war-room
    - [ ] #skunkworks
    - [ ] #product-bugs
    - [ ] #eng-announcements
    - [ ] #engineering
    - [ ] #engineering-product
    - [ ] #status
    - [ ] #releases
    - [ ] #nyc-office
- [ ] Get yourself familiar with the high level architecture: https://whimsical.com/SB3cDuYsM689yMYNoTpGF2
- [ ] Make your Google Calendar visible to all colleagues: https://support.google.com/calendar/answer/37082?visit_id=637257138637539347-1003588718&rd=1


**Expectations for the first a couple months:**

- [ ] Get access to the demo app in first 2 weeks (Reach out to mobile lead Fabian Celdeiro for instructions)
- [ ] Get admin and non-admin CC user in all LL environments in the first two weeks.
- [ ] Do a 10 minute product demo to Lead/Manager (able to join a chat as a consumer from the demo app or WebSDK, able to pick up the chat as an Enterprise User, able to explain the UI for Enterprise user (scripts, recommendations, video chat).Tip: Record for yourself for future reference.
- [ ] Shadowing an interview in the first 30-60 days (or earliest opportunity possible if we’re not hiring for the chapter) [Non Jrs]
- [ ] Present something you’ve done in squad Demos after at least 2 full sprint demos from joining
- [ ] Fix at least one Critical bug and release to Production in first 60 days
- [ ] Sentry error fix in the first 60 days
- [ ] Release captain in first 60 days
