---
uid: {{date:YYYYMMDD000000}}
title: 📆{{date:YYYY-MM-DD}}
date: {{date:YYYY-MM-DD 00:00:00}}
update: {{date:YYYY-MM-DD HH:mm:ss}}
tags: 
  - "#📆yyyy-mm/{{date:YYYY-MM}}"
draft: false
publish: false
note_type:
  - "daily note"
---

## MOC

- [📆{{date:YYYY-MM}}]({{date:YYYYMM00000000}}.md)

## Daily

## Dataview

```dataview
TABLE WITHOUT ID link(file.link, title) AS "Title" ,date
FROM "000_zettelkasten"
WHERE file.day >= date({{date:YYYY-MM-DD}}) AND file.day <=date({{date:YYYY-MM-DD}})
SORT title desc
```
