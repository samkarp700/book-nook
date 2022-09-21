# Book Nook
![Book Nook - Travel to the stars, Read!](/../main/public/images/booknook-readme-banner.png)

## Description
This application is designed to provide a platform and community for parents and/or teachers of young readers. This platform is designed to allow parents to discover and discuss new reads for their child based on the individual reading level and interest. The main features of the application include account registration, access to database of books, and post comments reviewing the existing books. 

## Deployed Application
[Book Nook](https://booknook-stars.herokuapp.com/)

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Tests](#tests)
- [Technologies Used](#technologies-used)
- [Contributors](#contributors)

## User Story
```
AS A parent who has a child that loves to read
I WANT a discussion website
SO THAT I can connect with other parents to get book recommendations for my child
```

**ACCEPTANCE CRITERIA:**
```
GIVEN a discussion website
WHEN I visit the site for the first time
THEN I am presented with the homepage, which includes a signup or login options
WHEN I choose to sign up
THEN I am prompted to create a username and password
WHEN I click on the sign up button
THEN my user credentials are saved and I am logged into the site
WHEN I am logged in to the site
THEN I am presented with book posts and the number of comments, and the option to log out
WHEN I view an existing blog post
THEN I am presented with the book title, author, genre, lexile level, and summary
WHEN I click on an existing blog post
THEN I have the option to leave a comment
WHEN I enter a comment and click on the submit button while signed in
THEN the comment is saved and the post is updated to display the comment, the comment creator's username, and the date created
WHEN I click on the logout option in the navigation
THEN I am signed out of the site
WHEN I am idle on the site for more than a set time
THEN I am able to view posts and comments but I am prompted to log in again before I can add comments
```

## Installation
1. To install this application, `git clone` this repository, or download the `.zip` file in the dropdown after clicking the green ‘Code’ button at the top of this repository—as long as it is in your local branch.
2. Ensure Node.js is installed in your operating system.
3. Install ***all*** of the dependencies listed in the [technologies used](#technologies-used) via command-line in terminal.
3. Initialize MySQL by running `mysql -u root -p`, and enter your password when prompted. Once loaded, enter `SOURCE db/schema.sql;` to create the database. Exit MySQL by entering `quit;` in terminal.
4. Run `npm run seed` to seed the database.
5. The application can be accessed by visiting `http://localhost:3001` in the browser after running the following command:
```
npm start
```
6. [Insomnia](https://insomnia.rest/) or [Postman](https://www.postman.com/) can be used to check the backend functionality.

## Technologies Used
- HTML
- CSS / [Bootstrap](https://getbootstrap.com/)
- JavaScript / [jQuery](https://jquery.com/)
- [Node.js](https://nodejs.org/en/)
- [MySQL](https://dev.mysql.com/doc/)
- Dependencies: [MySQL2](https://github.com/sidorares/node-mysql2#readme), [Sequelize](https://sequelize.org/), [Express Handlebars](https://github.com/express-handlebars/express-handlebars), [express-session](https://github.com/expressjs/session#readme), [connect-session-sequeilize](https://github.com/mweibel/connect-session-sequelize), [dotenv](https://github.com/motdotla/dotenv#readme), [node.bcrypt.js](https://github.com/kelektiv/node.bcrypt.js#readme), [Passport.js](https://www.passportjs.org/), [passport-local](https://github.com/jaredhanson/passport-local#readme)

## Contributors
- Demi Hayashi - [demivlkv](https://github.com/demivlkv)<br />
- Sam Karpovck - [samkarp700](https://github.com/samkarp700)<br />
- Mary Paul - [marymc13](https://github.com/marymc13)<br />
- Boris Habimana - [Borishabimana773](https://github.com/Borishabimana773)

## ScreenShots from  the site: 
![Screen Shot 2022-09-20 at 8 17 57 PM](https://user-images.githubusercontent.com/105761973/191387597-f877118e-636e-4546-8efd-79a6bccb5e42.png)

![Screen Shot 2022-09-20 at 8 18 07 PM](https://user-images.githubusercontent.com/105761973/191387602-80e0f46b-0ce9-4ebf-ad8a-4c3fb44ccf84.png)

![Screen Shot 2022-09-20 at 8 19 10 PM](https://user-images.githubusercontent.com/105761973/191387615-8aded240-9d2f-414f-9441-30cf2bd72bf8.png)
