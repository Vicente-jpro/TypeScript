# TypeScript
 Learning typeScript

#### Create directors
<pre>/dist/js and /src</pre>

#### Check typeScript version
```bash
    tsc -v
```

####  Set up file configuration
```bash
tsc --init

```
<br/>
Then go to file tsconfig.json and in /* Modules */ add or uncomment this line "rootDir": "./src", 
<pre>
    /* Modules */
    "module": "commonjs",                                /* Specify what module code is generated. */
    "rootDir": "./src",                                  /* Specify the root folder within your source files. */
    // "moduleResolution": "node",                       /* Specify how TypeScript looks up a file from a given module specifier. */
    // "baseUrl": "./",         
</pre>

<br/>

Then go to file tsconfig.json and in /* Emit */ add or uncomment this line "rootDir": "./dist/js", 
<pre>
    /* Emit */
    // "declaration": true,                              /* Generate .d.ts files from TypeScript and JavaScript files in your project. */
    // "declarationMap": true,                           /* Create sourcemaps for d.ts files. */
    // "emitDeclarationOnly": true,                      /* Only output d.ts files and not JavaScript files. */
    // "sourceMap": true,                                /* Create source map files for emitted JavaScript files. */
    // "outFile": "./",                                  /* Specify a file that bundles all outputs into one JavaScript file. If 'declaration' is true, also designates a file that bundles all .d.ts output. */
    "outDir": "./dist/js",                                   /* Specify an output folder for all emitted files. */
    // "removeComments": true,                           /* Disable emitting comments. */
    // "noEmit": true,         
</pre>


####  Compile your code.
Go into /src then execute this code in your terminal. 

```bash
tsc -w

```

Then you can use only this line do execute your code.
```bash
tsc 

```