haproxy
==================

Base docker image to run a HAProxy with etcd


Usage
-----

To create the image `domabo/haproxy`, execute the following command on the haproxy folder:

	sudo docker.io build -t domabo/haproxy .

Load the HAProxy image
------------------------

	ID=$(sudo docker.io run -d -p 80 domabo/haproxy /run.sh)
