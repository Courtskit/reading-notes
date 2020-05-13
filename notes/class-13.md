# The Past, Present & Future of Local Storage for Web Applications

- HTML5 Storage
  - way for web pages to store named key/value pairs locally, within client web browser
    - the named key is a string
    - the data can be a string, boolean, integer or float .. but it is stored as a string
    - functions can be used to receive anything other than a string
      -  parseInt() or parseFloat()

- setItem()
- getItem()

- limitations in current browsers 
  - 5 megabytes is how much storage space each origin gets by default
  - “QUOTA_EXCEEDED_ERR” - exceeded storage space
  - can't request more storage

```
- Modernizr

if (Modernizr.localstorage) {
  // window.localStorage is available!
} else {
  // no native support for HTML5 storage :(
  // maybe try dojox.storage or a third-party solution
  )}
```
- IE
- Firefox
- Safari
- Chrome
- Opera
- IPhone
- Android


- information on the local computer is not received by the web server

