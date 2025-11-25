-----------------------------------------------------------------------------

To run the java application docker file, follow the following commands

cd example/java
docker build -t my-java-app .
docker run --rm my-java-app


-----------------------------------------------------------------------------

For the python application ::

cd example/python
docker build -t my-python-app .
docker run --rm -p 5000:5000 my-python-app
# Open http://localhost:5000


-----------------------------------------------------------------------------

For the nodejs application :: 

cd example/nodejs
docker build -t my-node-app .
docker run --rm -p 3000:3000 my-node-app
# Open http://localhost:3000


------------------------------------------------------------------------------
