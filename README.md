### This document assumes you know fundamentals of programming, python and data structures. 

#### Preface:

1. How internet works generally?
    1. HTTP protocol
    2. Request / Response flow
2. What is an API / REST API?
3. HTTP Verbs
4. Status Codes
5. What is JSON & Serialization?
6. How to install linux alongside windows?
7. What is linux and distributions?
8. Basic linux commands & package manager fundamentals


#### Basic Concepts:

9. What is a database (relational)? (Table, Row, Column)
10. What is a framework and why use a framework at all?
11. Install django,django rest framework & virtual environment
12. Start django project
13. Django project structure
14. Settings file
15. Why using a VCS?
16. What is git?
17. Git staging git commit
18. Creating models
19. Migrations
20. Django admin panel
21. Basic APIView & JSON serializing
22. Registering view in url dispatcher
23. Calling API with postman


#### API In Depth:

24. ModelSerializer
25. CRUD, Different view types & http verbs
26. Different database relations
27. Writing models with relations
28. CRUD for endpoints with relations
29. Using urls.py file in every django app
30. ModelViewSet
31. DRF Router & browsable api
32. .gitignore / ssh key / git push / git pull / origin


#### API In Depth 2:

33. API design principles
34. HyperlinkedModelViewSet
35. DRF serializers in depth (Relations, Nested Serializers, List Serializers ...)
36. Git branching / git stash / git merge / git mv / git rm
37. Filtering & Paginating results
38. Documenting endpoints with OpenAPI / Swagger
39. Different DBMS (PostgreSQL, SQLite, MySQL, ...)


#### User Management System:

40. Authentication Vs. Authorization
41. Different authentication types (Session Based, Token Based, OAuth2)
42. What is JWT and how it works
43. Django_rest_simplejwt package and basic user log in
44. Authentication classes & permission classes
45. Protected API endpoints


#### Software Testing:

46. Python unittest package
47. Python requests package
48. DRF test framework
49. Unit Test Vs. Functional Test
50. APIClient, APITestCase, RequestsClient, APILiveServerTestCase
51. Python coverage package
52. Increasing code coverage with more tests


#### Performance Tuning:

53. What is caching?
54. Why should we cache?
55. What is redis?
56. Django cacheops cache invalidation
57. Installing npm & required configs
58. NPM loadtest package & benchmarking
59. Lazy Querysets


#### More Advanced Topics:

60. Database Indexing (performance)
61. Custom User Model
62. CORS issues & working with client side applications
63. Email Queuing
64. Celery
65. RabbitMQ | Message Broker | Queuing systems
66. Celery beat
67. Celery execution pools
68. Async I/O and it's combination with celery
69. OS Daemons and Celery Daemonization


#### Some nice to have Operation/DevOps related knowledge:

70. WSGI and unix sockets
71. NGINX and web servers
72. DNS
72. Deploy django backend on fresh ubuntu server
73. Docker & Containerization
74. Docker Compose

### Interview question
#### Python-specific:

1. What do you like about Python?

2. What is your favorite Python package (third-party or built in)?

3. Are you familiar with PEP8? Can you explain what it is and why it is helpful? How do you document your code?

4. What is the difference between a __docstring__ and a comment?

5. What is a tuple?

6. What is a list, and why would you use it over a tuple?

7. Have you ever used list comprehensions? If so, can you give an example of a use case?

8. Are you familiar with decorators? If so, can you explain what they are and why/where they would be used?

9. Are you familiar with generators? If so, what is the advantage of using them?

10. How good are with regex?

#### Django-specific:

1. Are you familiar with the term MVC? Can you explain how this is similar to Django?

2. Explain models, views, and templates. How do they work together?

3. Explain the ORM.

4. What is a QuerySet?

5. Explain how to filter QuerySets.

6. Are you familiar with Class-Based Views? What are their advantages/disadvantages?

7. How would I display the variable "section" in a django template, assuming that the variable is a string?

8. Explain how MVT differs from traditional MVC.

9. Explain difference between Forms and ModelForms? When you should use which?

10. Describe request object and it's main features.

11. Explain Cross-Site Request Forgery (CSRF), and how Django prevents it.

12. Walk me through what happens between when I type the URL into my browser and when the response is rendered. Your answer should be as detailed as possible. 

13. What is work of middleware and decorators ? What is their difference ?? how you will create these 2 .

14. Explain complete process (what happens inside) of models and migrations .

15. Why is MongoDB a bad choice to use with Django.

