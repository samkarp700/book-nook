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
