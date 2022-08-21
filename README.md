docker build --tag myrun .
docker run -p 8000:8000 --name products -e SECRET_KEY=?