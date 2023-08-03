```dataview
Table 
	file.folder as Folder,
	join(tags, ",") as Tags,
	gme as Emulator
From -"_templates"
Where file.name != "Index"
Sort file.folder
```