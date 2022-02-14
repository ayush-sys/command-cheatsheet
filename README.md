# command-cheatsheet

### React app
- `npx create-react-app my-app` **or** `yarn create react-app my-app` </br>
- cd my-app </br>
- `npm run start` **or** `yarn start` </br>



### React app with Tailwind CSS & Typescript
- `npx create-next-app@latest my-app` **or** `yarn create next-app my-app`

### Next JS App
-  `npx create-next-app@latest my-app` **or** `yarn create next-app my-app`


### Next JS app with Tailwind CSS & Typecript
-  `npx create-next-app --example with-tailwindcss my-app` </br>
-  `yarn create next-app --example with-tailwindcss my-app`



## Common NPM commands in Yarn

|NPM Command | Yarn Command| Description (_wherever necessary_)|
|:---|:---|---|
|npm install|yarn <br/> yarn install|Will install packages listed in the `package.json` file|
|npm install `pkg-name` <br/> npm install --save `pkg-name`| yarn add `pkg-name`|By default Yarn adds the `pgk-name` to `package.json` and `yarn.lock` files|
|npm install `pkg-name@1.0.0` | yarn add `pgk-name@1.0.0`|
|npm install `pkg-name` --save-dev| yarn add `pkg-name` --dev|
|npm install `pkg-name` --peer| yarn add `pkg-name`--peer|
|npm install `pkg-name` --optional| yarn add --optional|
|npm install -g `pkg-name`| yarn global add `pkg-name`| Careful, yarn add global `pkg-name` adds packages `global` and `pkg-name` locally! |
|npm update | yarn upgrade| Note: It's called **upgrade** in yarn|
|npm uninstall `pkg-name`| yarn remove `pkg-name`|
|npm run `script-name`| yarn run `script-name`|
|npm init | yarn init|
|npm pack | yarn pack| Creates a compressed gzip archive of the package dependencies|
|npm run | yarn run|
|npm cache clean | yarn cache clean|
|npm test | yarn test|
|npm install --production | yarn --production|
|npm  --version | yarn version|
|npm  info | yarn info|

