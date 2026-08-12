---
tags: dataview
---
```dataview
TABLE 
    item_use AS "Use", 
    future_plan AS "Future Plan", 
    when_to_do AS "When",
    status AS "Status"
FROM "00 Notes" AND #inbox-item 
WHERE status != "Completed"
SORT when_to_do ASC
```
