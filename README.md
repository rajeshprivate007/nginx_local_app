
# Nginx Local App

This repository is for deploy basic nginx webserver and run a default page using nginx.




## Set up Enginx

Install enginx

```bash
sudo apt-get update
sudo apt install nginx
systemctl status nginx
```

Now if you browse you local ip it will show the default page of Nginx. (127.0.0.1)

By default local IP runs with port 80. (127.0.0.1:80)



## Add your custom page

-> Nginx serves pages from the location: /var/www/html

-> Now create a html file and place it on location /var/www/html 

-> Then if you browse your local ip it will show your custom html page.

