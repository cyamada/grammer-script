grammer-script
==============

A script for syncing grammatic corrections across browsers. Syncing is done via Firebase and can be implemented
on any page running JQuery 1.3.2, 2.0.3, and JS API. This version of the script does not inject the js to pages
meaning the script must be hard-coded. 

Highlighted text with a correction submitted will then propagate in real-time to browsers opened to the same page. 
The written correction information is not shown but can be accessed with a call to message.correction
