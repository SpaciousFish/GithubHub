# GithubHub
This is a site to search Github for interesting projects.

See the app: https://github-hub.netlify.app

How to host on a local web server. There are 
several options:

- Use IISExpress on Windows:

  You can download IISExpress here: 
  http://www.microsoft.com/web/gallery/install.aspx?appid=IISExpress
  
  To use it, open a command window and go to the IISExpress folder:

  cd \Program Files (x86)\IIS Express

  Then type: 

  iisexpress /path:{folder with the project} /port:8080

  e.g.

  iisexpress /path:"c:\users\documents\project" /port:8080

  Once you do this, you can open the project up in a web browser by navigating to:

  http://localhost:8080

- Use node.js and http-server on any node.js compatible operating system

  You can download node.js from here:
  http://nodejs.org

  Once installed, you can get http-server installed by typing this at a node.js command prompt:

  > npm install http-server -g

  Once npm installs the tool, you can host the files by going to the folder they reside in and 
  typing:

  c:\users\documents\project>http-server .

  Once you do this, you can open the demo up in a web browser by navigating to:

  http://localhost:8080

