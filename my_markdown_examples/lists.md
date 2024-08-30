# Markdown lists

## Unordered lists
Unordered list items just begin with - or + or * and a space:
- unordered list item
- second unordered list item
+ breaking the list and starting a new one changing from - to +
+ second item of second list
- restarting previous list just switching again to -\
(or anyway breaking the second)
- note in the code the use of \ in the previous item to break the line\
(not only in lists and also double space works the same)
* now using *

## Ordered lists
To start an ordered list is enough to write any number followed by period and space:
1. first element
1234. markdown will increase the sequence automatically, regardless of the number at beginning of line

## Nested lists
- It is enough to add 3 spaces before the list marker
   - each time we want
      - a nested list
1. Works also with ordered lists with 3 spaces and also number restart from 1
   1. but markdown will manage automatically 
      1. the change of type of numeration/sequence

## Checkbox lists
if a list marker is followed by square brackets containing a **space** or an **X** then a checkbox is automatically shown as checked or unchecked:
1. [ ] task 1
2. [x] task 2
- [ ] List markers better to be consistent in order to make GitHub Issues correctly count the total of tasks and how many are checked/completed.
