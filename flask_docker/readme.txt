
Build the image
Now that we have a Dockerfile, let’s verify it builds correctly:

docker build -t flask-tutorial:latest .    -t : tag
After the build completes, we can run the container:

docker run -d -p 5000:5000 flask-tutorial. .  -d detach mode , port : host port--containerport
