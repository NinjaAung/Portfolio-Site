# Portfolio-Site

1. How is this project structure different than a Flask (or Node) application? What role are the urls.py and views.py files responsible for?

route connection are not decorators [@ function] and MVC are differnt as well. instead of having multiple routes within a project we have multiple apps responsible for viewing and connecting info and a urls.py unique to each app 


2. Why do we use 2 separate urls.py files? How do they interact?

primarily to organise our routes and application they provided valid routes and the correspounding respounces to each route

3. (5 Points) When is it desirable to split our code over multiple apps? Why would we want to do so?

If we split code amongst multiple apps it provides perfect organization and allow the web app to scale larger and larger and each function will work properly.

