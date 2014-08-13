trello-savedsearches
====================

Several Bookmarlets to achive custom trello(trello.com) actions. To install them just create a new marker for each one on your bookmark bar, and edit the url accordingly if necessary.

Note: For all bookmarlets to work, is necessary to be logged in on trello's page.


Saved Searches
==============

This bookmarlet allows you to programatically save a trello search, it is actually a shortcut to a specific search. In order to create a custom search, just create a new marker on to the bookmark bar as many times as different shortcuts you want to make, and edit the function call to pass the apropiate filter.


```javascript
javascript:function%20showStatusOpen(filter){$("input.header-search-input"%20).trigger(%20"click"%20);$("input.header-search-input"%20).val(filter);$("input.header-search-input"%20).trigger(%20"keydown"%20);}%20showStatusOpen("YOUR CUSTOM FILTER");
```






