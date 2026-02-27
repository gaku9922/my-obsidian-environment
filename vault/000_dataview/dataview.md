## All docs

```dataview
TABLE
	tags AS "tags",
	updated AS "updated"
FROM "" AND -"999_templates" AND -"999_assets" AND -"001_daily"
WHERE tags AND updated
SORT updated DESC
LIMIT 100
```
