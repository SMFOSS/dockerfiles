DOCKER = docker
IMAGE_TAG = python
DOCKERFILE_LOCATION = .

.PHONY: docker-image

docker-image:
	$(DOCKER) build -t $(IMAGE_TAG) $(DOCKERFILE_LOCATION)
