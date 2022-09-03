docker buildx build --platform linux/amd64,linux/arm64 -f Dockerfile --tag brainiac/multiarch-webhook:0.1.0 --push .


docker run brainiac/multiarch-webhook:0.1.0