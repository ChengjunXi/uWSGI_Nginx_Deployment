# uWSGI_Nginx_Deployment
A Load-balanced deployment of a Python Django project with uWSGI and Nginx . The basis Django project is from https://github.com/PacktPublishing/Django-2-by-Example with MIT license that is also included in this directory.

## Demonstration
There are 2 service providers on port 8001 and 8002, each with 2 threads.

![捕获](https://github.com/ChengjunXi/uWSGI_Nginx_Deployment/assets/93487110/98049c6f-ec39-4512-8aa5-5bd4e489f461)

The 3 requests are distributed to the 2 service providers based on polling.

![捕获1](https://github.com/ChengjunXi/uWSGI_Nginx_Deployment/assets/93487110/1ab245da-3e6b-41d4-a607-5cc22231fdb1)



