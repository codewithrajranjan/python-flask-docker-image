## Git clone the application

## Create a virtual environment inside the application 

```python

    virtualenv -p /usr/bin/python3 venv    

    source venv/bin/activate

```

## Install Python modules

```python

   pip3 install -r requirements.txt 
    
```


## Run the application using

```python

    python app.py

```


## You will get below REST API

```python

        http://localhost:5000

```

## Docker commands

```bash
    
        // List all running container
        docker ps

        // list all containers
        docker ps -a


        // list all docker images
        docker images

        // build a docker image
        docker build -t <imageName:version> dockerFilePath

        
        // run a docker container in daemon mode with ports exposed
        docker run -it -d -p <outsidePort>:<dockerInsidePort> <imageName:version>




```
