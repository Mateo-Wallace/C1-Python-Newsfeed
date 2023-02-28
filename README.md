<p id="readme-top"></p>

[![License Shield](https://img.shields.io/badge/License-MIT-success?style=for-the-badge)](./LICENSE) [![LinkedIn Shield](https://img.shields.io/badge/LinkedIn-555555?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/mateo-wallace/)

# Python Newsfeed

## Description

Python Newsfeed is blog that allows users to post links to Tech News. Other uses can comment and upvote those posts. It was made in order to practice Python backend using Flask.

While building this project I learned to:

- Structure Python code using indentation
- Create an API in Python
- Utilize a virtual environment to store pip packages
- Send information to the front end using Python

### Built With

[![Python Shield](https://img.shields.io/badge/Python-3776AB?&style=for-the-badge&logo=python&logoColor=white)](https://www.apollographql.com/)
[![Flask Shield](https://img.shields.io/badge/Flask-000000?&style=for-the-badge&logo=flask&logoColor=white)](https://flask.palletsprojects.com/en/2.2.x/)
[![Jinja Shield](https://img.shields.io/badge/Jinja-B41717?&style=for-the-badge&logo=jinja&logoColor=white)](https://jinja.palletsprojects.com/en/3.1.x/)
[![MySQL Shield](https://img.shields.io/badge/MySQL-4479A1?&style=for-the-badge&logo=mysql&logoColor=white)](https://dev.mysql.com/doc/)
[![SQL Alchemy Shield](https://img.shields.io/badge/SQL_Alchemy-d71f00?&style=for-the-badge&logo=mysql&logoColor=white)](https://www.sqlalchemy.org/)

## Table of Contents

- [Usage](#usage)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Usage

Navigate to [c1-python-newsfeed.herokuapp.com/](https://c1-python-newsfeed.herokuapp.com/) in order to see the site. You will be presented with the homepage that displays all users posts, it should look something like this:

![example of deployed site](./app/utils/assets/deployed.png)

The site will display the title, creator, points, and amount of comments a post has. By clicking on the title of the post you will be directed to the news article. By clicking on the comments you will be directed to the singular post and all of its comments.

In order to make a post you must either signup or login, you can do this by clicking the login button on the top right. 

Once you are logged in if you select your dashboard in the top right that is where you will be able to make a post. Also while logged in you can view other peoples posts and comment or upvote on them.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Installation

If you would like to download the project locally:

1. Fork the Project
1. Clone the Repo to your machine
1. Rename the `.env.example` file to just `.env`
1. Adjust the `DB_URL` variable so that where `mysql+pymysql://root:<password>@...` says `<password>` is replaced with your local mysql password. For example `mysql+pymysql://root:mypassword123@...`
1. Open your terminal, preferablly `powershell` as `git bash` will not work. Begin your virtual environment by in the command line running `python -m venv venv`
    >**NOTE**
    >
    >In order to activate your virtual environment run `.\venv\Scripts\activate` and to deactivate run `deactivate`. 
    >
    >This is best practice when working with the application so you do not download any packages globally to your computer.
1. Download the Python requirements for your project by running `pip install -r requirements.txt`
1. To begin the server run `python -m flask run`
1. To view the website navigate in your browser to `http://127.0.0.1:5000/`
    >**NOTE**
    >
    >Upon first viewing your version of the website their will be no data presented. Should you wish to have data pre filled run `python seeds.py` in order to seed data such as users, posts, comments, and votes.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contributing

If you have a suggestion that would make the repo better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!

1. Fork the Project
1. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
1. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
1. Push to the Branch (`git push origin feature/AmazingFeature`)
1. Open a Pull Request

If all of this is new to you take a look at the [GitHub Docs](https://docs.github.com/en/get-started/quickstart/fork-a-repo).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## License

Distributed under the MIT License. See [LICENSE](./LICENSE) for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contact

Mateo Wallace - [GitHub](https://github.com/Mateo-Wallace) - [Email](mailto:mateo.t.wallace@gmail.com) - [LinkedIn](https://www.linkedin.com/in/mateo-wallace/)

Project Link: [MP2-Discord-DumBot-V2](https://github.com/Mateo-Wallace/MP2-Discord-DumBot-V2)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
