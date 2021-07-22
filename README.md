# Chrome-Extension
Hackathon Chrome Extension Project For Codesmith FTRI 3 Cohort with Savitri Beaver


Savitri's Notes:

- use a content script (js file) to inject your script into a page and add it in the manifest file under "content_scripts": [{"matches": ["<all_urls>"],
"js": ["content.js]}]
- create a popup html page? 
- use chrome.tabs.query({currentWindow: true, active: true}, function())
- make a regex to search for all instances of bootcamp names?
- background.js file
