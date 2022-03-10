# FAVBooks

![App page screenshot](static/images/screenshot.png)

[View the app in Heroku here](https://my-recipe-book-a.herokuapp.com/)

## Table of Contents

1. [About](#About)
2. [User Stories](#User-Stories)
3. [Features](#Features)
4. [Data Model](#Data-Model)
5. [Testing](#Testing)
6. [Technologies Used](#Technologies-Used)
7. [Deployment](#Deployment)
8. [Credits](#Credits)



## About





## User Stories

#### User Site Stories

- As a Site User I can 


#### Admin Site Stories

- As an admin User I can 



## Features

#### Existing Features
- **Navigation Bar:** 

- **Footer:** 

-**Home Page:**

- **Login/Logout/Register:**

- **Add Recipe:**



#### Future Features



### Wireframes
Below are the initial wireframes for the site for both desktop screens and smaller devices:

**Desktop screens**

![Desktop]()

**Smaller screens**

![Mobile]()




## Data Model





## Testing




#### Remaining Bugs



#### Validator Testing

- Used [PEP8online.com](http://pep8online.com/) to validate Python code.
- User [W3C](https://validator.w3.org/#validate_by_input) to validate HTML and CSS code


##### Remaining erros





## Technologies Used

- [Gitpod](https://gitpod.io/)
- [Github](https://github.com/)
- [Unsplash](https://unsplash.com/)
- [Lucidchart](https://www.lucidchart.com/pages/)
- [Fontawesome](https://fontawesome.com/start)
- [Django](https://www.djangoproject.com/)
- [Heroku](https://id.heroku.com/)
- [Balsamiq](https://balsamiq.cloud/)
- [PEP8online.com](http://pep8online.com/)
- [W3C](https://validator.w3.org/#validate_by_input)
- [Stackoverflow](https://stackoverflow.com/)
- [Bootstrap](https://getbootstrap.com/)



## Deployment

The project is been deployed to Heroku. Steps for deployment:

- Deployment to Heroku:
    - Create an account in Heroku;
    - Create a new app in Heroku: choose a unique name and region;
    - Introduce sensitive data needed to be kept secret from the config Var tab in env.py and attach the database (Cloudinary url, Database url and Secret Key);
    - Add necessary buildpacks: Python;
    - Prepare environment and settings.py file by referencing env.py and link the database variable on Heroku;
    - Migarte all the changes;
    - Get all static and media files stored in Cloudinary by adding the cloudinary url in env.py and in Heroku, add Cloudinary to settings.py as well as telling Django, link the file to the templates in Heroku and allow Heroku as a host in Allowed_Hosts;
    - In Gitpod create the media, static and templates directories;
    - Add the project name in Procfile;
    - Make deployment commit in the terminal;
    - Manually deploy content through Heroku;
    - For deployment method, GitHub was selected and confirmed we want to connect to GitHub;
    - Connect Heroku to the repository for My Recipe Blog a;
    - Set "Enable Automatic Deploys" to allow automatic deployments every time the code is pushed;
    - Click on Deploy.
    - For final deployment:
        - In settings.py set Default = False;
        - Below add X_FRAME_OPTIONS = 'SAMEORIGIN';
        - Commit and push the changes in the terminal;
        - In Heroku, in the settings tab remove the DISABLE_COLLECTSTATIC variable;
        - In Heroku, go to the deploy tab and click on deploy branch.



## Credits

I would like to thank everyone that has supported me during the development of this project. To my family and friends for cheering me up to keep going, to my mentor Chris for guiding me through the requirements and provide me with good tips and advice and to the tutoring team at Code Institute for supporting me troubleshooting and learning how to solve issues appearing on the way.

[Back to Top ⇧](#My-Recipe-Book) 
