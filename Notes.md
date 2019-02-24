1. NPM resolves path of all executable that are in `node_modules/.bin` directory
2. Webpack have access of all node core modules (common sense, but now of 'cluster' module of node 😉, possibilities are endless)
3. We can do `$(npm bin)/webpack` which is resolved to `node_modules/.bin` directory too.
4. To run babel from terminal web can do,
    ```sh
    $(npm bin)/babel src/greet.js --presets @babel/preset-env
    ```
5. You can clone the project with your name
    ```sh
     git clone --depth=1 https://github.com/sanketgandhi/react-boilerplate my-app
    ```
