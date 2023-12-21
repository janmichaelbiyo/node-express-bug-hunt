# Node & Express Bug Hunt!

**READ ALL INSTRUCTIONS BEFORE STARTING**

There are 10 bugs in total, can you find them all? There are hints throughout (???), you should only need to make minor modifcations to 10 lines of code.

**Don't race through the files looking for the issues!** They should all have a console log or error that help you identify them. Read the console so that you know what error will cause each bug. The last one is tricky since it doesn't throw any errors. Document the error, line number and your fix in this README for each of the bugs.

## Setup
```
npm install
npm start
```

> NOTE: A couple of bugs prevent the server from starting.

## Error List

TODO: Add the error here followed by the line of code you fixed.




### Bug 0

`ReferenceError: app is not defined`

Fixed `quote.router.js` line 28: switch `app` to `router`. _This is the solution to the first bug._



### Bug 1

-- Router.use() requires a middleware function but got a Object

added `module.exports = router`
...
### Bug 2

-- server 404 error not found  GET http://localhost:5007/quotes%7D 404 (Not Found)

deleted qoutes from router.get on the qoute.router.js

### Bug 3

-- GET http://localhost:5007/quotes%7D 404 (Not Found)

deleted curly on url code in client.js file 

### Bug 4

--TypeError: quotesFromServer is not iterable
    at client.js:18:26

 the qoutes were not an array but an object, chaged the object of qouteLIst into an array   

 ### bug 5 

 404 vad request on post qoutesList is not defined 

 removed s from qpoutesList in the router.js push element

 ### bug 6

 ReferenceError: getQuote is not defined

 added s on getQoute() on like 55 of client.js 

 ### bug 7

 

## Extra Practice (Optional)

Complete the JS debugging exercises at:

- https://education.launchcode.org/intro-to-professional-web-dev/chapters/errors-and-debugging/exercises.html
