----- COMPONENTS :</br>
- React Components are a Core Building Block of any react application.</br>
- Components are reusable block of code that can be imported and exported.</br>
- Webpages are divided into multiple components/Files which are join together in the parent component.</br></br>


----- Rules Of Component : </br>
1) Component Name Should Start With Capital Letter</br>
2) Components File Should be save with .jsx extention.</br>
3) Components Can Be Represented in Two Ways : 1) Paired Tag 2) Self Closing Tag.</br></br>



----- Types of React Componenets :</br>
1) Function Based Component</br>
2) Class Based Component</br></br>


----- ----- (1) Class Based Component :</br></br>

- It uses ES-6 Classes.</br>
- React Library must be imported.</br>
- Requires inheritance from React.Component.</br>
- React.Component is a Base Class where all the methods and property exist.</br>
- Whenever we are using CBC (Class Based Component) render() is mandatory.</br></br>


----- ----- (2) Function based component :</br></br>

- Function Based Components are JavaScript Functions that returns jsx elements.</br>
- Function Based Components are simpler than Class Based Components and Widely used in Modern React Application.</br>
- Before React Hooks they ware Stateless Functionalities.</br>
- With Hooks Function based Components can manage state and life cycle behaviour.</br>
- Mostly we are using Arrow Function for Function Based Component.</br></br>


Q.1) Difference Between Class Based Component and Function Based Component.</br></br>

- CBC : It uses ES-6 Classes</br>
- FBC : It does not uses ES-6 Classes.</br></br>

- CBC : React Library Must be Imported.</br>
- FBC : React Library Not Required.</br></br>

- CBC : We Need to Inherit React.Component.</br>
- FBC : No Need to Inherit.</br></br>

- CBC : Render() Method is Mandatory.</br>
- FBC : Render() is not Mandatory.</br></br>

===================================================================</br></br>



<mark>----- COMPONENT -----<mark>
</br>
</br>
- Here We have a Two Types :</br>
  1) Class Based Component (CBC)</br>
  2) Function Based Component (FBC)</br></br>
</br>
</br>
================================================</br>
  1) Class Based Component (CBC)</br></br>

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

</br></br>
================================================</br>
2) Function Based Component (FBC)</br></br>
- In Function Based Component (FBC) we have same Steps. (DIFFERENT CODE)</br></br>

<img width="1920" height="1080" alt="Screenshot 2026-03-11 193236" src="https://github.com/user-attachments/assets/62826bb1-a932-403f-893a-fb65046839c5" /></br></br>

<img width="1920" height="1080" alt="Screenshot 2026-03-11 193542" src="https://github.com/user-attachments/assets/7a3636fb-e67e-4ee6-bc59-b1b0d65960c0" />
