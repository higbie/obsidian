---
title: Los Angeles Labor Lexicon
---
***Labor Lexicon*** is a work in progress. We are using this space to experiment with data models for our collections and research infrastructure projects. You can navigate through the data using the Explorer menu on the left sidebar (collections, organizations, people, and places) and by clicking on links you find. The Graph View (top right) displays links between pages. For background on this project check out [[About Memory Work Los Angeles]]

#### Organizations by Affiliated People
```dataview
table file.inlinks AS "Associated People"
from "organizations"
```


#### People by Affiliated Organization
```dataview 
table file.inlinks AS "Associated Organizations"
from "people"
```