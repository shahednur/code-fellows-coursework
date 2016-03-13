# Code Fellows Coursework

This repository contains some of my coursework from my time at Code Fellows.  Projects are not listed in any particular order.

##Code 401: Advanced Software Development in Full-Stack JavaScript

####image-vat

My independent coding assignment, an angular image gallery which allows users to add images to a MongoDB database.  Project continued here: https://github.com/JHM90/image-vat.git

####first-game

My fork on the our final project, [Spacecataz](https://github.com/SpaceShooterProj/first-game).

####client_for_rest_api

This application has server and client components which are located in either the 'server' or 'client' folder. The client is built using AngularJS and the server is built using Node.js, Express, and MongoDB.

####client_side_app

This is a simple Angular clock application. The client application is created using Gulp which takes HTML, CSS, and JS files in the "app" folder and copies their minified versions into a "build" folder for production use.

####rest_api

This REST API uses three resources, two of which represent two sides with units which have a name, a health value, a damage range, and an accuracy rating. These two resources have CRUD functionality for adding, deleting, viewing, and updating their units.  The third resource returns the balance of the force based on the number of battles each side wins. Wins are calculated by having the first member of each side attack one another until one, or both, are defeated. When this occurs the next Jedi on a defeated side begins attacking the victor (or new combatent) of the other side until only one side remains.

####react-crud-app

My fork from a group project, a CRUD application using React and jQuery. This application has server and client components, each of which is located in either the 'server' or 'client' folders in this directory.  Group project located here: https://github.com/React-CRUD/react-crud-app

####bitmapping

My fork from a group project, This application can help perform a few basic image processing transformations on bitmap files that are BM bitmaps, that have a 'BITMAPINFOHEADER' or 'BITMAPV4HEADER' DIB header, that have 8 or 24 bit color depth, and that have or do not have a color palette. Accepted bitmaps may have any width or height although smaller sized bitmaps are recommended for faster processing.  Group project is located here: https://github.com/bitmap-transformer/bitmapping

####saturday

This is a copy of my fork for our first group project, [Stock Poppers](https://github.com/stockwatchers/saturday), an application for viewing stocks that includes user registration and login functionality.  Graphs of stock data grabbed from the Yahoo! Finance API are rendered using D3.js.

####squirtle_beats_charizard

My fork from a group project, a single resource REST app using Koa.  Group project is located here: https://github.com/ricecreamdude/squirtle_beats_charizard

####simple_http_with_persistence

This HTTP server receives GET and POST requests to '/json'.  If a POST request is sent carrying a JSON string the JSON string is saved into a JSON file in a 'data' folder. Each time a POST request is sent the name of the saved file is incremented by one. For example, if one POST request carrying a JSON string is sent and no GET requests have been sent the first file will be named '0.json'. If another POST request carrying a JSON string is then sent the new file saved will be named '1.json'.  If a GET request is sent the content of the most recently saved JSON file in the 'data' folder will be sent to the client. If there are no saved JSON files a default JSON file is created and it's content is then returned.

####tcp_server

This TCP server logs any requests it gets into a uniquely named file.

####Ruuter

A basic framework for creating an HTTP server with routes. Easily write files and header messages upon requests.

####simple_modular_patterns_and_tests

A super duper useful greeting application.

####basic_http_server

This is a basic HTTP server. It responds to two routes, '/time' and '/greet'.  '/time' returns the current server time to the client when a GET request is performed by the client.  '/greet/name' returns a personal greeting to the client ([name]) when a GET request is performed by the client. Name must be a single word string in this case. The client may also perform a POST request to '/greet' where [name] will be collected from a JSON object with a name property. For example, sending the JSON object '{"name": "John"}' will return "Hello John".

####express_middleware

This is a simple Express server with a JSON parsing middleware function. Integration and unit testing is performed on the middleware.

####nodeBeginnerBook

Code in the Node Beginner Book, manually typed.

##Code 301: Intermediate Software Development

####code-blog

This is a single page code blog application.  You can view it here: https://jhm90.herokuapp.com/

####deployment-code-blog

The deployment version of the single page code blog application.
