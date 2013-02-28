## Schedule

### Intro

  * 30 second attention grabber, Flashy demo?
  * Session overview (5 minutes)
    * David intro
    * Jim intro
    * Link Github Examples Repo
    * session overview
      * Javascript Concepts
      * Node Concepts
      * Basic Node Apps
      * Complex Node Apps and App Deployments
  * My History with Node?
  * Node.js now.
    * thriving community
    * skepticism
  * Get feel for audience ability (5 minutes)
    * how many have laptops and will be participating?
    * how many know JS (more than JQuery?)
    * how many know any Node
    * how many have built something meaningful in Node

### Javascript Concepts (30 minutes)
  * functions, object
  * scope
  * by reference or value?
  * closures
  * classes
  * inheritance
  * anonomous functions
  * async vs sync
  * callback pattern
  * ECMAScript Latest
  * native JSON
  * popular helper libraries

### Node Concepts (60 minutes)
  * [Why Node?](http://nodejs.org/about/)
  * event loop
    * importance of non-blocking
    * IO concepts
      * db call in most languages
      * db call in node with callback
    * exits when no processes left
  * callback pattern standards
    * limit pyramid depth
    * err, result callback args
  * promises
  * single process
    * shared memory
      * benefits
      * gotchas
  * Node Modules
    * package.json
    * require
    * singleton vs factory module export
    * NPM
    * exporting binary for command line usage
    * which modules should I use?

### Node in Basic Apps (20 minutes)
  * cli apps
  * [restful apps](https://github.com/skookum/restful)
  * [express app](http://expressjs.com/)

### Using Node in a complexapp (30 minutes)
  * common DB choices
    * MongoDB
    * Redis
    * MySQL
  * using traditional MVC architecture
  * using components alternative
  * base12
  * running more than 1 process
    * shared sessions with Redis
    * Redis pub/sub
  * deployments
    * Heroku
    * Linode




### Misc Content points to possibly add
  * unit testing
  * effective node app are many small specialized apps, not a single large app
  * many small requests vs less large ones
  * the event loop is always running
  * streams
  * speed (req/sec)
  * answer “why should I care about node”
  * discuss wide range of uses
    * websites, apps, api’s, cli tools, etc


### Demo App Ideas
  * basic chatroom
    * socket.io
  * shared app
    * drawing?
    * fish tank?
  * max game
  * CLI app
    * read file
    * send request through API
    * streams?
    * use JS lib that would normally be used client side