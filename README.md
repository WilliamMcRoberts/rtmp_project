RTMP SERVER using NGINX, EXPRESS, DOCKER COMPOSE, OBS

1. clone repo
2. install docker / compose
3. command: docker compose build then docker compose up
4. start stream in OBS with url: "rtmp://localhost:1935/live" and stream key:  "test?key=supersecret"
5. navigate to http://localhost:8080/ in your browser
6. watch your stream
