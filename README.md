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

1. **ONLab Developers:**
https://www.youtube.com/watch?v=ycNw2Jxziuw
2. **Imran Sayed - Codeytek Academy**
https://www.youtube.com/watch?v=U4sfx7vN0Iw&list=PLD8nQCAhR3tSijB-KSc26ZiYYz3Lts4HD
3. **WordPress & JavaScript in 2019: Coding a Custom Block Type for Gutenberg Block Editor - LearnWebCode**
https://www.youtube.com/watch?v=Mv68Sa-iHyo
4. **Create Dynamic Gutenberg Block Tutorial | Fetch Latest Posts from Blog**
https://www.youtube.com/watch?v=XkjrrLR0Y3E
5. **Gutenberg block development bangla tutorial ( part 1 )**
https://www.youtube.com/watch?v=TmAq1Su6lD4
6. **Block Lab**
https://www.youtube.com/channel/UCXAYSopp1CZGswZf1w_Q80g/featured
7. **Gutenberg + Wordpress / How to develop blocks / Tutorial [ Part 1 ]**
https://www.youtube.com/watch?v=ycNw2Jxziuw&list=PLl4kJY9FLZGHqeGGx6kSBBVekrdpvZQEo
8. **Getting started with Gutenberg Block Development**
https://www.youtube.com/watch?v=EtS1on6YWhg
9. **Online Web Tutor**
https://www.youtube.com/channel/UCB2flCo-gW6RhpVVXySqcMg
10. **Extending Core WordPress Blocks - Gutenberg Course**
https://www.youtube.com/watch?v=6sL6J34SUlk
11. **WordPress Development - Create WordPress Themes, Plugins and Gutenberg Blocks Tutorial**
https://www.youtube.com/watch?v=jUmLd6Mwv4s
12. **Digging Into Gutenberg 2020 | Gutenberg Block Development Tutorial | @wordpress/components**
https://www.youtube.com/watch?v=_grCOGDeCwM
13. **How to create Block Patterns | register_block_pattern | The Future of Page Building in WordPress**
https://www.youtube.com/watch?v=eAIcFTo73oI&list=PLD8nQCAhR3tS2ObKBs7hx0B4uiiEbjuIq
14. **Gutenberg Block Tutorial - RichText Component**
https://www.youtube.com/watch?v=K3uQa035HTk
15. **Wordpress Development: Creating a custom Gutenberg Hero Section Block**
https://www.youtube.com/watch?v=SpymGO3La1M

## Gutenberg Tutorial Articles

1. https://wordpress.org/gutenberg/handbook/
2. https://organicthemes.com/create-custom-block-wordpress-gutenberg/
3. https://code.tutsplus.com/tutorials/wordpress-gutenberg-block-api-creating-custom-blocks--cms-31168
4. How to Build Custom Gutenberg Blocks: a Beginner’s Guide - https://modularwp.com/how-to-build-gutenberg-blocks/
5. Wordpress Gutenberg Block API - https://code.tutsplus.com/series/wordpress-gutenberg-block-api--cms-1281
