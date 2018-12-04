# Quickstart
Clone repo: 

```git clone https://github.com/migueltanada/ingress-controller.git```

![clone_screenshot](https://raw.githubusercontent.com/migueltanada/ingress-controller/master/img/clone_screenshot.png)

Enter folder

```cd ingress-controller```

Run jenkins ang nginx 

```docker-compose up -d```

![compose_screenshot](https://raw.githubusercontent.com/migueltanada/ingress-controller/master/img/compose_screenshot.png)

Copy proxy pass config for jenkins 

```docker cp default.conf nginx:/etc/nginx/conf.d/```

Restart nginx

```docker restart nginx```

Access Nginx http://<ip>

![nginx_screenshot](https://raw.githubusercontent.com/migueltanada/ingress-controller/master/img/nginx_screenshot.png)

Access Jenkins http://<ip>/jenkins

![jenkins_screenshot](https://raw.githubusercontent.com/migueltanada/ingress-controller/master/img/jenkins_screensot.png)

