# Typescript

 Quick start with *typescript*:
 
 1. Create project folder [optional], my project folder was called Type Script
 2. Open terminal in project folder and paste or type the command ```npm install typescript```
 3. Now paste or type the command  ```mkdir src```
 4. Inside of the src folder create a file named [tsconfig.json](http://stackoverflow.com/questions/12799237/how-to-watch-and-compile-all-typescript-sources) and include the following code snippet
 ```            
            {
                "compilerOptions": {
                    "emitDecoratorMetadata": true,
                    "module": "commonjs",
                    "target": "ES5",
                    "outDir": "js",
                    "rootDir": "src"
                }
            }
 ```
 5. Open a terminal in the src directory and run ```tsc -w```, it'll compile any ".ts file" in this directory into a ".js file" and store them in the js directory.
 6. To test, create a file called "main.ts" in the src folder and include the code snippet below then look into the "js" directory.
 ```
 class main{
     
 }
 
 ```