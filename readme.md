# URL cutter

<img src="https://github.com/lestec-al/url-shortener-django/blob/master/url1.png" width="640" height="360"/>
<img src="https://github.com/lestec-al/url-shortener-django/blob/master/url2.png" width="640" height="360"/>

Link shortening service on Django. Features:
- final link is not short because the test host is long
- accounts for users
- for all users cut your link to unique link (that link redirect to your link)
- for registered users page with links (search by original links, ability delete links and rename link part, clicks counter, time created)
- used bootstrap front-end framework

# To run on a local server you need:
- install Python (v3.9 or higher)
- download or clone this project
- through the command line, go to the project folder and type (press enter after each command): 'pip install -r requirements.txt', 'python manage.py makemigrations', 'python manage.py migrate', 'python manage.py runserver'