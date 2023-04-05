# hello-docker

Command to run hellow-docker application:

First navigate to application directory in CMD.

Build docker image:

  ``` docker build -t hello-docker . ```

Note: "-t" indicate the Tag. "hello-docker" indicate image name. "." indicate the current direcoty of application.

Get List of images:

  ``` docker image ls ```

Run docker image:

  ``` docker run hello-docker ```

Note: hello-docker is a image name.
