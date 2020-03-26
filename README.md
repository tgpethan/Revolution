<h1 align="center">
  <img height="150" src="http://ethanus.ml/images/Revolution.png">
</h1>
<h2 align="left">What is Revolution?</h2>
<p align="left">Revolution is a modular web framework, written in node.js and built with the purpose of being a solid framework that apps can build upon to get up and running quickly and easily. Revolution is designed to make it easy to create the application you need, with no waste.
</p>

<h2 align="left">What is Revolution for?</h2>
<p align="left">Basically anything. As long as you want to try it, it’s probably possible.</p>
<h2 align="left">How does Revolution work?</h2>
<p align="left">Revolution uses a set of modules to handle various functions, there are two modules included with the repo and builds, these being consoleHelper and example_request_handler. consoleHelper is a required module and as such the framework will not start without it, however example_request_handler can be removed without consequence and is there purely to help with module development.</p>
<h2 align="left">How do modules work?</h2>
<p align="left">Modules are loaded in at runtime and are completely separate from each other. Each module has a prefix, for example the request handlers have the prefix “handle_requests” and the consoleHelper has the prefix of "handle_console". These prefixes help the server to determine the function of each module.</p>
<h2 align="left">How to use Revolution.</h2>
<h3 align="left">From source</h3>
<p align="left">git clone https://github.com/tgpethan/Revolution.git<br>
  cd Revolution<br>
  npm i<br>
  node . </p>
<h3 align="left">From build</h3>
<a href="https://github.com/tgpethan/Revolution/releases/latest">Download latest build</a>
<p align="left">Unzip the zip<br>
  Run the Revolution executable</p>
<h2 align="left">How to install modules.</h2>
<p align="left">With modules you simply have to place the module inside the modules folder and start the server.<br>
  The modules will automatically set themselves up and the server will start as normal.
</p>
<h2 align="left">Projects Revolution is used in</h2>
<a href="https://github.com/tgpethan/EUS/">EUS</p>