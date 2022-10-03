# Helm - example NGINX chart

Created based on the template 'Custom Helm starter chart' with the command:


  `$ helm create nginx-chart --starter <TEMPLATE_DIR_PATH> && sed -i '0,/^\([[:space:]]*appVersion: *\).*/s//\11.23.1/;' <CHART_PATH>/nginx-chart/Chart.yaml'`

