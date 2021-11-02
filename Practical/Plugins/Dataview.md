A way to query your vault for things!

```dataview
list from #coolStuff
```


# Not just lists!
```dataview
table coolness FROM #coolStuff and !"SomeNotes/Archive" 
sort coolness asc
```

*This is a table with properties that are exposed to Dataview. It can sort things and exclude things. Wowzo!*