# Docker images SMPPsim

### Usage
You can simply run the server as follows
```bash
docker run -d -p 8088:88 -p 2775:2775 -p 2776:2776 balsagoth/smppsim
```

Or 

Run and build the image from the dockerfile

```bash
docker build -t smppsim .
docker run -d -p 8088:88 -p 2775:2775 -p 2776:2776 smppsim
```


### Author

Ivan Pereira <ivan@zivan.org>

