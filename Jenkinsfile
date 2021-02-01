# First pull jenkins image from docker registry buy running the following command
docker pull jenkins/jenkins:lts

#Second, after pulling jenkins images, type the following command to verify that the image was successfully pulled
docker images
   or 
docker image ls  

# Third, create a container with the jenkins image. This will create jenkins server for you.
docker run -d --name (YourPreferedName) -p3000:8080 jenkins/jenkins:lts

#Explanation of the above command.
# run, starts a new container for you
# -d, runs the container in detached mode
# --name enables you to specify the name (example, Jenkins-Serever) of the container/jenkins server that you want to create. 
# -p is publish or port 
# 3000 is my prefered port number. You can choose a port number of your choice say, 7000, 9000 5000, 6000 or any if not in used already. 
# 8080 is jenkins default port number. 
# jenkins/jenkins is the jenkins images we just pulled from docker registry
# lts is the latest jenkins images in the docker registry.

#Fourth, Start your jenkins server on any browser. Type:
localhost:3000 #This will open jenkins server for you. 

#You should be asked to enter Administrator password. TO get Administrator password, type

docker exec jenkins cat /var/jenkins_home/secrets/initialAdminPassword

#This will deplay Administrator password. You will copy and paste to gain initial access to your jenkins server.
#Create admin/root account and then click on "sujected plugins" to install plugins. 

#Start bulding your projects and pipelines. 

               








