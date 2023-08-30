# Router-Log-Analysis
Analysing Simluated Router Logs from fabricated scenarios of common Attacks possible on a household. Part of Digital Forensics and Investigation Activity. 

The intention behind this activity was to learn and analyse how different attacks can be inferred from just the logs of a router. I couldnt find real logs for this, and so we were instructed to create the data. I tried the best that I could. There are certainly many inaccuracies and even straight up mistakes in this analysis, but it is meant only to get the point across, which I believe it does. I apologise however for the probably inaccuracy that you may find in this data. Do not take it as is, as a credible source of information, it is only for educational purposes. This would have been authentic if we could find router logs and perform attacks on them, but we couldnt so, this here is the best that we could do. 

Given the fact that it was an analysis activity either way, the focus here has been on just demonstrating the attacks, and try to prettify the graphs created using python and matplotilb. 

# For a Detailed Report, check out [The Assignment Report](./Assignment_2.pdf)

# Analysis Conducted. 

## Normal Usage Data

### Interface Usage - Normal Usage

![Normal usage of Devices connected. ](router_log_analysis_graphs/normal_interface_usage.png)

## DOS Attack Data

### Devices Connected - Normal Usage

![Normal usage of Devices connected. ](router_log_analysis_graphs/normal_devices_usage.png)

### IP Addresses Connected - DOS Attack

![DOS Attack Simulation Data for IP Addresses](router_log_analysis_graphs/ddos_attack_ips.png)

### Hourly Usage - Normal Usage

![Normal usage of Devices connected. ](router_log_analysis_graphs/normal_hourly_usage.png)

### Hourly Usage - Normal Usage

!![Normal usage of Devices connected during DOS Attack ](router_log_analysis_graphs/ddos_hourly_usage.png")

### Protocols Used - Normal Usage

![Normal usage of Devices connected. ](router_log_analysis_graphs/normal_protocols.png)

### Protocol Usage - DOS Attack

![DOS Attack Simulation Data for Protocol Usage](router_log_analysis_graphs/ddos_protocols.png)

### Daily Usage - Normal Usage

![Normal usage of Devices connected. ](router_log_analysis_graphs/normal_requests_per_day.png)

### Daily Usage - DOS Attack

![DOS Attack Simulation Data for Requests per day](router_log_analysis_graphs/ddos_requests_per_day.png)

## Brute Force Attack Data

### Hourly Usage - Normal Usage

![Normal usage of Devices connected. ](router_log_analysis_graphs/normal_hourly_usage.png)

### Hourly Usage - Brute Force Attack

![Brute Force Attack Simulation Data for Hourly Usage](router_log_analysis_graphs/insta_hourly_usage.png)

### Daily Usage - Normal Usage

![Normal usage of Devices connected. ](router_log_analysis_graphs/normal_requests_per_day.png)

### Daily Usage - Brute Force Attack

![Brute Force Attack Simulation Data for Daily Usage](router_log_analysis_graphs/insta_requests_per_day.png)

### Websites Visited - Normal Usage

![Normal usage of Devices connected. ](router_log_analysis_graphs/normal_website_visits.png)

### Websites Visited - Brute Force Attack

![Brute Force Attack Simulation Data for Website Visits](router_log_analysis_graphs/insta_website_visits.png)

## Port Scanning Data

### Ports Used - Normal Usage

![Normal usage of Devices connected. ](router_log_analysis_graphs/normal_ports.png)

### Port Usage - Port Scanning Attack

![Port Scanning Attack Simulation Data for Ports Usage](router_log_analysis_graphs/port_scanning_ports.png)

### Daily Usage - Normal Usage

![Normal usage of Devices connected. ](router_log_analysis_graphs/normal_requests_per_day.png)

### Daily Usage - Port Scanning Attack

![Port Scanning Attack Simulation Data for Daily usage](router_log_analysis_graphs/port_scanning_daily_usage.png)


# Credits

[This amazing article on Towards Data Science by Bradley Stephen Shaw](https://towardsdatascience.com/make-your-charts-look-glorious-9ce3fa310b70)