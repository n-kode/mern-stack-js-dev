BASIC NPM
node -v --> check node version
npm init -->create a package.json
npm install express -->install express
npm install babel-cli babel-preset-stage-0 babel-prest-es2015 --save-dev --> save local project only, dev dependencies are use for dev only not included in production like babel which compiles es6 where current browser understands
npm install -g react --> install globally
 npm install create-react-app -g --> cli to create react app
 npm install eslint@5.2.0 -g -->@ is the version you want
 npm install eslint -g --> the updated version
 npm outdated --> check the outdated packages locally
 npm outdated -g --> check the outdated packages globally
 npm uninstall babel-preset-es2015 --> uninstall babel
 npm install babel-preset-env --save-dev --> it will install the one in the env file
 version 2.2.2 --> first digit major, second is minor, third is patch or bug fix for semantic versioning
 verion ^2.1.2 -->caret will install version2 up but not 3
 verion ~2.1.2 --> tilde will install version 2.1.x up but not 2.2.x, more strict
 package-lock.json --> if you clone a project then package has caret and you have no package-lock.json if you do npm install it will install the latest breaks the app, so its imprtant to have the package-lock.json even if the verion of package has caret it will not update

ADVANCE NPM
npm cache verify --> it will verify the cache  then return a report, if there is problem then run
npm cache clean --force --> it will clean cache, verion 5 self heal
npm audit --> check if there are isuues in npm
npm -v --> check the version of npm
npm audit --> check if there are isuues in npm, if high solve it buy checking what package is it then install agian that package
npm install nodemon --> it will detect changes and auto run
"script" --> located in package.json you can add your own scripts to run inside your app
npx -p @angular/cli ng new myapp --> temporarily install @angular/cli then run the commad of the cli ng new myapp

Other options than NPM
YARN - npx yarn --> install yarn temporarily
NI - npx -p better-npm-install ni -->install ni temporarily
