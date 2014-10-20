

# node-surveys : install node modules
npm install 



## Usage : NTML implemented.

In case you don't want authentication with NTLM, comment out 
app.all('/', ntlm());
app.get('/', routes.index_ntlm);

Uncomment 
// Main App Page - Use this when you don't need NTLM authentication
//app.get('/', routes.index); 
http://localhost:3000


## Developing
NTML based auth
session management with Mongo DB store
socket io for real time reports


### Tools

