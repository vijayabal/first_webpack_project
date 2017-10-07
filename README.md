# first_webpack_project


This simple project explain how to add webpack.

Do the following steps:

1. First install npm platform.

2. Load all files in folder into local folder. Open folder in cmd and do the following commands
    > npm init
	
	> npm install webpack
3. Depedency files are added in folder inside node_modules

4. Open package.json ->under script property add 
		
	"build":"webpack src/js/index.js dist/bundle.js",

5. Run build cmd 

	>npm run build

6. Now bundle js is created in destination folder.	

7. To minified bundle js add below property under script in package.json

	"build:prod":"webpack src/js/index.js dist/bundle.js -p" 

8. Run buid:prod cmd prompt
	>npm run build:prod