<!-- ----- ----- OPEN "main.jsx" FILE AND WRITE FOLLOWING CODE -->

- Here We are Using Two Method to Display Data on Screen.





import React, { createElement } from 'react'
import { createRoot } from 'react-dom/client'


----- ----- /* First Method */

- Here we are using <> insted of using <div> tag.

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




----- ----- /* SECOND METHOD */
- Here We are creating Elements.
- We use [] To Display Both Varibles at a Time.




let element1 = createElement('h1', null, 'Hello, React!')
let element2 = createElement('h2', null, 'Hello, React!')

createRoot(document.getElementById('root')).render(
    [element1, element2]
)




<img width="1920" height="1080" alt="Screenshot 2026-03-03 083059" src="https://github.com/user-attachments/assets/e5caefae-cbad-408b-bc10-d28f052ea0c7" />

