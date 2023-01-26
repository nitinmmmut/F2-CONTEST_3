# F2-CONTEST_3
DOM concept

javascript form validation

Project Overview Lets create a Multi Page application:

Screen 1: [5 marks] Home screen should have a signup page. It should accept, name, email, password and confirm password.

Validation : [10 marks]

Name should at least be 2 letter word Email should be validated with regex Passwords should have at least 1 capital letter, 1 small, 1 number and 1 special characters, but password cannot be the same as name or email. Password and confirm password should be the same. Also make sure that email id is not already registered.

Store data in such a way so we can access it on multiple screen [15 marks] Finally store user details as an array of objects, adding an id on our own. Eg: [{id: 1, name: “Abhishek Kumar”, email: “myemail@gmail.com”, password: “Abhishek123#!” }

When the user clicks on the submit button in the signup form these details are validated and the user should redirect to the login page. Any error in the signup page should be displayed in red colour in a paragraph. [10 marks] Login page should have email and password, make sure that when email and password are entered then person should match it with existing record. If not found => show a suitable error message. [10 marks] If found: Login success And then generate a token => a random string to 10 characters and store it as token in every user object , make sure that the token should be unique for every user. Finally redirect the user to next page called -> Your favourite and dream project chatGpt (but with more features) [10 marks] ChatGpt really and that is also more advanced. Can we really do it? Who has created this question, I don’t want to make this, such options are not allowed. Keep your mouth shut and work. In this next page : Sample Data for this page: [5 marks]

You need to create an array of objects (create some sample data) Every object will have three things: {question: “What is a dog” , answer: “Dog is a animal with 4 legs”, imageLink = “dog.jpg”} Stock up some questions, answers and its image in the array of objects

Create a textbox in page and submit button, people can write the questions in textbox:, [5 marks]

If the question matches with any of the questions in the array, display its answer and image after the user clicks on the submit button. [5 marks]

Once the answer is visible then a new input box and a button(speakText) should be visible. Input box is where people can write his token. [10 marks]

When speak button is clicked: [15 marks]

Token should be verified, if verified display his name and a variable(“number of calls left”) By default every user who Login will get 10 calls to text to speak feature, that means he can max use speakText feature for 10 times. Number of calls variables should show the number of calls remaining everytime speakText button is clicked. If the token is not verified, display a suitable message.
