# Responsive-Error-Pages
Responsive web error code pages templates for WB.

This project is licensed under [GNU AGPLv3](https://choosealicense.com/licenses/agpl-3.0/#).

<https://assets.williambargent.co.uk/errors/v1/html/404.html>

## Usage
Using a .htaccess file, define the path to the error pages:

```
ErrorDocument 401 /var/www/html/.error-documents/400.html
ErrorDocument 401 /var/www/html/.error-documents/401.html
ErrorDocument 403 /var/www/html/.error-documents/403.html
ErrorDocument 404 /var/www/html/.error-documents/404.html
ErrorDocument 500 /var/www/html/.error-documents/500.html
```

If you have an asset server, deploy the iframe HTML files to each web server node so you can manage the main error page content centrally.

## Screenshots
### Desktop
![alt text](https://github.com/WilliamBargentLTD/Responsive-Error-Pages/blob/master/desktop.png "Desktop Screenshot")
### Tablet
![alt text](https://github.com/WilliamBargentLTD/Responsive-Error-Pages/blob/master/tablet.png "Tablet Screenshot")
### Mobile
![alt text](https://github.com/WilliamBargentLTD/Responsive-Error-Pages/blob/master/mobile.png "Mobile Screenshot")
