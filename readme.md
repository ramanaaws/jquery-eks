aws ecr get-login-password --region us-east-2 | sudo docker login --username AWS --password-stdin 590779969216.dkr.ecr.us-east-2.amazonaws.com



sudo docker build -t 590779969216.dkr.ecr.us-east-2.amazonaws.com/jquery-eks:1

sudo docker push 590779969216.dkr.ecr.us-east-2.amazonaws.com/jquery-eks: