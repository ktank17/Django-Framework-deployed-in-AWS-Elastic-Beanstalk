# Django-Framework-deployed-in-AWS-Elastic-Beanstalk

## Project Proposal:

#### Title of Topic: 
Implementing ToDo CRUD App using Django Framework deployed in AWS Elastic Beanstalk 

#### Implementation:
- We will be creating a To-Do application using the Django framework. Creating an app where we can add new items to the list ,editing and deleting items from the list once the work gets completed.
- Django runs on an MVT (Model View Template) system. So for the To-do application, we use models, views, crud operations, url routing, DTL (Django Template Language) and some basic settings.
- Here is the sample screenshot of how the view page of Todo app looks. 

![Screenshot (189)](https://user-images.githubusercontent.com/54612462/95407487-ffef6c00-08d1-11eb-8ca5-bed39be35a9f.png)

- To add todo, enter the description, select category, select the due date and click on Add Task.
- For deleting any todo, just click on it and select the Delete task.

#### Authors:
- Krishna Tank 
- Apurva Siddappa Raj
- Riny George

#### Introduction:
- Django is a Python-based free and open source web framework that follows the Model-View-Controller (MVC) architectural pattern
- Django's primary goal is to ease the creation of complex, database-driven websites. The framework emphasizes reusability and pluggability of components, less code, low coupling, rapid development. Python is used throughout, even for settings files and data models. Django also provides an optional administrative create, read, update and delete interface that is generated dynamically through introspection and configured via admin models.
- Django framework allows developers to focus on components of the application that are new instead of spending time on already developed components. Django is fully featured than many other frameworks on the market. It takes care of a lot of hassles involved in web development; enables users to focus on developing components needed for their application.

#### Table of Contents:
###### What is Django Framework?
Django is an open-source python web framework used for rapid development, pragmatic, maintainable, clean design, and secure websites. A web application framework is a toolkit of all components needed for application development.
###### Django Installation and First Project
Installing Django in a virtual environment and then creating the first Django Web application.
###### Django Models and Admin
A model in Django is a special kind of object – it is saved in the database. A database is a collection of data. This is a place in which you will store information about users, your blog posts, etc. To add, edit and delete the posts we've just modeled, we will use Django admin.
###### Django URLs and Views
A view is a place where we put the "logic" of our application. It will request information from the model you created before and pass it to a template.
###### Django ORM and Quesryset 
Django connects to the database and stores data in it. A QuerySet is, in essence, a list of objects of a given Model. QuerySets allow you to read the data from the database, filter it and order it.
###### Django Forms
The final thing we want to do on our website is create a nice way to add and edit blog posts. Django's admin is cool, but it is rather hard to customize and make pretty. With forms we will have absolute power over our interface – we can do almost anything we can imagine!
###### Deploying Django to AWS
Deploy an example Django-based application onto Lightsail. You start by creating the instance, and deploying your application. Next, you ensure the application is running correctly using Django's built-in web server. Finally, you configure Apache to host the application.
###### The Future and Conclusions
Django is very popular and used by a large number of developers. It is becoming more popular every day and releasing new features. It’s better and there are more jobs for Django developers.
###### Django VS Flask
Django is a full-stack web framework for Python, whereas Flask is a lightweight and extensible Python web framework. Django is developed based on batteries-included approach. It enables programmers to accomplish common web development tasks without using third-party tools and libraries. The features provided by Django help developers to build large and complex web applications. On the other hand, Flask accelerates development of simple web applications by providing the required functionality. 

###### References: 
https://en.wikipedia.org/wiki/Django_(web_framework)
https://tutorial.djangogirls.org/en/django/ 
https://medium.com/@sagarajkt/what-is-django-and-why-is-it-used-2dafdc75ce67 
https://medium.com/@epythonguru/the-future-scope-of-python-django-web-development-6817dde8b24b 
https://aws.amazon.com/getting-started/hands-on/deploy-python-application/
https://realpython.com/deploying-a-django-app-and-postgresql-to-aws-elastic-beanstalk/
https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/create-deploy-python-django.html
