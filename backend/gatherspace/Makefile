build:
	docker build -t gs_backend .
up:
	docker-compose up
reset:
	docker-compose down
	docker-compose up
init:
	docker exec -it gs_backend pipenv run python3 manage.py migrate