# Hello-world image deployment using docker file

Deploying hello-world image using dockerfile

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

