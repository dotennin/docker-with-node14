setup:
	docker volume create nodemodules
install:
	docker-compose -f docker-compose.builder.yml run --rm install
build:
	docker-compose -f docker-compose.builder.yml run --rm build 
dev:
	docker-compose up
