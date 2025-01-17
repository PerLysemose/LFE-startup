# TSC Materials for [PROJECT NAME]

This directory contains the meeting notes, process documentations, and other materials related to this project.

## Project Intake checklist

This is a checklist for TSC's to review as part of the intake process. The TSC should review this entire list during the kickoff meeting. For anything outstanding, create an [issue](../issues) to track and link to it in the list

- [ ] Copy this checklist to a project specific location for tracking
- Acceptance Criteria
	- Have an open and documented technical governance, including:
		- [X] A [LICENSE](../LICENSE) file in every code repository, with the license chosen an [OSI-approved license](https://opensource.org/licenses).
		- [X] A [README](../README.md) file welcoming new community members to the project and explaining why the project is useful and how to get started.
		- [X] A [CONTRIBUTING](../CONTRIBUTING.md) file explaining to other developers and your community of users how to contribute to the project. The file should explain what types of contributions are needed and how the process works.
		- [ ] A CODEOWNERS or [COMMITTERS](../COMMITTERS.csv) file to define individuals or teams that are responsible for code in a repository; document current project owners and current and emeritus committers. 
		- [X] A [CODE_OF_CONDUCT](../CODE_OF_CONDUCT.md) file that sets the ground rules for participants’ behavior associated and helps to facilitate a friendly, welcoming environment. By default projects should leverage the Linux Foundation Code of Conduct unless an alternate Code of Conduct is approved prior.
		- [ ] A [RELEASE](../RELEASE.md) file that provides documentation on the release methodology, cadence, criteria, etc.
		- [_] A [GOVERNANCE](../GOVERNANCE.md) file that documents the project’s technical governance.
		- [ ] A [SUPPORT](../SUPPORT.md) file to let users and developers know about ways to get help with your project.
	- [ ] Complete and approve the [Technical Charter](CHARTER.md) and agree to transfer any relevant trademarks to The Linux Foundation or its affiliate, LF Projects, LLC, and to assist in filing for any relevant unregistered ones.
	- [ ] Submit a completed [Project Contribution Proposal](https://wiki.lfenergy.org/display/HOME/New+Project+Proposals+Process) to the TAC for consideration
	- [X] Schedule to present at an upcoming TAC meeting ( provide date ).
	- [X] Submit presentation to the TAC ( provide link to presentation ).
	- [X] Receive the affirmative majority vote of the TAC ( provide date ).
	- [_] Receive the affirmative majority vote of the Governing Board ( provide date ).
- New Project Intake
	- Establish TSC
		- [ ] Location for TSC documents and meeting notes ( recommendation is ```tsc``` directory in main repo, and then ```meetings``` under the ```tsc``` directory )
		- [ ] TSC members identified, added to [GOVERNANCE.md](../GOVERNANCE.md).
		- [X] First TSC meeting held ( [agenda](meetings/initial-meeting-agenda.md) )
		- [X] Elect TSC Chairperson
		- [X] TSC meeting cadence set and added to project calendar (https://lists.lfenergy.org/calendar)
	- [ ] Code scan completed and any recommendations remedyed ( details at https://wiki.lfenergy.org/display/HOME/The+Linux+Foundation+License+Scanning+and+Analysis+Support+Program+for+LF+projects ).
	- Infrastructure
		- [ ] Source Control (Github, GitLab, something else ) and LFE Staff is an administrator.	
			- [ ] Developer Certificate of Origin past commit signoff done and DCO Probot enabled.
		- [ ] Issue/feature tracker (JIRA, GitHub issues) and LFE Staff is an administrator.
		- Collaboration tools 
			- Mailing lists - one of ( refer to [guidelines](https://wiki.lfenergy.org/display/HOME/Project+Collaboration+Tools#ProjectCollaborationTools-Mailinglists): 
				- [ ] Create new list(s) ( default is -discussion@ and -private@ - create [service desk request] to provision ) 
				- [ ] Move to https://lists.lfenergy.org ( create [service desk request] to setup/transfer )
			- [ ] Establish project calendar on https://lists.lfenergy.org ( refer to [guidelines] (https://wiki.lfenergy.org/display/HOME/Project+Collaboration+Tools#ProjectCollaborationTools-Calendars) )
			- [ ] Slack or IRC ( create [service desk request] to setup Slack project channel - refer to [guidelines]( https://wiki.lfenergy.org/display/HOME/Project+Collaboration+Tools#ProjectCollaborationTools-Slack) )
		- [ ] Website ( if needed )
		- [ ] CI/build environment ( if needed )
		- [ ] Add project to [LFX Insights](https://insights.lfx.linuxfoundation.org/) ( create [service desk request] to trigger )
		- [ ] Add project to [LFX Security](https://security.lfx.linuxfoundation.org/) ( create [service desk request] to trigger )
	- Project assets
		- [ ] Domain name ( create [service desk request] to create/transfer )
		- [ ] Social media accounts ( create [service desk request] to setup/transfer - if needed )
		- [ ] Logo(s) ( create [service desk request] to create ); will be added to [artwork repo](https://artwork.lfenergy.org) in SVG and PNG format and color/black/white )
	- Outreach
		- [ ] New project annoucement done ( create [service desk request] to trigger )
		- [ ] Project added to LF Energy properties
			- [ ] Website ( https://lfenergy.org/projects )
			- [ ] LF Energy landscape ( https://l.lfenergy.org )
- Early Adoption requirements ( see https://wiki.lfenergy.org/display/HOME/Technical+Project+Lifecycle#TechnicalProjectLifecycle-EarlyAdoption )
  - Demonstrate growth in the project’s community, including
	- [ ] Growth in the number of commits to the project, number of project committers, and organizational diversity of contributions and committers.
	- [ ] Production or planned production use of the project by at least two independent end users which, in the TAC’s judgment, are of adequate quality and scope.
  - Technical Governance of the project is operational, as measured by:
	- [ ] A Technical Steering Committee with at least 5 members and a chairperson elected by the members, holding regular open meetings.
	- [ ] Achievement of the Core Infrastructure Initiative’s Best Practice badge at the ‘Passing’ Level ( apply at https://bestpractices.coreinfrastructure.org/en )
	- [ ] Development of a growth plan, to be done in conjunction with their project mentor(s) at the TAC. This plan should address the following points:
		- Release plans for the next 18 months.
		- Target end-users.
		- Identification of any regulatory or standards body requirements for deployment, and plans for implementation.
		- Plans for growth of project contributors and committers to support the growth plan.
			- Since these metrics can vary significantly depending on the type, scope and size of a project, the TAC has final judgement over the level of activity that is adequate to meet these criteria.
	- [ ] Identification of any infrastructure resources needed to fulfill the growth plan.
	- [ ] Prepare and schedule presentation to the TAC of the project’s growth, technical governance, and growth plan ( link to presentation deck )
	- [ ] Receive the affirmative majority vote of the TAC and Governing Board
- Graduated Project requirements
  	- [ ] Have a defined governing body of at least 5 or more members (owners and core maintainers), of which no more than 1/3 is affiliated with the same employer. In the case there are 5 governing members, 2 may be from the same employer.
	- [ ] Have fulfilled or are on track to complete the growth plan defined in the Early Adoption stage proposal.
	- [ ] Have a healthy number of contributions or committers from at least three organizations, with any one organization not composing more than 50% of the contributions or committers. Committers must be identified within the project in a COMMITTERS file.
	- [ ] Have a public list of project adopters for at least the primary repo (e.g., ADOPTERS.md or logos on the project website).
	- [ ] Achievement of the Core Infrastructure Initiative Best Practices badge at the Gold level.
	- [ ] Prepare and schedule presentation to the TAC on the fulfillment of these requirements ( provide link to presentation ).
	- [ ] Receive a ⅔ majority vote from the TAC a to move to Graduated stage ( provide date ).
	- [ ] Prepare and schedule presentation to the Governing Board on the fulfillment of these requirements ( provide link to presentation ).
	- [ ] Receive a majority vote of the Governing Board to move to Graduated stage ( provide date ).

[service desk request]: https://github.com/lf-energy/foundation/issues/new/choose
