  # Observability - for Django Notes-app
  
  # 1. Notes-app - based on Django runnning on 8000 port
  # 2. prometheus - taken metrics data , query and alerting server run on 9090 port
  # 3. cadvisor - used to taken metrics data from multiple Docker Container running on local system and provide data to prometheus , shows metrics on 8080 port
  # 4. node-exporter - used to taken metrics data from local system and provide data to prometheus , shows metrics on 9100 port
  # 5. grafana - used to visualize data received from prometheus , shows metrics visualization on 3000 port 
