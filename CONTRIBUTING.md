<!-- Contributing -->

<!-- How to run Docker File Locally --
#In terminal:
#docker build -t flask-smorest-api .  # Build the docker image using this directory's Dockerfile ("flask-smorest-api" is the name of the image yo want to give)
#then..
#docker run -dp 5000:5000 -w /app -v "$(pwd):/app" <IMAGE NAME> sh -c "flask run --host 0.0.0.0"