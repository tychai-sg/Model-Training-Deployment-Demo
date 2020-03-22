# Deployment of the Model

Build the Docker image:

    cd docker
    docker build -t tychai/dogs-vs-cats .


Run the Docker image:

    docker run -p 7001:7001 tychai/dogs-vs-cats


Access the app at http://localhost:7001/ from a browser.
