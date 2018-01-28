# Making JSX Programmable
Statically assigning JSX to variables isn't very useful, to improve on this, we can `return` JSX from a function; in addition to this we can also use Javascript inside JSX by using `{` and `}` to inject Javascript inside our JSX.

## In Summary
1. We define a new React component by creating a function.
1. This function returns JSX, in this example we return a nicely formatted version of the current date.
1. We resolve the function when we render it via `ReactDOM.render` by using the function name as an XML element.
