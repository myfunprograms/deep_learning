This is the repo for projects of the Deep Learning course.

### Steps to run the IPython notebook
Go to the projectX directory
<br>1. Change the volume mapping in the docker-compose.yml to be a directory on your machine.
<br>2. Create / Start a docker machine.  
For example,    
`` docker-machine create -d virtualbox conda``  
`` eval $(docker-machine env conda)``
<br>3. Go to the root of the project, run the following command.  
 ``docker-compose build``  
 ``docker-compose up``
 
### Projects
Project 1. First nerual network
<br>
Project 2. Image classification 
