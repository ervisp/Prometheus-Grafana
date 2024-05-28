![image](https://github.com/ervisp/Prometheus-Grafana/assets/105393897/b19fb55f-310f-462a-a6bb-6cb8ad9f2ed5)



#### Prometheus-Grafana #####

Setting up Prometheus and Grafana with docker-compose

# Step 1 
Clone the repository: https://github.com/ervisp/Prometheus-Grafana
Navigate to the prometheus-grafana folder.

# Step 2

Run the following command to start the containers in the background: 

docker-compose up -d

Once the containers are up and running, you can access Prometheus and Grafana locally.

#  Step 3 
Prometheus is accessible at http://localhost:9090.
Grafana is accessible at http://localhost:3000.

# Addition info
# Configuring Prometheus
There is a prometheus.yml file provided in the repository. This file contains the configuration for Prometheus.
You can modify the prometheus.yml file to add the local applications that you want Prometheus to scrape and monitor.

# Once they are up, I can monitor Docker containers by modifing again docker compose using the cadvisor service as a target for scraping.

###########
