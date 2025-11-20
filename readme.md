git clone https://github.com/moslem-el-saman/ts-classes.git
```

Navigate into the project directory:

```bash
cd ts-classesnpm start

```

### Installing Dependencies

Once you've cloned the repository and navigated into the project folder, install the necessary Node.js dependencies:

```bash
npm install
```

This will install all packages listed in `package.json`, including `typescript`, `ts-node`, and `nodemon`.

## Running the Project

This project uses `ts-node` for direct execution of TypeScript files and `nodemon` for automatic restarts during development.

Here are the available scripts defined in `package.json`:

*   **`start`**: Runs the compiled JavaScript code.
*   **`dev`**: Starts the project in development mode using `nodemon` and `ts-node`, automatically recompiling and restarting on file changes.
*   **`build`**: Compiles the TypeScript code into JavaScript.

### Development Mode (Recommended)

For active development, use the `dev` script. This will watch for changes in your TypeScript files and automatically recompile and restart the application.

```bash
npm run dev
```

### Running the Compiled Project

If you want to run the project after it has been compiled to JavaScript, first build it:

```bash
npm run build
```

Then, you can start the compiled JavaScript application:

```bash
npm start
```

### Compiling TypeScript

To manually compile your TypeScript code to JavaScript, use the `build` script:

```bash
npm run build
