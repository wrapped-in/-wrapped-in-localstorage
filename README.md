![Wrapped](https://github.com/wrapped-in/wrapped-in-localstorage/blob/main/publick/logo.png)
# Library for working with local storage
***
## Installation

npm:

```bash
$ npm install wrapped-in-localstorage
```

CDN:

```html
<script src="https://cdn.jsdelivr.net/npm/wrapped-in-localstorage@1.0.62/dist/wrapped-in-localstorage.min.js"></script>
```
***
## Feature List

#### Checking if an element exists in local storage.
```javascript
    WrappedLocalStorage.has();
```
* Returns - Boolean.

#### Getting the value of an item in local storage.
```javascript
    WrappedLocalStorage.get();
```
* Returns - Object.

#### Create an item in local storage.
```javascript
    WrappedLocalStorage.set();
```
* It takes arguments - key, value.

#### Removing an item from local storage.
```javascript
    WrappedLocalStorage.delete();
```
* It takes an argument - key.

#### Clearing local storage.
```javascript
    WrappedLocalStorage.deleteAll();
```

#### Get the number of local storage items.
```javascript
    WrappedLocalStorage.getLength();
```
* Returns - Nuber

#### Checking the health of local storage.
```javascript
    WrappedLocalStorage.checkEnabled();
```
* Returns - Boolean.