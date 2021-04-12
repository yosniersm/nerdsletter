# Nerdsletter

The nerdsletter system is a little subscription system
for [Node.js](//nodejs.org) modules, using
the [npm module registry](//npmjs.com) (among others) as an external
data source.


## Getting started

Follow these instructions to get a demonstration nerdsletter system up and
running.

1. Checkout this repository.
  ```
  $ git clone https://github.com/yosamac/nerdsletter.git
  ```

2. Checkout all the microservice repositories.
  ```
  $ ./nerdsletter/git-clone-all.sh`
  ```
  
3. Install all the modules.
  ```
  $ ./nerdsletter/npm-install.sh`
  ```

4. Build images every mircro-service
  ```
  $ cd <micro-service>`
  $ npm run build:pro-image`
  ```

5. Start up the system by running the local development environment
  using ([docker-compose](https://docs.docker.com/compose/)).
  ```
  $ docker-compose up
  ```

## List of repositories

* [nerdsletter-subscription](//github.com/yosamac/nerdsletter-subscription)
* [nerdsletter-email](//github.com/yosamac/nerdsletter-email)
* [nerdsletter-public](//github.com/yosamac/nerdsletter-public)



