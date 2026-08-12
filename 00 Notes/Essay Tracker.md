---
tags:
  - review
  - flashcards
created: 2026-06-12
updated: 2026-06-12 15:22
sr-due: 2026-09-22
sr-interval: 78
sr-ease: 310
---
# Essay Tracker

[[Essay Dataview Guide]]

## Essays
```dataview
TABLE 
  type AS "Type",
  source_material AS "Source",
  word_count AS "Word Count",
  time_taken AS "Time",
  round(word_count / time_taken,1) AS "WPM",
  medium AS "Medium"
FROM #essay and "00 Notes"
SORT file.ctime DESC
```


## Progress


```dataview
TABLE WITHOUT ID
  created as "Date",
  word_count AS "Word Count",
  time_taken AS "Time",
  round(word_count / time_taken,1) AS "WPM",
  medium AS "Medium"
FROM #essay and "00 Notes"
SORT date ASC
```
## Progress (Only written essays)

```dataview
TABLE WITHOUT ID
  created as "Date",
  word_count AS "Word Count",
  time_taken AS "Time",
  round(word_count / time_taken,1) AS "WPM",
  medium AS "Medium"
FROM #essay and "00 Notes" and type = "long"
SORT date ASC
```
