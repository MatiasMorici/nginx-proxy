**Nginx-proxy demo using 2 laravel proyects with their respective mysql databases.**

**Steps:**

*1st:*
> CD nginx-proxy/

> docker-compose up -d

this will run the nginx-proxy daemon


*2nd:*
> CD laravel-app/

> docker-compose up -d

*3rd:*
> CD laravel-app2/

> docker-compose up -d


*4th:*
Add to your hosts file:
>   127.0.0.1  ap1.local

>   127.0.0.1  ap2.local
  
*Now you can test both pages in your browser:*
>   http://ap1.local/

>   http://ap2.local/
  
  
If you access to localhost you'll see 503 error.
