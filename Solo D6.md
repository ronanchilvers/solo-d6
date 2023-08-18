---
created: 2023-07-07 11:29
---
![[Tiny Dungeon 2e - Banner.jpg]]

> [!abstract]- Adventure Seed
> An artifact has been stolen from a merchant in the Trade Ward. Their potential employer, a human
> merchant named [[Lina Devdan]] has asked to meet them to discuss the matter. They have two
> leads:
> - A scrap of skin from some unknown creature
> - A small wooden box (with a secret compartment)
> 
> These were found after the robbery took place.

# Maps
```dataview
List 
From -"_templates"
Where contains(file.tags, "map")
Sort file.name
```

# Scenes
```button
name Create new scene
type command
action Quickadd: New Scene
```
^button-new-scene
```dataview
List
From -"_templates"
Where contains(file.tags, "scene") 
Sort file.name desc
```

# Characters
```dataview
List 
From -"_templates"
Where contains(file.tags, "character")
Sort file.name
```

# Setting
```dataview
List 
From -"_templates"
Where contains(file.tags, "setting")
Sort file.name
```

# Mechanics
```dataview
List
From -"_templates"
Where contains(file.tags, "mechanics") 
Sort file.name
```

# Creatures
```dataview
List
From -"_templates"
Where contains(file.tags, "creature") 
Sort file.name
```

# Places
```dataview
List 
From -"_templates"
Where contains(file.tags, "place")
Sort file.name
```