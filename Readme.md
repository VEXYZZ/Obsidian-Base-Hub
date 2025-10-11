---
version: 2.0.1
---
---

This example Vault was created by [[Rafa Campos]], using the KISS principle.

## Objective

All components have been created to facilitate work management in projects with complicated and/or changing environments. 

> It is not a team management tool, only for managing your own work.

## Components

- [[ℹ️ Inbox]] manager, for disordered notes that are taken quickly, with the idea that they will be processed into the rest of the components sooner or later
- Data manager:
	- [[ℹ️ People]]: Documents work relationships and colleagues
	- [[ℹ️ Meetings]]: Facilitates note-taking and meeting organization
	- [[ℹ️ Diary]]: Facilitates control of daily work and progress made
- Work manager:
	- [[ℹ️ Tasks]]: Documents work in minimum units called tasks. Tasks have global statuses, which indicate their level of progress.
- Development control
	- [[ℹ️ Projects]]: Control of work in developments with a beginning and an end
	- [[ℹ️ Areas]]: Control of work in permanent developments
	- Each project and area has its own database to document tasks, team and meetings, so that information is centralized without repeating the contents

## How to use

1. Register your projects and areas following the steps indicated in [[ℹ️ Projects]] and [[ℹ️ Areas]]. 
2. Complete your people database in [[ℹ️ People]]
3. Every day, generate a daily note using the Obsidian functionality and apply the daily note template
	1. Go to Settings > Templates
	2. Set the path of the `999 - Templates` folder as the template directory
		1. When you create Meetings or People, use the appropriate templates by using the "Insert template" button in the side menu with the 📄 icon
		2. Modify these templates over time to adapt them to your case
	3. Go to Settings > Daily notes
		1. Configure the location of the new file in `050 - Dialy / Items`
		2. Configure the location of the base template as `999 - Dialy note
4. Add custom properties for your work context
5. Contact [[Rafa Campos]] to request or share possible improvements