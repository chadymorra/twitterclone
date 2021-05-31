# Twitterclone
## Twitter-Clone DApp on Ropsten 

### Authors:
* Chady Morra
* Boris Bambo
* Abdelhafid Al Bekkaoui

### Documentation:

How to use twitterclone:
* To pull the docker image use the following command
```
docker pull chadmorra/twitterclone:latest
```
* To run the container and map the webserver port 8000 to port 8000 on your host use the below commands:
```
docker run -it -p 8000:8000 chadmorra/twitterclone:latest python3 -m http.server &
```
Access http://127.0.0.1:8000 in your Browser and connect your metamask

For unit tests:
```
docker run -it <image-id> ganache-cli -h 0.0.0.0 &
```
```
docker exec -it <image-id> truffle test
```

Happy Tweeting, 

Freedom of speech
