# Welcome to the CFBC Works Repository! 
This is your crashcourse on "what is where" and "how to change it"

**For Contributors**
|Content|Source File
|--|--|
|'Base' text that appears on multiple pages (i.e. title, subtitle, footer content|_config|
|color schemes/pallettes|_sass/colors/_cfbcStyle.scss|
|navigation bar labels & page links|_data/navigation.yml|
|item-specific text |_items/~~itemName~~.md|
|page-specific text|pages/....(index, collection/people/project.md)


**For Developers:**
 - i want to change the filter functionality? where is it?
	 - _includes/_itemlist.html - where multiple item boxes get appended based on filter criteria via script
	 -  __itembox.html: where individual item cards/tiles are laid out & generated

