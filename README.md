# tracker-stacker

Define & track agile projects.

This repo currently contains a summary of search for existing solution; next steps are to consider whether to develop a webapp to meet some/all of the critical needs.

Desired benefit: An integrated solution that covers all critical aspects of defining & tracking requirements. Most promising proposal so far is to use 'glue code' & apis to combine existing services & fill the existing gaps between them. Ultimately we hope for a tool that allows all stakeholders in a given agile project to collaborate extensively.

Note that Jira already offers a lot of the desired benefits. Top reasons Jira is not already the selected solution:
- difficulty setting it up
- difficulty adjusting it as need/understanding changes
- difficulty onboarding new people
- difficulty using it, even for experienced people.

## summary of preliminary findings

To date ... Through the testing of multiple time-tracking[note_f] solutions, frustrations continually surfaced as none seemed to fully meet the business requirements of agile practices. Shortcomings were regularly discovered, & stop-gap measures were implemented to continue effectively using the platforms. In order to get a clearly-defined sense of ongoing business operations, the integration of multiple solutions was required. With each aditional implementation, the fragility of the integration rose. Eventually, more effort was spent on bridging the gaps rather than using the software to gain valuable insights.

[note_f] would 'supply chain management' be a more accurate term for the total effort? Is there an even more generic-yet-accurate term?

[purpose of this section] this piece is intended eventually to help other firms decide whether their needs match those of the group & whether they'd want to get the benefits of joining the development team

style: give yourself credit for your efforts to date vs using passive constructions

## breakout of key requirements

This list currently serves as a ['straw man proposal'](https://en.wikipedia.org/wiki/Straw_man_proposal) ("a brainstormed simple draft proposal intended to generate discussion of its disadvantages and to provoke the generation of new and better proposals.")

### Define project scope collaboratively, present it for input & manage changes
Collect initial input from stakeholders.
Use templates so best practices easy to follow for people who are not web professionals.

_existing services: (Trello, Asana, ...)_

Preliminary list of stakeholders
- project owners
- design team
- implementation team
- testing team
- editorial team
- documentation team
- maintenance team
- infrastructure team
- other (authenticated) consumers of selected pieces of information

### Define & track budget use; manage changes

_existing services: (Freshbooks, Harvest, Jira, Zoho, ...)_

- include budget tracked on various platforms
- understand budget specifics at a glance, especially
  - overall budget vs percent of work complete vs budget spent
  - line-item budget allocated vs progress on tasks vs budget spent

### Define & track tasks

_existing services: (Jira, Asana, Trello, ...)_

- prioritize/reallocate efforts
  - line items completed & in progress
  - status of unfininshed line items

### Track & pay invoices

_existing services: (Freshbooks, Harvest, Zoho, ...)_

Separate 'portals' for invoice management between each 'layer' of budget owner and serivce provider:
- client & prime contractor
- prime contractor & employees
- prime contractor & subcontractors
- any of the above and "pass through" service providers

Details to manage
- % spent on project, % invoiced, % paid
- description of completed efforts
- acceptance/rejection of completed efforts

Ability to preserve connection to information from teams/vendors and information shared in client-ready format (e.g. audience-appropriate display modes of different details on each entity)
