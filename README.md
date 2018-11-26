## CREATE GUTENBERG BLOCK

https://github.com/ahmadawais/create-guten-block

We need NPM already installed on my PC.

You’ll need to have Node >= 8 and npm >= 5.3 on your local development machine (but it’s not required on the server).

1. Navigate to "wp-content/plugins" folder
2. Issue this command

```js
npx create-guten-block my-block
```

OR, (for older versions)

```js
npm install create-guten-block --global
```

It will create a directory called my-block inside the current folder. Inside that directory, it will generate the initial project structure and install the transitive dependencies:

3. Once the installation is done, you can open your project folder and run the start script.

```js
cd my-block
npm start
```

NPM will start watching the project until Control+C is pressed to stop watching.

This runs the plugin in development mode. To produce production code run:

```js
npm run build
```
