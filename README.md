# Cross-Site-Scripting (XSS) 

Below are the below types of XSS 

Stored (Persistent) XSS :- When user input is stored on the back-end database and then displayed upon retrival (e.g. posts or comments) 
Reflected (Non-Persistent) XSS :- When user input is displayed on the page after being processed by the backend server, but without being stored (e.g search result or error message) 
DOM-based XSS :- Occurs when user input is directly shown in the browser and is completely processed on the clisent-side, without reaching the back-end server (e.g through client-slient HTTP parameters or anchor tags) 


We can check if the server is vulnerable to XSS or not by testing payload in the below sites. 

https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/XSS%20Injection/README.md
https://github.com/payloadbox/xss-payload-list

