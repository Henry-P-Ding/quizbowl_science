# Random Answer Lines
```dataview 
TABLE WITHOUT ID answers
where answers
FLATTEN date(now) as Now
FLATTEN (file.mtime.year + file.mtime.hour + file.mtime.day + 
	     file.mtime.hour + file.mtime.minute + file.mtime.second + 
	     file.size + Now.hour + Now.minute + Now.second) * 15485863 
	     as Hash
FLATTEN ((Hash * Hash * Hash) % 2038074743) / 2038074743 as Rand
SORT Rand
LIMIT 20
```
# All Answer Lines
```dataview
TABLE WITHOUT ID answers
where answers
SORT answers ASC
```