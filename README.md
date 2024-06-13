Steps for this Demo:  
step 1: Create a nodejs web app   
step 2: use docker to create a containerimage of the app and push it to dockerhub   
step 3: used eksctl to create a kubernetes cluster in AWS EKS composed of 3 worker EC2 nodes  
step 4: created a kubernetes deployment file and configure it to run the docker container inside pods on the 3 worker nodes 
