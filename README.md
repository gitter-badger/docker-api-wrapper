# Docker API Wrapper
[![npm version](https://badge.fury.io/js/docker-api-wrapper.svg)](http://badge.fury.io/js/docker-api-wrapper)
[![Build Status](https://travis-ci.org/saigon-devs/docker-api-wrapper.svg?branch=master)](https://travis-ci.org/saigon-devs/docker-api-wrapper)

Docker API Wrapper that makes us call to the Docker API fast, easy and works like a charm...

# Use it

`npm install docker-api-wrapper`

or 

`npm install docker-api-wrapper --save-dev`

then 

`import {Container, Image} from 'docker-api-wrapper';`

# Run integration testing

+ If you want to make it works, please add ./spec/config.js file, then add
 
`module.exports = {
     server: '[your docker server ip]',
     port: [your docker port]
 };`
 
+ `npm install`
+ `npm run test`

# Demo Web Application

[Docker API with SwaggerUI](https://github.com/saigon-devs/docker-api)