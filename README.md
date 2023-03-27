# ToDo-Django-React.js-App

### Initial challenge and requirements> ###
- A Full-stack todo app must be developed using Django and React. In this web application the user must be able to manage, view, and edit their commits or tasks.
- The app must be user-firendly and efficient.
- The app must compile with the highest code quality in the industry.
- A database of free election must be used.

### The app ###
Since the app is fullstack, it can be divided in two main branches, backend and frontend. In the main backend file, an inner folder named the same (backend) contains the settings and configuration of the app such as `settings.py`, `urls.py` among others. It is to note that the SQL chosen was MySQL, and the use of it can be seen in the database section in the `settings.py` file that controls the overall Django technology. Also, in the "todo" folder are contained the views, methods, admin and serializers as well as migrations of the app itself that are innate of Django.
Moreover, in the frontend main folder, the "src" folder contains the application itself, wirtten mainly in JavaScript and CSS, in which the _React_ framework is invoked. The "components" subfolder contains the model of the react JavaScript file. In adition, the packages that are not enclosed in more folders are the register of the frameworks and languages the app contains.
Overall, the application is written in languages such as Python, SQL, JavaScript, CSS, and HTML, and it uses modules such as node.js, react.js, bootstrap, Django, crosheaders, rest framework, API and axios.

### Instructions ###
It is of vital importance to have a local environment in which the app can run, this because it does not contain a public nor private domain and needs to be run from a localhost. The required modules, installations and languages are the ones the app uses that were previously mentioned. In order to run the backend, enter `python manage.py runserver`* in the terminal and in frontend `npm start`. The app should pop up in the tester-s default browser of a localhost link should be shown.

**Note: make sure that the server will run in the correct environment both in front and backend (suggestion: use `cd` commands to navigate in the folders and consider using `pipenv shell` or `pipenv run` terminal commands to enter such environments)

