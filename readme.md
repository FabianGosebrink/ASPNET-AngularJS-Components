# ASP.NET AngularJS Demo with Component based design

This repository offers you a demo application implemented with AngularJS (Component based design) and an endpoint using ASP.NET WebAPI.

Server and Client are completely seperated that you can exchange the endpoint easily.

### Check the corresponding package.json for the npm commands to start the repository

## AngularJS Client

This client is implemented with component based design and the one-way dataflow. It is using gulp as a taskrunner to minify and uglify the javascript files. By running 

```yarn```

and 

```npm start```

the application starts and runs in your default browser.

By typing 

```npm run buildProd```

the application build in a ".dist"-folder and you can then type 

```npm run liteProd```

to serve the files from the ".dist"-folder.


## Screens

### Home

![ASP.NET/ASP.NET Core AngularJS/Angular Demo](.github/screen1.jpg "Screen1")

### Form

![ASP.NET/ASP.NET Core AngularJS/Angular Demo](.github/screen2.jpg "Screen2")