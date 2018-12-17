## CREATE GUTENBERG BLOCK

https://github.com/ahmadawais/create-guten-block

I need NPM already installed on my PC.

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

## Gutenberg Video Tutorials

1. https://www.youtube.com/watch?v=ycNw2Jxziuw
2. https://www.youtube.com/channel/UCFnOHnLDMs7UUZxY8oq6fFA/videos

## Gutenberg Tutorial Articles

1. https://wordpress.org/gutenberg/handbook/
2. https://organicthemes.com/create-custom-block-wordpress-gutenberg/
3. https://code.tutsplus.com/tutorials/wordpress-gutenberg-block-api-creating-custom-blocks--cms-31168
4. How to Build Custom Gutenberg Blocks: a Beginner’s Guide - https://modularwp.com/how-to-build-gutenberg-blocks/
5. Wordpress Gutenberg Block API - https://code.tutsplus.com/series/wordpress-gutenberg-block-api--cms-1281
