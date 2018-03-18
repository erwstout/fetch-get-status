# fetch-get-status
A small helper to check a status of a fetch.

## Usage
```js
import fetchCheckStatus from 'fetch-check-status';

doSomething() {
  fetch(someURL)
  .then(fetchCheckStatus)
  .then(response => doSomethingElse(response))
}
```
