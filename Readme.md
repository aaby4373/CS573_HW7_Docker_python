Readme
===



Clone the git repository
---

On your command line.
```
git clone git@github.com:aaby4373/CS573_HW7_Docker_python.git
```

Once done, follow the steps below in order.

Build the image
---

```
 sudo docker build -t docker/python2 .
```

Run the cloned file
---

```
sudo docker run -p 8888:8888 docker/python2
```

Alternatively
===

Pull the file from dockerhub
---

Please run the below command.
```
sudo docker pull abishai777/dockerhub:python2
```
sudo is optional

Run the cloned file
---

```
sudo docker run -p 8888:8888 abishai777/dockerhub:python2
```

Click the URL generated in a new tab and the notebook should open.


Accessing images
---
```
sudo docker images
```
It gives you the image id , creation time, repository, size and  tag

Accessing containers
---
```
sudo docker ps -a
```
It retrieves container id, image id, created, command, PORTS and name
