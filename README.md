# socketio-openshift-example

OpenShift websocket support demystified for application developers. This example app can be run locally on your own dev machine and in the OpenShift cloud. This example utilizes the [express.js](http://expressjs.com/) and [socket.io](http://socket.io/) libraries in [node.js](http://nodejs.org/). See the [config.js](https://github.com/nodebooks/socketio-openshift-example/blob/master/config.js) for the details for OpenShift.

Let's play ping-pong.

### Fork details

This project was forked from [socketio-openshift-example](https://github.com/nodebooks/socketio-openshift-example) and updated to work on Node.js (Latest) gears on Openshift. This was for my personal investigation, but others may find it useful.

## Run locally

Here are the console commands for Ubuntu Linux and/or Mac OS X with relevant tools installed. The first command `cd ~` switches to your home directory, skip this if you want to install to some other dir.

```
cd ~
git clone https://github.com/nodebooks/socketio-openshift-example.git wsexample
cd wsexample
npm install
node server.js # or nodejs server.js in some Ubuntu releases
```
Now open your browser on [http://127.0.0.1:8080](http://127.0.0.1:8080)
