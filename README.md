# Link-Shortener-1.0
Shortens the input URL to give a shortened link as well as keeps track of the initial URL,shortened link and no. of clicks on the link.

The web application uses Node.js,Express and MongoDB.

package.json contains the script 'devStart' that runs server.js using nodemon.

server.js contains all the code for the application it is a basic server.

When the application is deployed we can use the PORT environment variable however as of now it defaults to port 5000 thus run localhost:5000 on local browser to see implementation.

Folder views contains index.ejs 'ejs' is the template view engine packages which were installed.

index.ejs contains the form for getting new links as well as list of previously inputted links and their shortened links as well as number of times the links were clicked which is maintained in a table.

Instead of writing own css we use bootstrap cdn to provide some basic styling.

Models folder contains shortUrl.js containing the initial url,shortened url and no of clicks column values.

shortid library generates the shortened links which is included in the above shorturl.js.
