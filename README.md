# React-js-Combo
Desarrollo integral de aplicación 
## Comparación Angular y Reactjs:


Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3


****Intalación inicial:****
  ' sudo apt-get install curl '
  ' curl -sL https://deb.nodesource.com/setup_11.x | sudo -E bash -
  sudo apt-get install -y nodejs '
  ' node --version '

  ' curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
  echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list '
  
  ' sudo apt-get update && sudo apt-get install yarn '
  ' yarn --version '

  ' sudo snap install --classic code '
  
  ****plugins para code:****
  Babel Javascript para syntax highligthing
  ESLint checkeos de código
  Git Blame y GitLens integraciones con git
  Prettier - Code Formatter code formater

***EN REPO:***
_backend:_ 
Crear archivo server.js:

```javascript
  var http = require("http");

console.log("Loading server");

http.createServer(function(request, response) {
  console.log("Request received");
  response.writeHead(200, {"Content-Type": "text/html"});
  response.write("Hola Mundo");
  response.end();
}).listen(8888);
```

