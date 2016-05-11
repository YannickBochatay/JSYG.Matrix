# JSYG.Matrix
matrix constructor for JSYG

### Installation
```shell
npm install jsyg-matrix
```
You can also install it from bower

### Example with es6
```javascript
import Matrix from "jsyg-matrix"

let mtx = new Matrix()

console.log( mtx.translate(50,50).rotate(90).inverse().toString() )
```