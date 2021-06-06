# To view this project:
1. Clone the repository.
2. Open terminal
3. Write `npm install` command in the terminal to install the dependencies.
4. Write `npm start` command in the terminal. It will open the website in developement mode at [http://localhost:3000](http://localhost:3000).


# How did you decide on the technical and architectural choices used as part of your solution?

For technical part, I have created a single page application using React. React is an open-source front-end JavaScript library for building user interfaces. In react we divide the page into components. When any updating occurs in a component, only that component is re-rendered instead of reloading the whole page. It increases the speed of the application as well as user doesn't feel a thing since only a given component reloads and not the whole page. React is fast, scalable and simple. Hence, It is one of the best option for developing UI.
 
For the architecture part, project has two main folders - src and public. Public folder contains index.html and assets. Src folder contains components, css, App.js and react.js. React is basically the view part in MVC(Model View Controller) framework.

# Are there any improvements you could make to your submission?
It was a pretty straight forward task, we had to create web app with 3 screens and an API feed. The website fetches the data from JSON file and shows it in the pages. Currently I have saved the json file locally in the folder but I can make it more general by connecting it with server and storing all the assets there. 

# What would you do differently if you were allocated more time?
If I have had more time, i would have created the login page, created component which would provide more information about the series or movie when clicked. 


