# panoptes-docker

* Specs
  - Ubuntu 16.04 image with Anaconda 3.4.1.1 
  - (python 3.5, gphoto2-updater, astronomy.net, dcraw, exiftool)

* Using Inmage Hosted on Docker Hub
  - Install docker, for windows and macs install [Docker Toolbox](https://www.docker.com/products/docker-toolbox) and follow instructions 
  - Run the commands:
    - `docker pull  megwill4268/pocs:v1.01`
    - `docker run -t -i  megwill4268/pocs:v1.01 /bin/bash`

* To Build Image
   - Install docker, for windows and macs install [Docker Toolbox](https://www.docker.com/products/docker-toolbox) and follow instructions 
   - clone this repository
   - Run the commands: 
     - `docker build`
     - `docker run -t -i  megwill4268/pocs:v1.01 /bin/bash`