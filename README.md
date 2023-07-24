# 0. Basic setup
mandatory
Create and run Webpack using a basic installation.

Create a folder named task_0.
Install webpack and webpack-cli as developer dependencies within the folder using npm.
Install jQuery as a regular dependency using npm.
Make sure that webpack and webpack-cli are listed under the devDependencies key along with jQuery being listed under the dependencies key within the package.json
Create a src directory with a index.js in it.
The file should import jquery and add three different paragraphs to the page body: (refer to this link under the Babel section for importing jQuery)
Holberton Dashboard

Dashboard data for the students

Copyright - Holberton School
Create a dist/index.html. Import your main.js in the body.
You must use jQuery to add the elements to the body of the page.
When running Webpack, your javascript and html files should be generated in a dist folder.
You should not use a custom webpack config file.
Opening your main file should not generate any error in the console.
Your html code should only import one Javascript script (the one generated by webpack).
Do NOT push your dist/main.js if you have one.
Repo:

GitHub repository: alx-react
Directory: 0x00-Webpack
File: task_0/package.json, task_0/src/index.js, task_0/dist/index.html
