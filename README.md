# EXP-03: State in React
## NAME:BASHA VENU
## REG.NO: 2305001005

## Aim
To develop a React application demonstrating state management using the useState() Hook.

## Objectives
1.Understand state in React.

2.Initialize and update state variables.

3.Handle button click events.

4.Dynamically update the user interface.

## Program
APP.JSX
```

import { useState } from "react";
import "./App.css";

function App() {
  const [count, setCount] = useState(0);
  const [name, setName] = useState("BASHA");

  return (
    <div className="container">
      <h1>React State Example</h1>

      <h2>Student Name: {name}</h2>

      <button onClick={() => setName("POORNA")}>
        Change Name
      </button>

      <hr />

      <h2>Count: {count}</h2>

      <button onClick={() => setCount(count + 1)}>
        Increase
      </button>

      <button onClick={() => setCount(count - 1)}>
        Decrease
      </button>

      <button onClick={() => setCount(0)}>
        Reset
      </button>
    </div>
  );
}

export default App;
```
APP.CSS
```
#root {
  width: 100%;
  margin: 0 auto;
}

.container {
  text-align: center;
  font-family: Arial, sans-serif;
  padding: 40px 20px;
}

h1 {
  color: #6c3ce9;
}

button {
  background-color: #6c3ce9;
  color: white;
  border: none;
  padding: 12px 20px;
  margin: 8px;
  border-radius: 6px;
  cursor: pointer;
  font-size: 16px;
}

button:hover {
  background-color: #4b25ad;
}

hr {
  margin: 25px auto;
  max-width: 400px;
}
```
## Output
<img width="1502" height="707" alt="image" src="https://github.com/user-attachments/assets/67404bb9-2bfb-48f8-aa3b-8c5d645f52a8" />
<img width="1507" height="711" alt="image" src="https://github.com/user-attachments/assets/7e09aea8-a20d-435a-9490-8cd57f584a7d" />

## Result
The React application was successfully developed to demonstrate state management using the useState() Hook and dynamic user interface updates.
