REACT LIBRARIES : <br/>

- React is Depends on Two Libraries, 1) React and 2) ReactDOM<br/><br/>

1) REACT :<br/>

- In react is a core library of react Js.<br/>
- It contains functionalities to manage and maintain the components, state, props and event handling.<br/>
- We need to import React from "react".<br/><br/>

2) ReactDOM :<br/>

- This Library is responsible for rendering the components into the UI/DOM Tree.<br/>
- We need to import ReactDom from "react-dom/client"<br/><br/>

#-- CreateRoot :<br/>

- It is a Method which helps you to create Root for rendering react components within DOM Node.<br/>
- It acts as bridge between index.html and main.jsx<br/>
- It Specifies where react should render.<br/><br/>


#-- CreateElement : <br/>

- It is a Method which helps you to create react elements programmatically.<br/>
- It is an alternative to using jsx.<br/>
- It takes Three Parameters 1) ElementType 2)Attribute 3) Content<br/><br/>

=====================================================================<br/><br/>

FILE : main.jsx<br/><br/>

import React, { createElement } from 'react'<br/>
import { createRoot } from 'react-dom/client'<br/><br/>

createRoot(document.getElementById('root')).render(<br/><br/>

    <>
        <h1>Hello, React!</h1>
        <h2>Hello, React!</h2>
        <h3>Hello, React!</h3>
        <h4>Hello, React!</h4>
        <h5>Hello, React!</h5>
        <h6>Hello, React!</h6>
    </>
<br/>
)<br/><br/>

/* ANOTHER METHOD ---------------------*/<br/><br/>

let element1 = createElement('h1', null, 'Hello, React!')<br/>
let element2 = createElement('h2', null, 'Hello, React!')<br/><br/>

createRoot(document.getElementById('root')).render(<br/>
    [element1, element2]<br/>
)<br/><br/>


=====================================================================<br/><br/>



<mark> ----- ----- OPEN "main.jsx" FILE AND WRITE FOLLOWING CODE </mark>

- Here We are Using Two Method to Display Data on Screen.





import React, { createElement } from 'react'
import { createRoot } from 'react-dom/client'


<mark>----- ----- /* First Method */</mark>

- Here we are using <> insted of using div tag.

createRoot(document.getElementById('root')).render(

    <>
        <h1>Hello, React!</h1>
        <h2>Hello, React!</h2>
        <h3>Hello, React!</h3>
        <h4>Hello, React!</h4>
        <h5>Hello, React!</h5>
        <h6>Hello, React!</h6>
    </>

)




<img width="1920" height="1080" alt="Screenshot 2026-03-03 080845" src="https://github.com/user-attachments/assets/43fb1cd8-042f-4fda-8f8d-6cb5f9bf3aa9" />




<mark>----- ----- /* SECOND METHOD */</mark>
- Here We are creating Elements.
- We use [] To Display Both Varibles at a Time.




let element1 = createElement('h1', null, 'Hello, React!')
let element2 = createElement('h2', null, 'Hello, React!')

createRoot(document.getElementById('root')).render(
    [element1, element2]
)




<img width="1920" height="1080" alt="Screenshot 2026-03-03 083059" src="https://github.com/user-attachments/assets/e5caefae-cbad-408b-bc10-d28f052ea0c7" />

