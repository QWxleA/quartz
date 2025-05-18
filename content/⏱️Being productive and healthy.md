---
title: Being productive and healthy
type: moc
tags:
  - productivity
  - type/moc
public: true
---
This is an index related to human behavior and how we have much less of a free will then we take for granted

**Measured productivity**
 - [[it is easy to think we are productive, but it is hard to measure oneself]]
	- [[🌱 multi-tasking does not lead to increased productivity]]

**workflow**
- [[A fitting work environment will enhance productivity]]
	- [[Defining satisfactory workflows reduce stress and increase productivity]]

**Goals**
- [[Avoid ill-defined goals, instead focus on flexible projects]]


--- 

## Misc

```dataview
table file.title as "Title", file.mtime as "Modified"
from #productivity 
where type
sort file.ctime desc
```

```dataview
TABLE WITHOUT ID file.link AS "Incoming Links", date 

WHERE contains(this.file.inlinks, file.link)
SORT date desc
```