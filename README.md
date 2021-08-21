# Run Go in Docker

We can also run go in a small docker container: <br/>

```
cd GoDevEnvironment

docker build --target dev . -t go
docker run -it -v ${PWD}:/work go sh
go version

```
