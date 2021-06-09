# To view this project:
1. Clone the repository.
2. Open terminal
3. Write `npm install -g serve` to create a static server.
4. Write ` serve -s dist` command in the terminal. It will deploy the website at [http://localhost:5000](http://localhost:5000).

# How did you decide on the technical and architectural choices used as part of your solution?

For technical part, I have created a single page application using React. React is an open-source front-end JavaScript library for building user interfaces. In react we divide the page into components. When any updating occurs in a component, only that component is re-rendered instead of reloading the whole page. It increases the speed of the application as well as user doesn't feel a thing since only a given component reloads and not the whole page. React is fast, scalable and simple. Hence, It is one of the best option for developing UI.
 
For the architecture part, project has two main folders - src and public. Public folder contains index.html and assets. Src folder contains components, css, App.js and react.js. React is basically the view part in MVC(Model View Controller) framework.

# Are there any improvements you could make to your submission?
1.Unit tests need to be covered.
2.CSS needs to be improved [trying to follow with design as much as I can].
3.Need to setup eslint and husky for pre-checking before commit.

# What would you do differently if you were allocated more time?
1.If I have had more time, i would have created the login page, created component which would provide more information about the series or movie when clicked. 
Create better css. 


