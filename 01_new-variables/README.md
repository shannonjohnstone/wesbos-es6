#  Variables

```js
var
let
const
```

var is block scoped
const cant be re assigned
let is block scoped

#### let
Let is block scoped, a block is identified by being inside a set of {}, when you use let inside {} you can only declare the
values the once. Example

```js
{
  let emily = 'emily';
  let emily = 'emily johnstone' // this will get a err, as its already beein declared within the same block

}
```
But you can instead update the let. Example

```js
{
  let emily = 'emily';
  emily = 'emily johnstone' // this will work :)
}
```
