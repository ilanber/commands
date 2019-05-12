# Commands & Installs
Commads and installs doc.

## Add SASS librarry 'node-sass' package to any.
1. Generic: `npm init` - 'package.json' file.
2. Generic: `npm install` - node_modules.
3. `npm install -g node-sass` - 'node-sass' package globally.
4. Check the 'dependecies' prop in 'package.json' includes the 'node-ass' with current version.
5. Add to the 'scripts' prop in 'package.json' this line watcher `"scss": "node-sass --watch scss -o css"`. 
  ('--watch sass is the folder where all .scss development files and --o css is the a folder that will hold the
  transpiled css styles.')
6. RUN-BUILD: `npm run scss` - will create a transpiled .css file in your /css/ folder.
7. Notes:
    - Make sure to verify the path of the /scss/ and /css/ folders in the 'package.json' file.
    - Create the /scss/ folder first with a scss file (example: style.scss) and a /css/ folder without a .css 
    file in it so the RUN cimmand will create it at first for you.
    - once you RUN, each save will update automatically the .css generatd file. so no need to RUN after every change.

## Add SASS to ReactJS
1. start the project with: `create-react-app app --scripts-version react-scripts-sass`
2. Or install in a project `npm i react-scripts-sass`
3. if `react-scritps` was deleted install it again with `npm install react-scripts`
4. MUST: `npm install` again at the end.

## Kick react app
1. npx create-react-app my-app
2. cd my-app
3. npm start

## Add fetch jsonp
1. `npm install fetch-jsonp`
2. USE: `import fetchJsonp from 'fetch-jsonp';`

## Json Mock Server
1. `npm` init - package.json
2. `npm install --save json-server`
3. 'npm run json:server' - "josn:server" is custom and can be chaned

## Build
1. `npm run-script build`

## Git
1. `git init`
2. `touch [filename]` - create file (`ls` - see files and folders `nano [filename]` edit file)
3. `git add .`
4. `git commit -m ["any messege"]`
5. Create a repo in GitHub.
6. `git remote add [name] [git repo url from GitHub]
7. `git push --set-upstream [name] master'
8. `git checkout -b [branch name]`

