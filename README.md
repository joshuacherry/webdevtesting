## Testing Ground for webdev stuff
[URL](https://joshuacherry.github.io/webdevtesting/)

#### Getting sha512 of a file with curl
```
curl -s https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js | openssl dgst -sha512 -binary | openssl base64 -A

3P8rXCuGJdNZOnUx/03c1jOTnMn3rP63nBip5gOP2qmUh5YAdVAvFZ1E+QLZZbC1rtMrQb+mah3AfYW11RUrWA==

```
Add the output to your script.
```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js" integrity="sha512-3P8rXCuGJdNZOnUx/03c1jOTnMn3rP63nBip5gOP2qmUh5YAdVAvFZ1E+QLZZbC1rtMrQb+mah3AfYW11RUrWA==" crossorigin="anonymous"></script>
```
