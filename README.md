# ToDoList
<p>This mini project was made to demonstrate my skills with node.js, express.js EJS SQL and PostreSQL to make applications. My main focus in this project is to show my understanding of CRUD (Create, Read, Update, Delete) operations with databases. The project run is shown below:</p>

https://github.com/user-attachments/assets/a1c5eab1-5361-4f44-b465-75777409ad3e

<h3>How it works</h3>

<p>When the plus button is clicked it triggers a post request to my express server where the requests body is parsed, the form data is read and inserted into my PostresSQL database hosted loclally (C). The express server reads the database and shows the data in the database with a checkbox and a edit button (R). If the user would like to edit an entry they click the pencil and a input string shows up where they can edit the current entry and confirm it. This sends another post request to the express server which then updates that entry in the database (U). If the user has done the task and want to remove it they click the checkbox and it sends a post request to the express server to delete the entry from the database (D). After any operation the user is redirected so that the page updates with the new data added, edited or removed.

Whenever buttons are pressed different html elements are hidden using javascript methods that can be seen at the bottom of the index.ejs file.</p>

<h3>Running the project</h3>

<p>If youd like to run this project you would need to have node and PostreSQL installed on your computer. You would then use npm i to install all required packages from the node package manager. Once that is done you would need to open pgAdmin and create a table called items with 2 columns, 1 being id which is the primary key represented as an inter and is serial to auto increment id for every entry and the second column being title represented as text. Once all of that is done you would need to change the password at the top of the index.js file to correspond with your PostgreSQL password and run the file. </p>

