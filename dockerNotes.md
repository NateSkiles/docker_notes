## Docker Notes
#### Intro
Why user docker?
* Docker makes it really easy to install and run software without worrying about setup or dependencies
What is docker?
* Docker is a platform or ecosystem around creating and running containers

Parts of the Docker ecosystem:
* Client, Server, Machine, Images, Hub, Compose.

Image -
* Single file with all the deps and config required to run a program

Container - 
* Instance of an image.  Runs a program.

Docker Client (Docker CLI) -
* Tool that used to issue commands to =>

Docker Server (Docker Daemon)- 
* Tool that is responsible for creating images, running containers, etc

```docker run hello-world```
Reaches out to docker hub, grabs an image, **_creates_** a container out of that image.
The ```run``` command runs the commands:
* ```create``` - creates a container from an image
* ```start``` - starts the container

Image Cache - 
* Images storage locally of programs.
    * Once downloaded, you can call that program a lot quicker next time.

System calls -
* Running program issues request to kernel to interact with a piece of hardware

```docker ps [OPTIONS]``` -
* List containers


