# Dockerfile Collection

### networkstatic/star_wars

Test your Docker install, demo docker or pop some popcorn and watch an ASCII remaster of Star Wars :p

* Start the movie with the following:

```
docker run -it --rm networkstatic/star_wars
```

Use ctrl^c to break the movie session.

### networkstatic/nmap

Nmap is a perenial favorite for security fuzzing.

A couple of example usages:

* Run the `nmap --help` to view port scanning options.

```
docker run -it --rm networkstatic/nmap --help
```

* Scan for open ssh (tcp/22) ports on a range of IPs

```
docker run -it --rm networkstatic/nmap -sT 192.168.1.1-100 -p 22
```

### networkstatic/nginx_kittah

This is an example of a simple change to the static Nginx index.html page. Replace the default index.html with some funs ascii art.

* Run and listen on port 8080 with the following:

```
docker run -it --rm  -p 8080:80 networkstatic/nginx_kittah
```
