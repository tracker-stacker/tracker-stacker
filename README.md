# tracker-stacker

Define and track agile projects.

This repo currently summarizes search for existing solution and considers whether parts/all of the critical needs warrant more webapp development.

## summary of preliminary findings

Objective: define and track agile projects

Benefit: An integrated solution that covers all critical aspects of definition & tracking requirements. Most promising proposal so far is to use 'glue code' and apis to combine existing services and fill the existing gaps between them.

To date ... Through the testing of multiple time-tracking[note_f] solutions, frustrations continually surfaced as none seemed to fully meet the business requirements of agile practices. Shortcomings were regularly discovered, and stop-gap measures were implemented to continue effectively using the platforms. In order to get a clearly-defined sense of ongoing business operations, the integration of multiple solutions was required. With each aditional implementation, the fragility of the integration rose. Eventually, more effort was spent on bridging the gaps rather than using the software to gain valuable insights.

-----------------

## solution requirements

Defining & tracking project scope
- collect input from stakeholders using templates (objective: make best practices easy to follow for people who are not web professionals)
  -- project owners
	-- design team
	-- implementation team
	-- testing team
	-- editorial team
	--
Defining & tracking project budget
- include time tracked on other platforms
- realtime budget management
	-- understand overall budget vs spent at a glance
	-- understand line-item budget allocated vs spent at a glance
- project management
	-- prioritize/reallocate efforts
	-- understand time reported vs progress on tasks vs time budgeted
	-- actual time spent on line items vs budgeted time for line items
	-- vendor effort and time management
- project tracking needs
	-- overview of project progress against budget
	-- line items completed and in progress
	-- status of unfininshed line items
	-- % spent on project, % invoiced to client, % collecsted
	-- description of completed efforts
- ability to export costs into clinet-ready invoice

[note_f] would 'supply chain management' be a more accurate term for the total effort? Is there an even more generic-yet-accurate term?

objective: this piece is intended eventually to help other firms decide whether their needs match those of the group and whether they'd want to get the benefits of joining the development team

style: give yourself credit for your efforts to date vs using passive constructions
