
# HTML + Tailwind CSS with Webpack

This project uses HTML, Tailwind CSS, and Webpack to create a simple, customizable website.




## Prerequisites
Before you begin, make sure you have the following installed:

- Node.js
- npm (comes with Node.js)



## Installation

To install the dependencies for this project, run the following command:

```bash
  npm install
```

This will install the following packages:

- babel
- autoprefixer
- babel-loader
- clean-webpack-plugin
- copy-webpack-plugin
- css-loader
- css-minimizer-webpack-plugin
- html-webpack-plugin
- imagemin-webpack-plugin
- mini-css-extract-plugin
- postcss
- postcss-loader
- style-loader
- tailwindcss v3.2.4
- terser-webpack-plugin
- url-loader
- webpack
- webpack-cli
- webpack-dev-server
- webpack-merge


## Usage

Start the development server:

```bash
  npm start
```
It will run the development server with hot reloading and other features, you can access the application in your browser on http://localhost:9999.

To refresh any change on the fly:

```bash
  npm run watch
```

To build the bundle in development mode, run: 

```bash
  npm run build:dev
```
It will create a development bundle in the dist folder.

To build the bundle in production mode (ready to release) run:

```bash
  npm run build:production
```
It will create a production-ready build in the dist folder, you can use the output files on your hosting or deploy it on your server.




## Customization

You can customize the Tailwind CSS configuration by editing the tailwind.config.js file.

You can also configure the various plugins used in the webpack.config.js file.
## Conclusion
This is just a starting point, you can add additional features and customize it as per your requirement. Once you have all this set up, you can focus on building the features of your application, keeping the styling and build process managed.
## Credits

 - [Tailwindsss](https://tailwindcss.com/)
 - [Webpack](https://webpack.js.org/)
 
