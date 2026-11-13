# Ex-3-State-in-React
## Name: TAMIL MARUDHU K
## Roll no: 2305001033
## Department: CSE

## AIM
### To create a simple React application that demonstrates the use of State using the useState() Hook. 

## PROGRAM
### App.jsx 
```py
import { useState } from "react"; function App() { const [name, setName] = useState("Aravindan T"); const [newName, setNewName] = useState(""); 
return ( 
<div> 
<h1>Student Name Example</h1> 
<h2>Student Name: {name}</h2> 
<input type="text" placeholder="Enter new name" value={newName} 
onChange={(e) => setNewName(e.target.value)} 
/> 
<button onClick={() => setName(newName)}> 
Change Name 
</button> 
</div> 
);
}
export default App;

```
## OUTPUT
<img width="1286" height="442" alt="image" src="https://github.com/user-attachments/assets/648452d0-bab7-4d3c-8d1e-9efa7e5cde23" />
<img width="1352" height="397" alt="image" src="https://github.com/user-attachments/assets/c9c5cf1e-2e66-454c-8057-d85b13370b8b" />

## RESULT
### The React application was successfully created using Props to pass employee information from the parent component to the child component. Three employee details were displayed successfully using Props and Props Destructuring.
