# MCMap
A WIP browser-based viewer for image tiles generated by the MCMap Java application/Minecraft server plugin. I'm using this project primarily as a way to get experience with web development, so it's going to be fairly rough for a while.

I wanted to focus on fundamental web technologies for this project, so I've decided to avoid web development frameworks and implement all client-side code in pure Javascript/CSS/HTML. Once the rest of the project is complete, I will probably reimplement client-side code in React to get the full advantages of modern web application development tools. 

I want to have all front-end features implemented before I start working on back-end code, so for now the project has been roughly implemented as a Tomcat servlet. Once the front-end is feature complete, the back-end will be reworked into something cleaner and more elegant, and much of the data that's currently defined directly in client Javascript will be offloaded to the server. I am tentatively considering a node.js server and a MySQL server for this step.
