# python-dev-container-demo

# ...existing code...

## Running with Docker

Build the Docker image:
```
$ docker build -t python-dev-container-demo .
```

Run the Docker container:
```
$ docker run -p 5000:5000 python-dev-container-demo
```

## Running the Flask app locally

```
$ flask --app hello run
 * Serving Flask app 'hello'
 * Running on http://127.0.0.1:5000 (Press CTRL+C to quit)
```

## Running in VS Code Dev Container

1. Open the project in VS Code.
2. Press `F1` and select `Remote-Containers: Open Folder in Container...`.
3. Select the project folder.
4. The container will build and start, and the Flask app will be available on port 5000.
