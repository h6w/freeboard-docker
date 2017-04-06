# Freeboard in a container on Alpine Linux with nginx, so it's teeeeny!

[![Microbadger](https://images.microbadger.com/badges/image/tudorh/freeboard.svg)](http://microbadger.com/images/tudorh/freeboard "Image size")
[![Docker Stars](https://img.shields.io/docker/stars/tudorh/freeboard.svg?maxAge=86400)](https://hub.docker.com/r/tudorh/freeboard/) 
[![Docker Pulls](https://img.shields.io/docker/pulls/tudorh/freeboard.svg?maxAge=86400)](https://hub.docker.com/r/tudorh/freeboard/)
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=UY3DF5LBT46BE)


# How to use this image

```
docker run --name myfreeboard -p 8080:80 -d tudorh/freeboard
```

This will expose an installation of Freeboard at http://localhost:8080

