## 1. Project / Area root file

Root files are named as the project they represent, and they contain embedded views of project/area .base file. Every base file has 3 views:
1. Team:
	1. People (notes placed in `070 - People/items`)
	2. With links to this project root file
2. Task:
	1. Tasks (notes placed in `040 - Tasks/items`)
	2. With links to this project root file
3. Meetings:
	1. Meetings (notes placed in `060 - Meetings/items`)
	2. With links to this project root file

---

![[ISciq6We93.png]]

---

![[Hujyek3req.png]]

## 2. Quick add notes from embedded view

Native base embeddings provide a useful `+ New` button. Using it you don't need to place tasks, people, or meetings in the right folder (respective items folder). By using this button, you only need to set project link and status and that's all! It seems especially useful in daily notes.

![[ZjnQElj9cS.png]]

## 3. Daily meetings

By using a custom filter code, you can match all meetings where their `scheduled` property (which is a date) is equal to a note title (which is daily notes syntax). Since this view is part of Meetings base file and it's included in daily notes template, it's easy to have a view of meetings scheduled for today.

![[7Jaayb3wl7.png]]
