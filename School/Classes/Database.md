```dataview
TABLE
Name as "Name",
Class as "Class",
Date as "Date",
Due-Date as "Due Date",
Tagged-Concepts as "Tags",
Description as "Descriptions"
FROM #class-material WHERE Name != "{{title}}"
```