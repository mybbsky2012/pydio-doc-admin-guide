For Pydio Cells to work you will be needing some specific packages and such.
As a matter of fact we will provide you the list of the required packages and such so that you can use Pydio Cells at it's fullest.

### Webserver

With Pydio Cells the webserver is provided within the binary, we are using [Caddy](https://caddyserver.com/docs) a web server written in go that is really easy to use and is configurable through a single file named 'Caddyfile'. It provides HTTPS by default using Let's encrypt certificates.

### Php

We recommend you to use PHP 7 as it's faster than PHP 5 that will soon be no longer supported by Pydio, for the moment if you cannot upgrade you can still use Pydio with PHP 5.5.9.

You also require the following packages :

* **php-fpm**
* **php-gd**
* **php-intl**
* **php-dom**
* **php-curl**

### Database

For the moment we are supporting :

* **MySQL** version 5.6 and above.
* **MariaDB** version 10 and above.

### Networking

Pydio needs both **80** & **443** ports to be available, you can run either one of them but we highly recommend that you use **443** to make sure that all communication between the server and the client are encrypted. With Pydio Cells the embarked webserver provides this feature.

### Hardware

For Pydio Cells to run smoothly you should meet the following requirements:

* **RAM** : 2gb minimum
* **CPU** : 2 cores minimum
* **HD**  : we recommend you to use an ssd as it has faster access time and huge writing/reading speeds.

### Cells Binary

You can get the cells binary from our public servers [here](https://download.pydio.com/pub/)
or you can use the links below :

* **[Home Edition](https://download.pydio.com/pub/cells/release/0.9.1/linux-amd64/cells)**
* **[Enterprise Edition](https://download.pydio.com/pub/cells-enterprise/release/0.9.1/linux-amd64/cells-enterprise)**