## appwrite for me
This appwrite has been initialized with the following command.

```sh
docker run -it --rm \\n    --volume /var/run/docker.sock:/var/run/docker.sock \\n    --volume "$(pwd)"/appwrite:/usr/src/code/appwrite:rw \\n    --entrypoint="install" \\n    appwrite/appwrite:0.11.0
```
