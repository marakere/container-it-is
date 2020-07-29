docker image build -t container-it-is .

docker container run -d --name hello-container -p 8080:8080 container-it-is