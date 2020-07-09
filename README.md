# hyperskill-SimpleSearchEngine
Developing a simple search engine to see if a query exists (or not) within a data set.  
https://hyperskill.org/projects/66

<img src="https://github.com/drtierney/hyperskill-SimpleSearchEngine/blob/master/SimpleSearchEngine.gif" width="800" height="500" />

## Syntax

| Arg | Valuelist | Comment
| --- | --------- | ------- |
| --data | `<string>` | Required<br>Filepath to datafile to be searched|

```
SimpleSearchEngine.jar --data "D:\temp\games.csv"
```

## Stages

**Stage #1 String theory**  
Set two strings (where to search and what to search) for the program to return an index of the searched word or report “not found”.

**Stage #2 Expand the search**  
With the help of arrays and linear search, add more strings to the program and search for specific data from that input. 

**Stage #3 User menu**  
Using switch operator and methods, create a user menu for your search engine.

**Stage #4 X-files**  
Enable your search engine to search for data stored in the files.

**Stage #5 Inverted index search**  
Working with lists and maps, build the inverted index to enhance your search.

**Stage #6 Search strategies**  
Get familiar with patterns and learn to deal with more complex types of search.
