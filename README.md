docker build -t sitenov-image .
docker run -d -p 8080:80 --name sitenov-app sitenov-image
