Problem 3:

> GET /odetocode.jpg HTTP/1.1
> Host: odetocode.com
> User-Agent: curl/7.64.0
> Accept: */*
>
< HTTP/1.1 200 OK
< Content-Length: 11751
< Content-Type: image/jpeg
< Last-Modified: Mon, 10 Dec 2012 02:44:57 GMT
< Accept-Ranges: bytes
< ETag: "64c77b5780d6cd1:0"
< Server: Microsoft-IIS/10.0
< X-Powered-By: ASP.NET
< Date: Thu, 19 Sep 2019 12:21:44 GMT
<

Problem 4:
curl --output http-easy.html http://www.jmarshall.com/easy/http/ 

Problem 5:
curl --output duckduckgo.html https://duckduckgo.com/
curl -v -o duckduckgo.txt -o duckduckgo.html https://duckduckgo.com/ 

Problem 6:
curl -v -o science.txt https://duckduckgo.com/?q=science&t=h_&ia=about 
curl -v -o computer-science.txt https://duckduckgo.com/?q=computer+science&t=h_&ia=about

Problem 7:
curl -v -o gmit.json https://duckduckgo.com/?q=gmit&format=json
