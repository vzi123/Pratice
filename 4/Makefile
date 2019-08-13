init:
	npm install
	/usr/local/bin/docker-compose build

run:
	serverless sam export -o template.yml
	/usr/local/bin/docker-compose up