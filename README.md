# full-stack-app-love-notes

This is a full-stack appliaction where the user can draft love notes/letters. It is intended to allow the user to get their thoughts out. The user can read and edit the notes that they have created. 

Link to Project: https://full-stack-love-note.herokuapp.com/

![Project Image](/public/img/projectScreenshot.png)


### How It's Made:

This project uses EJS, CSS, and JavaScript on the front-end and Node.js + Express.js, and MongoDB on the back-end. 

The user fills out their note and submits it. This submission is sent as a request to the server. The details of their note is sent and stored to a database in MongoDB. Then, the server requests the data from the database, the data is sent as a response to the front-end so that the information can be rendered dyanmically through EJS. 


### Lesson Learned

I learned how to use CRUD functions to operate on stored data in MongoDB. Also, I learned how to use EJS, a simple templating language that allow us to generate HTML markup with Javascript.  
 

###
