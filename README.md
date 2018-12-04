# Quickstart
Clone repo: 
```git clone https://github.com/migueltanada/ingress-controller.git```
![clone_screenshot]()

Run jenkins ang nginx 
```docker-compose up -d```
![compose_screenshot]()

Copy proxy pass config for jenkins 
```docker cp default.conf nginx:/etc/nginx/conf.d/```
![cp_screenshot]()

Restart nginx ```docker restart nginx```
![restart_screenshot]()

Access Nginx http://<ip>
![nginx_screenshot]()

Access Jenkins http://<ip>/jenkins
![jenkins_screenshot]()

