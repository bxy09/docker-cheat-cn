.PHONY: build push clean
IMAGE = alpine/lua
TAG = latest

build:
	docker build -t r.gpxtrade.com/$(IMAGE):$(TAG) .
push:
	docker push r.gpxtrade.com/$(IMAGE):$(TAG)
