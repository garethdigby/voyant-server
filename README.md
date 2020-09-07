# voyant-server
Dockerfile for Voyant Server, a web application for Voyant Tools. [https://github.com/sgsinclair/VoyantServer](https://github.com/sgsinclair/VoyantServer)

## Supported version  

2.4m45  

# How to Use this image  

Pull the docker image.  

`$ docker pull garethdigby/voyant-server`  

Run docker, mapping container port 8080 to host port 8080.  

`$ docker run -d --name voyant-server -p 8080:8080 garethdigby/voyant-server:2.4m45`  

You access Voyant Tools on your local machine at [http://localhost:8080/voyant](http://localhost:8080/voyant).  


# Bibliography  
sgsinclair's [Voyant Server](https://github.com/sgsinclair/VoyantServer)  
sepastian's [VoyantServer - Docker](https://github.com/sepastian/voyant-docker)  
