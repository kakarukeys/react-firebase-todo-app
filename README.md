# TodoApp implemented in *FB React* with Firebase backend

the purpose of this exercise is to
  - explore integration of [FB React](https://facebook.github.io/react/) app with [Firebase](https://www.firebase.com)
  - learn to build realtime offline-first web application
  - implement authentication and authorization with Firebase

by using as few number of external dependencies as possible to avoid distractions from the learning goals.

The code with comments lies in *index.html*. A Firebase account and app are needed, replace Firebase URL in `index.html` with the correct one.

```javascript
firebaseRef = new Firebase("<YOUR APP URL>");
```

Python is needed to run a webserver serving the files, needed js files are fetched from cdn.

### To Run
Clone the repo, go inside the directory

```sh
$ python -m SimpleHTTPServer
```

then open http://localhost:8000 in a browser.
