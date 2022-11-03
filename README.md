# ToDoList
This application is a to do list. User can write a new todo item and press enter and then that item will be added to the todo list. To remove an item from the list, user can just click on that item and it will be removed from the list.
The rendering part of the application has 2 React components - Todo and ToDoForm. Todo removes the given item using its index from the array of items. TodoForm component is written in form.js file. This component adds the new item to the list on pressing enter. 
The styles of the list are in styles.css.

How to Run: Clone the repository on your local machine in a directory. Install http-server in that directory using the following command:
npx install --global http-server 
Then run http-server using the command: 
http-server ./ 
The server would be running at https://localhost:8080 as mentioned in the terminal after you run the server. In a browser, type https://localhost:8080 and press enter and you can see the todo list.
