# Unintentional Child Element Removal using innerHTML

This example demonstrates an uncommon HTML bug related to the use of `innerHTML`.  When replacing the content of a div using `innerHTML`, any existing child elements within that div are removed and replaced with the new content.  This is unexpected behavior if the intention is to modify but not remove the children.