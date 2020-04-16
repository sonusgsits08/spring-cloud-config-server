# Read Me First
*****************************
This project is to externalize properties & store at central location. client does not need to bother
about properties being stored. spring-cloud gets these properties for client.
 
to run this project you need to perform below steps:

1# create a local/remote repo and place limits.service.properties file under it.
2# add few properties limits-service.minimum ,limits-service.maximum in this file
3# commit this change & restart client changes will be reflected into client side.
4# start spring-cloud-config-server and then start limits-service
5# GET: http://localhost:8081/configServer/limits   will show you the properties minimum & maximum placed in local/remote repository.
