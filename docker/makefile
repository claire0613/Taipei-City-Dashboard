.PHONY: up db init app

up: db init app

db:
	docker-compose -f docker-compose-db.yaml up -d

init:
	docker-compose -f docker-compose-init.yaml up -d

app:
	docker-compose up -d


clean_db:
	docker compose -f docker-compose-db.yaml down -v



