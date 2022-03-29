# f.js

Simple library of essential javascript functions.

## DOM
```javascript
f.html.getElem(query, parent); //returns the element, parent param optional
f.html.getElems(query, parent); //returns array of elems, parent param optional
f.html.spawn(parentElem, childType, id); //return new elem, id param optional
f.html.empty(elem); //removes all children of elem from dom
```

## AJAX
```javascript
f.http.get(file, callback); //once file data is rx'd, it is passed to callback
f.http.post(file, data); //sends post req
```