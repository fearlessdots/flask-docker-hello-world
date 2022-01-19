# flask-docker-hello-world

## What it is?
A really simple 'Hello, World!' in Flask using Docker (with docker-compose file). I just made it to learn more how to use Docker =]

## How to run?

To pull the **`python3`** image and build the custom one, run:

```shell
docker build -t <image_name> --pull .
```

Alternatively, using **`docker-compose`**:

```shell
docker-compose build --pull
```

And to create a container running this image, run:

```shell
docker run -d -v <volume_name>:/usr/src/app -p 5000:5000 <image_name>
```

Alternatively, using **`docker-compose`**:

```shell
docker-compose up -d
```

## Additional information

More information can be found in the sources below:

- <https://github.com/markbenschop/flask-demo/blob/master/Dockerfile>
- <https://www.clickittech.com/devops/dockerize-flask-python-application/>
- <https://predictivehacks.com/how-to-use-docker-for-flask-api/>
