# Models in your dockerfiles!

Here's how to build the images in this repo:

```
docker build -t your-registry.fly.dev/models/smollm/135m:q4 smollm
docker build -t your-registry.fly.dev/models/hermes3/8b:q4_k_m hermes3
```

Push these to [your custom registry](https://github.com/tigrisdata-community/docker-registry) and serve your stuff in the cloud with ease!
