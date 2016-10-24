docker-lemp API and Frotend
===========

# Usage

	NAME = Your name
	PATH = Path to files
	In folder needs to be 2 separate folder api and frontend laravel structure.

    docker run --net mynet123 -d \
     --name NAME --volume-driver=nfs \
      -v PATH:/var/www -p 3332:80 -p 3333:81 vecbralis/ypp

