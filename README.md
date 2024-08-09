## Quick Overview

```sh
npm install
cd test-1
npm start
```

### Get Started Immediately

You **don’t** need to install or configure tools like webpack or Babel.<br>
They are preconfigured and hidden so that you can focus on the code.

Create a project, and you’re good to go.

### Project Structure
It will have a directory called `test-1` inside the current folder.<br>
Inside that directory, it will generate the initial project structure and install the transitive dependencies:

```
test-1
├── README.md
├── node_modules
├── package.json
├── gulpfile.js        # configure project
├── index.html
├── .gitignore
├── app
│   ├── css
│   ├── img
│   └── js
│   └── scss
└── build              #optimize your project
```

You will write code in the app folder. If you write CSS, write the code in the "css" folder. If you can work with SCSS, write the code in the "scss" folder. 
The project will automatically build your code into the build folder, so you don't need to worry about the build folder.
