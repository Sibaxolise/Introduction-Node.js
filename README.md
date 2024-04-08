Introduction to Node.js
   * History of Node.js
      • Originated in 2009 by Ryan Doll as a JavaScript runtime built on Chrome's VA engine.
      • Significant turning point in 2011 with the release of npm 1.0, facilitating open-source node library sharing.
      • Emergence of the Node.js Foundation in 2015, a collaboration between IBM, Microsoft, and PayPal.
      • The Node.js community is flourishing, hosting numerous international conferences and events, and has extensive application across diverse industries.

• JavaScript is primarily used for front-end development, but its capabilities extend beyond.
• Node.js, introduced in 2009, is used for a wide range of tasks, from command line tools to server creation and file system interaction.
• Major companies like PayPal, Netflix, and Microsoft use Node.js for scalable event-driven applications.

JavaScript and Node
• Javascript eliminates syntactical disparities between front-end and back-end development.
• Managing transitions between languages can be cognitively overhead due to syntax variations.
• Code and data structures can be shared seamlessly between the two.
• Libraries like Underscore can be used uniformly on both fronts.
• Use of the same token and encryption library ensures authorization consistency.
• Maintaining identical algorithms is imperative in web game development.
• Changing multiple data models across languages is less efficient than in a single language.
• Uniform programming principle minimizes redundancy and maximizes efficiency.
• Javascript unifies front-end and back-end, improving maintainability and overall development efficiency.

Pros of JavaScript
• Allows code sharing across back and front ends.
• JavaScript's dynamic nature: type determined by value, not variable declaration.
• Integrates with JSON for seamless web application use.
• Simplifies data transfer from back to front end without complex conversions.
• While not a universal solution, sharing JavaScript enhances web app development.

Callbacks and Asynchronous Tasks
• Synchronous tasks require waiting for each task to finish, causing blocking.
• Asynchronous tasks allow for immediate progress without waiting for the previous one.
• Synchronous processing can hinder user interface responsiveness until completion.
• Task completion time ranking, networking, and file system access often require lengthy waits.
• Node's efficiency in handling such tasks is attributed to its adept handling.
• Asynchronous code often employs callbacks, allowing execution to continue even with the "this comes after" console log.
• The callback is triggered upon task completion, mirroring how readdir calls the "phoneNumber" callback.

Node Globals
  Creating a module
• Create a new file, "my-module.js," in Visual Studio Code.
• Initiate another file, "module-demo.js," to make code within "my-module.js" accessible.
• Utilize exports object in "my-module.js" to make data available externally.
• Create a property named "myText" with a placeholder value.
• Maintain a one-to-one correspondence between files and modules.
• Access "my-module.js" by setting its reference to a variable within "module-demo.js" using the require function.
• Verify module values match expectations using a console log.
• Execute "module-demo.js" to see successful data access from another module or file.

Third-Party Packages
• Node Package Manager (NPM) is a tool for managing packages, including Lodash.
• Lodash is installed using "npm install lodash" and is stored in "node_modules."
• A file named "demo.js" is created using Lodash and assigned to a variable named "_".
• Node automatically knows the default module location, allowing for easy use of functions like "random" in JavaScript.
• Nodemon, a command-line interface, is installed globally using the "-g" flag for accessibility across projects.
• The "package.json" file is used to track dependencies of installed packages.

Package.json files
• Managing custom files and third-party packages is impractical due to space and transfer time.
• Creating a package.json file to maintain project dependencies is a solution.
• The npm install command automatically installs everything from the list.
• To create the package.json file, enter npm init in the terminal.
• The file includes defaults and scans the node_modules folder, adding dependencies.
• For quick package.json creation, use npm init --yes.
• Node's built-in module for file read and write operations is also discussed.

Node Modules
  Reading from Files 
• The Node.js file system module allows you to work with the file system on your computer.
• To include the File System module, use the require() method.
• The fs.readFile() method is used to read files on your computer.

Directory Access
• Initiating a new demonstration file using 'fs' module and'readdir' function.
• Initial parameter for'readdir' specifies directory location to read.
• Establishing callback with error and data parameters.
• Logging data using console.
• Saving changes, executing demo with nodemon.
• Output shows all directories within Drive C.
• Demo exemplifies the straightforward process of reading directories.

Writing to Files
• This method replaces the specified file and content if it exists.
• If the file does not exist, a new file, containing the specified content, will be created.
File Writing in JavaScript

• Creates a new file named demo.js, incorporating the file system module.
• Uses the writeFile function with the file name as the first parameter and the data as the second.
• Corrects a discrepancy in file content by converting the object to a string using JSON.stringify.
• Removes a deprecation warning by creating a callback function that logs errors and a 'write finished' message to the console.
• Updated script eliminates the deprecation warning and provides feedback upon completion.

Node Frameworks
  Understanding Frameworks
    • Frameworks serve as a foundational structure in software development.
    • They are crucial for web development, especially for creating large APIs or HTTP servers.
    
  Web APIs
    • Web APIs act as services enabling data retrieval and storage.
    • They are used to manage user creation, retrieval, and related functionalities.
    
  Popular Node.js Frameworks
    • Express: Traditional and tested, known for its simplicity.
    • Sails: Features-rich, includes an Object Relational Mapper (ORM).
    • Koa: Modern, offers innovative features.
    
  Future Discussions
    • Further exploration of Express, Sails, and Koa.
    
Express
• Express.js is a web framework designed for Node, supporting both web applications and web APIs.
• Web applications are functionalities on both the front and back end, distributed across the entire application.
• Express.js, operating within Node, specifically addresses the back end, facilitating communication with it.
• Despite its back-end nature, Express.js significantly contributes to the overall app.
• Express.js has extensive community support and online documentation due to its longstanding presence in the development community.

Socket.io
• Addresses Express's limitation of client-server communication.
• Enables bidirectional communication, allowing server to push notifications and data to client.
• Composed of client-side library for browsers and server-side library for Node.js.
• Both APIs feature event-driven functionality.
