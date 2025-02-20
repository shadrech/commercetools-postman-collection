# Getting started with the commercetools Postman Collection.

## What are Postman Collections?

Postman is an API platform that helps you quickly use REST APIs without requiring any development work. Postman Collections are a group of saved API requests that you can import into the Postman app.

## commercetools API collections

* [Platform API](api/)
* [Import](import/)
* [Machine Learning](ml/)

## Install Postman App

Instructions for installing the Postman app or using the web version can be found at https://www.postman.com/downloads/

## Setting Up Enviornment
Every root folder in [Platform API](api/), [Import](import/)
, [Machine Learning](ml/) contains a template.json file. Import this file from the Environments tab.

![image](https://user-images.githubusercontent.com/4946943/141699003-e989317e-41dc-42c9-b682-eb97f6c8fe6d.png)

This will create an empty variable set environment. 
![image](https://user-images.githubusercontent.com/4946943/141699543-9f626cd3-5dcf-4b8d-94ad-f0045fc15b44.png)


Set the initial values for primary variables.
* host : The host information can be [found here](https://docs.commercetools.com/api/general-concepts#hosts)
* auth_url : The Authorization URL can be [found here](https://docs.commercetools.com/api/authorization#requesting-an-access-token-using-commercetools-oauth-20-server)
* client_id : From your API Client. More information can be [found here](https://docs.commercetools.com/merchant-center/api-clients#create-an-api-client)
* client_secret : From your API Client
* project_key: your project key


## Import commercetools Postman collection

Every root folder in [Platform API](api/), [Import](import/)
, [Machine Learning](ml/) contains a collection.json file. Use these files to import into the Postman app.

![image](https://user-images.githubusercontent.com/4946943/141699715-cbf64f9e-945b-42c1-ae8f-8de0cf892937.png)

You should be able to see the collection imported. If you expand the collection, there are two primary folders:
* Authorization - Use "Obtain access token" to get an authentication token.
* Projects - Explore endpoints and it is ready to use.

 
