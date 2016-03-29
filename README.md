# Simple chat app in TypeScript


## Tools Required
* [Node.js](https://nodejs.org/) (>= 2.0)
* NPM
* [Gulp.js](http://gulpjs.com/) (```npm install --global gulp```)
* [typings](https://github.com/typings/typings) (```npm install --global typings```)

## How to run
1. Run following commands:
   ```
   npm install
   typings install
   ```
   
   Some things to note:
   * ```npm install``` will install this project's node dependencies from package.json.
   * ```typings install``` will retrieve TypeScript Definition files (*.d.ts) from [registry](https://github.com/typings/registry).
2. Compile the app with the following command:
   ```
   gulp build
   ```
   
   The above command will use tsconfig.json to compile all necessary files to **<project_root>/dist/** folder
3. Launch the Node process to serve the app using the following command:
   ```
   node dist/app.js
   ```
4. Open your favorite browser and navigating to ```http://localhost:3000/``` to access the app.
