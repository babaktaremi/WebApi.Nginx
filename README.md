# Running the project

 navigate to the docker-compose directory and run the following command:

 ```
docker-compose up -d
```

Web API URL is accessable via the following address ```http:localhost:4000```

If you want to horizontally scale the web api , run the following command:

```
docker-compose up --scale webapi.nginx=5 -d
```

By running the following command , you have 5 instances of web api running behinde Nginx reverse proxy. you can refer to the ```ServiceId``` for determining each instance
