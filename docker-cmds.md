## Docker Commands Interacting with Image, Container, Volume, Network

1. Image
   
   ```bash
   => docker image --help
   
   Usage:  docker image COMMAND
   
   Manage images
   
   Commands:
     build       Build an image from a Dockerfile
     history     Show the history of an image
     import      Import the contents from a tarball to create a filesystem image
     inspect     Display detailed information on one or more images
     load        Load an image from a tar archive or STDIN
     ls          List images
     prune       Remove unused images
     pull        Download an image from a registry
     push        Upload an image to a registry
     rm          Remove one or more images
     save        Save one or more images to a tar archive (streamed to STDOUT by default)
     tag         Create a tag TARGET_IMAGE that refers to SOURCE_IMAGE
   
   Run 'docker image COMMAND --help' for more information on a command.
   ```

2. Container
   
   ```bash
   
   => docker container --help
   
   Usage:  docker container COMMAND
   
   Manage containers
   
   Commands:
     attach      Attach local standard input, output, and error streams to a running container
     commit      Create a new image from a container's changes
     cp          Copy files/folders between a container and the local filesystem
     create      Create a new container
     diff        Inspect changes to files or directories on a container's filesystem
     exec        Execute a command in a running container
     export      Export a container's filesystem as a tar archive
     inspect     Display detailed information on one or more containers
     kill        Kill one or more running containers
     logs        Fetch the logs of a container
     ls          List containers
     pause       Pause all processes within one or more containers
     port        List port mappings or a specific mapping for the container
     prune       Remove all stopped containers
     rename      Rename a container
     restart     Restart one or more containers
     rm          Remove one or more containers
     run         Create and run a new container from an image
     start       Start one or more stopped containers
     stats       Display a live stream of container(s) resource usage statistics
     stop        Stop one or more running containers
     top         Display the running processes of a container
     unpause     Unpause all processes within one or more containers
     update      Update configuration of one or more containers
     wait        Block until one or more containers stop, then print their exit codes
   
   Run 'docker container COMMAND --help' for more information on a command.
   ```

3. Volume
   
   ```bash
   => docker volume
   
   Usage:  docker volume COMMAND
   
   Manage volumes
   
   Commands:
     create      Create a volume
     inspect     Display detailed information on one or more volumes
     ls          List volumes
     prune       Remove all unused local volumes
     rm          Remove one or more volumes
   
   Run 'docker volume COMMAND --help' for more information on a command.
   ```

4. Network
   
   ```bash
   => docker network
   
   Usage:  docker network COMMAND
   
   Manage networks
   
   Commands:
     connect     Connect a container to a network
     create      Create a network
     disconnect  Disconnect a container from a network
     inspect     Display detailed information on one or more networks
     ls          List networks
     prune       Remove all unused networks
     rm          Remove one or more networks
   
   Run 'docker network COMMAND --help' for more information on a command.
   ```
   
   
