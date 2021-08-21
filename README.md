# Run Go in Docker

Run go in a small docker container: <br/>

```
cd GoDevEnvironment

docker build --target dev . -t go
docker run -it -v ${PWD}:/work go sh
go version

```
