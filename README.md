# gotoReact

[![Dependency Status](https://david-dm.org/psancho/gotoreact/status.svg)](https://david-dm.org/psancho/gotoreact#info=dependencies) [![devDependency Status](https://david-dm.org/psancho/gotoreact/dev-status.svg)](https://david-dm.org/psancho/gotoreact#info=devDependencies)

After using AngularJs in a ES6+webpack+Babel shell, I decided to dive into react.
This is my very 1st experience with React, that comes just after completing the [tutorial](https://reactjs.org/tutorial/tutorial.html).

My favorite reading was: [How to use Webpack with React: an in-depth tutorial](https://medium.freecodecamp.org/learn-webpack-for-react-a36d4cac5060)

Here is a more complete [description](./description.md).
## Main features
* Babel
* React
* Webpack
* ESLint

## Quick start

```bash
# Clone this repo
git clone https://github.com/psancho/gotoReact.git gotoReact
 
# change directory to your app
cd gotoReact

# install the dependencies with npm
npm i

# start the server
npm start
```

Go to http://localhost:8080 in your browser.

Note you can change the port directly in the `scripts` section of the `package.json`:
```json
"start": "webpack-serve --port=9000"
```

## Building the app

Just launch the following:

```bash
npm run build
```

## License

[MIT](./LICENCE)