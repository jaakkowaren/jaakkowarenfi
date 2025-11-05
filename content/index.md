---
title: Welcome!
---
This is page mostly for me at this point, but you are free to look around.


<!-- QueryToSerialize: TABLE 
author,("![coverimg|95](" + cover +")") as Cover
FROM #moc/book

WHERE !contains(file.path, "99 admin/")

AND !contains(file.path, "00 Home/")

SORT file.name DESC 
-->






```dataview

TABLE 
author,("![coverimg|95](" + cover +")") as Cover
FROM #moc/book

WHERE !contains(file.path, "99 admin/")

AND !contains(file.path, "00 Home/")

SORT file.name DESC

```
