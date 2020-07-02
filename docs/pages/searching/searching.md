---
Title: Searching
nav_order: 1
---

# Searching

## Find cells that include a character array

Given a cell array x, find the indices of the cells that include the character array y

`find(cellfun(@(x) ~isempty(x), strfind(x,y)))`


