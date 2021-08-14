# php-docker
A simple docker for easy running php sites


## Instructions for running

1. Install docker into your system. 

2. clone this repo 
`git clone https://github.com/joetorres/php-docker.git`

3. Navigate to the directory
`cd php-docker`

4. Build the image
`docker build . -t php-site:latest`

5. Run a container with your website as a mounted volume. 
`docker run --name awsome-website -p 8080:8080 -v /path/to/your/php/project:/var/www/html php-docker`

Thats it. Enjoy.
