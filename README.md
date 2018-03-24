# Deploying hello-world image using dockerfile

For this First to nedd to install docker-ce.
    
      curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
      sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
      sudo apt-get update
      apt-cache policy docker-ce
      sudo apt-get install -y docker-ce

cloning:

    git clone https://github.com/Renuka-chowdary/sample-hello-world-deployment-using-dockerfile.git


Then follow this step to print Hello-world:

1. To build the image 

        sudo docker build -t Hello-world:latest .

2. Find the docker Images ID

        sudo docker images

3. Running the image

        sudo docker run -it -p 80:80 Hello-world:latest

4. Open your browser - give your machine IP-address followed by port Number 80

        machine-ip:80
        
Where you can see output as <b>Hello-world<b>         

