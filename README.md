# express-postgres-react-polyfills-make

This is a sample project, generated by [docker-compose-nodejs-examples](https://github.com/b00giZm/docker-compose-nodejs-examples), to help you getting started with [Docker Compose](https://docs.docker.com/compose/) and Node.js.

## Requirements

You need, of course, recent versions of Docker and Docker Compose installed. Please refer to the [original documention on the Docker website](https://docs.docker.com/compose/install/) to see how to install them on your system.

[GNU Make](https://www.gnu.org/software/make/) should also be available on your system. If you have any build tools installed, chances are pretty good that `make` is already present on your machine.

## Quickstart

```bash
cd /path/to/express-postgres-react-polyfills-make
make
```

Depending on the project layout, it might take a few minutes to compile, build and start the app. When done, you can access the app in your browser. On macOS and Linux, this should be [http://localhost:3000](http://localhost:3000).

## What's Inside

* Skeleton: **express**
* database: **postgres**
* Frontend: **react**
* Browser Polyfills: **yes**
* Build Tool: **make**

Don't like it? Roll your own with [docker-compose-nodejs-examples](https://github.com/b00giZm/docker-compose-nodejs-examples).

## Make Targets

* **docker-build** - Builds the application's Docker image
* **install** - Installs all necessary NPM dependencies
* **start** - Starts the application via `docker-compose up`
* **build-js** - Builds all JavaScripts for the browser
* **watch-js** - Builds JavaScripts and watches for file changes to rebuild
