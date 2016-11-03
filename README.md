Speedtest Mini
--------------

Build your own speedtest server with docker.


```
sudo docker build --tag rmika/speedtest-mini .
sudo docker run -p 80:80 --restart always -d --name speedtest -t rmika/speedtest-mini
```

Then goto http://localhost/ from your browser.



