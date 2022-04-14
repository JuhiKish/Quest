I have created an Ec2 instance and a security group using on AWS using IAC CloudFormation template.
Installed docker on the ec2 instance and started the service.
I am unable to locate which app I am supposed to copy to the container because I do not see any artifact on git repositiory
I have also installed an httpd on Ec2 host and created one index.html file which I am able to view on http://3.235.156.47
I have written one docker file to copy the Ec2 host content to the docker container and expose the container port to 80 and via port mapping, we should be able to view the web app running on container from outside world.

