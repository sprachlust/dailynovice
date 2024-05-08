


```dataview
TABLE dateformat(file.mtime, "yyyy.MM.dd HH:mm") AS "Last modified"
FROM "/content" SORT file.mtime DESC LIMIT 10
```
