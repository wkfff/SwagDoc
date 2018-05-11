# SwagDoc
SwagDoc is a Delphi library to generate swagger.json file for Swagger Spec version 2.0. Create a public documentation REST API using Swagger 2.0 for Delphi Language. The swagger.json file is responsible for containing all the documentation for your REST API. This file must be attached to the Swagger UI (User Interface) files. SwagDoc's only responsibility is to generate the swagger.json file.

## Swagger - version 2.0

The main prerequisite for working with SwagDoc is to know the Swagger 2.0 specification that can be viewed in the link below.

https://github.com/OAI/OpenAPI-Specification/blob/master/versions/2.0.md

When creating a Swagger documentation for your REST API you can produce a page like the following example.

![image](https://user-images.githubusercontent.com/20048296/39936694-a4d9ac9a-5523-11e8-8161-98d0e396eb6f.png)
http://petstore.swagger.io


For you to produce a page containing a Swagger documentation you need the Swagger UI distribution files.

These files you can find in the github swagger-api / swagger-ui repository.

https://github.com/swagger-api/swagger-ui/tree/master/dist

![image](https://user-images.githubusercontent.com/20048296/39937130-2925f868-5525-11e8-921d-c9ff0f59fefd.png)


First you need to download the swagger user interface files and generate the swagger.json file. You then need to change the index.html file to indicate the relative path of the location where the swagger.json file is located on your web server that is hosting the swagger user interface files.

See an example below.

![image](https://user-images.githubusercontent.com/20048296/39946376-49ad0df0-5544-11e8-8a5c-0980f5e6c257.png)
