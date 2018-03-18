# fetch-get-status
A small helper to check a status of a fetch.

## Usage
```js
import fetchGetStatus from 'fetch-get-status';

doSomething() {
  fetch(someURL)
  .then(fetchGetStatus)
  .then(response => doSomethingElse(response))
}
```
