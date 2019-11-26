this post is for running Wordpress kubernetes on local Docker for desktop.

To start using wordpress localy for testing. 

make a sure Docker for desktop is running and have enabled kubernetes.


1)clone this repo

2)run below command


kubectl create -k ./


This will start wordpress localy and you can access using http://localhost:30004


In next post I will write you you can use managed kubernetes (AKS,EKS, GEK) for running wordpress.


