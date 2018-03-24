# sample-hello-world-deployment-using-dockerfile

cloning:



Then follow this step to print Hello world:

1. To build the image 

        sudo docker build -t mynginx:latest .

2. Find the docker Images ID

        sudo docker images

3. Running the image

        sudo docker run -it -p 80:80 mynginx:latest

4. Open your browser - give your machine IP-address followed by port Number 80

        machine-ip:80
        
Now you can see <b>Hello-world<b> on browser.         

