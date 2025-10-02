# GET aHEAD

### On the website, there are two buttons. One sends a HTTP POST request and one sends a HTTP GET request to the server based one which button you press. The biggest hint on this flag was most likely the name, as the key to finding the flag is basically changing the HTTP request from a GET to HEAD. A HTTP HEAD request is one that basically requests metadata about a resource. After making a HEAD request to index.php the server responds with 

HTTP/1.1 200 OK
flag: picoCTF{r3j3ct_th3_du4l1ty_6ef27873}
Content-type: text/html; charset=UTF-8

### Thus, the HEAD response responded with the flag!
