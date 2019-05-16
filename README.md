# React-Memories

React Path

***************************
Module 2 Your First React Hook
- Pass a Function in onClick evente, we do not invoke the function
- logEvent without the parentesis.
EX:
function logEvent() {
  console.log(Math.random());
}

function Button() {
  const [counter, setCounter] = useState(0);
 ** return <button onClick={logEvent}>{counter}</button>;
 ** return <button onClick={function logEvent() { console.log(Math.random()); }}>{counter}</button>;
 ** return <button onClick={( ) => console.log(Math.random() }>{counter}</button>; 
}

ReactDOM.render(<Button />, document.getElementById("root"));
*************************

*************************
Module 2 Your First One-way Data Flow
- Props, it is properties that is passed through Parent function to child function
- To display the props we use props.variable passed in Parent function
- Each function has his own responsabilities, you design those response.
- You can pass params through parents like <Button message=2 /> and call it with props in child functions
*************************
