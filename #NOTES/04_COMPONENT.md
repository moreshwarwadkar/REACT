<mark>----- COMPONENT -----<mark>
</br>
</br>
- Create Component Folder in `'src'`. (First Letter Should be Capital)
- Inside that Folder Create a Component File. (First Letter Should be Capital)
- In Our Case We Have Created `ComponentA.jsx`.( FileName With Extention .jsx)
- Inside That File Write Following Code.
</br>
</br>
</br>

<img width="1920" height="1080" alt="Screenshot 2026-03-03 085412" src="https://github.com/user-attachments/assets/54558818-94d9-4bc2-b03d-e6432e7ba6b1" />
</br>
</br>
`class ComponentA` : Here We can give any name to the class.</br>
`export default ComponentA` : This is Important Line. This will export data. By using this we can access this class in another file.
</br></br>

<img width="1920" height="1080" alt="Screenshot 2026-03-03 085809" src="https://github.com/user-attachments/assets/7741a984-e143-40a4-9b27-60e8e49858ec" />

</br></br>
- To Access this in `main.jsx` File, We have to import First : `import ComponentA from './Components/ComponentA';`
- Then we have to write a Class Name in Angular Brackets.
- Here we have to ways to write `1) <ComponentA/>  ` `2) <ComponentA></ComponentA>`
