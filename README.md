# LoLs
List of Lists

# lols.yml
This is a configuration of where the list of lists happen. It's faily simple.

```
---
lists:
  "Topic One":
    Statistics:
      Created: 123456
    "Item One":
      Created: 123456
      Completed: 123456
    "Item Two":
      Created: 123456
  "Topic Two":
    Statistics:
      Created: 123456
      Completed: 123456
    "Item One":
      Created: 123456
      Completed: 123456
    "Item Two":
      Created: 123456
```

list -> topic -> Statistics is not an item and part of the list but timestamped references to determine when the list is created and completed.

# Front End
Whatever is created should display the lists, allow a list to be created, and allow CRUD actiosn on the list in the list of lists.
