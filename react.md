* React works by calling `ReactDOM.render(JSX, document.getElementById('root'))`. This function call is what places your JSX into React's own lightweight representation of the DOM. React then uses snapshots of its own DOM to optimize updating only specific parts of the actual DOM.

* Regarding JSX, it should only return a signle element, this parent element can wrap all nested elements. Note that we can also wrap everything in parantheses, but it is not strictly required.

* we use `{/* */}` to put comments inside a JSX.

* 