#!/bin/bash
yum -y install httpd
systemctl enable httpd
systemctl start httpd
echo '<html><h1>Hello From Priyesh!</h1></html>' > /var/www/html/index.html
