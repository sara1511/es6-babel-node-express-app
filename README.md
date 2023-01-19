# es6-babel-node-express-app

A node JS server using express for routing, compiled with babel to use ES6

### Getting started
* clone/fork this repo `git clone https://github.com/sara1511/es6-babel-node-express-app.git`

First, run the development server:

```bash
cd es6-babel-node-express-app
npm install
npm run start:dev
# or
yarn install
yarn run start:dev
```

Open [http://localhost:8000](http://localhost:8000) with your browser to see the result.

The route is currently working and have no logic what so ever to return. It just send back the JSON send to the route or give a success message.


### Production setup

Build your Babel node es6 application to deploy and run on production server:

```bash
npm run build
npm start
# or
yarn run build
yarn start
```
