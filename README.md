# js_sortable_list
A html table where each column can be sorted by clicking it's header

Also a search-box where the rows are filtered on the written text.

# Usage

To define your own table:
  1. Give each column a unique name in the header, see below. 
  2. Fill up with your rows, and make sure the div "hidden-data" contains each rows data for sorting. NOTE: Use lower case, because the search use lower case.
  3. Define each columns datatype in the js-object dataTypes. This is for sorting to work. (string-wise or number-wise)
  
  That's it! You should not need to change anything in the javascript-functions for the sorting and filtering to work.

![Screen dump](/Snorvarg/js_sortable_list/screendump.png?raw=true "Screen dump")
