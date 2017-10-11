# express-simple
> A project for fast development of REST APIS, where routes can return JSON documents

Simple starter, bare bone structure based on ExpressJS. Helps easily creating controllers for routes. Provides Flightplan file for simple deployment strategy.

This project uses the following libraries:
- [express](https://www.npmjs.com/package/express)
- [helmet](https://www.npmjs.com/package/helmet)
- [morgan](https://www.npmjs.com/package/morgan)
- [body-parser](https://www.npmjs.com/package/body-parser)
- [flightplan](https://www.npmjs.com/package/flightplan)
- [fly](https://www.npmjs.com/package/fly)

## Installation
To install, open your terminal and run following commands:
```
git clone https://github.com/mjrdnk/express-simple
cd express-simple/ && npm install
```
## Usage
To run express-simple, make sure you are in your projects directory and run this command:

```
node server.js 
```

or use this optional tool for running the server with reloading:

```
npm install -g nodemon
nodemon
```

And then go to http://localhost:5000/api/v1.0/hello

## Credit
Flighplan based on [this gist](https://gist.github.com/learncodeacademy/35045e64d2bbe6eb14f9)

## License

[MIT](LICENSE)
