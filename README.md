docker build -t python-lightweight-frontend .

docker run -d -p 5000:5000 --name python-frontend python-lightweight-frontend
