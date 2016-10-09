# scarfage Docker Container #

## Building the Container ##
```
docker build -t rayterrill/scarfage:0.1 -t rayterrill/scarfage:latest .
```

## Uploading the Container ##
```
docker push rayterrill/scarfage
```

## Pulling the Container from Docker Hub ##
```
docker pull rayterrill/scarfage
```

## Running the Container in Interactive Mode (and Delete After Exit) ##
```
docker run -it --rm rayterrill/scarfage
```
