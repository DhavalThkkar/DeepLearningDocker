# DeepLearningDocker
My custom Image for Quick setup of Deep Learning Libraries in Python on any machine.

## Some Handy commands

1. Building the image```sudo docker build -t anaconda -f Dockerfile.cpu .```

2. Removing all containers ```sudo docker rm $(sudo docker ps -a -f status=exited -q)```

3. Removing all images```sudo docker rmi $(sudo docker images -a -q)```


# NOTE

Only Anaconda and Jupyter Notebook works. No support for Tensorflow, CNTK and Keras yet.
