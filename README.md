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
• Creating demo.js file and enabling access to Node's file system using 'fs' module.
• Generating a temporary JSON file, data.json, with a property named 'name' enclosed in double quotes.
• Using'readFile' function to access the file system, passing in the location of the data JSON file as the first parameter.
• Shifting the callback to the third parameter and adding 'UTF-8' as a string in the second parameter to read the JSON.
• Accessing the JSON file using'require' directly, creating a 'data' variable and setting it to'require' with the path to data.json.
• Observing two distinct objects in the console - one from'require' and another from'readFile'.
• Addressing the disparities by creating a new variable, 'data,' and setting it to 'JSON.parse(data)' to convert the string to JSON.
