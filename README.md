# Host-Based Intrusion Detection System Using ELK Stack SIEM

## Executive Summary

This project demonstrates the implementation of a Host-Based Intrusion Detection System (HIDS) using the ELK Stack (Elasticsearch, Logstash, and Kibana), Filebeat, and Suricata. The solution provides centralized log collection, real-time security monitoring, and interactive visualization to help detect and investigate potential security threats on a host system.


## Objectives

- Design and implement a Host-Based Intrusion Detection System (HIDS).
- Collect and centralize system and security logs.
- Monitor security events in real time.
- Visualize logs using Kibana dashboards.
- Detect and analyze suspicious activities using Suricata.

## Tools Used

- Elasticsearch
- Logstash
- Kibana
- Filebeat
- Suricata
- Ubuntu Linux
- VirtualBox

## Project Structure

```
Host-Based-Intrusion-Detection-System/
│── README.md
│── Documentation/
│── Screenshots/
│── Filebeat/
│── Logstash/
│── Suricata/
└── Kibana/
```

## Methodology

1. Set up the ELK Stack environment.
2. Install and configure Filebeat for log collection.
3. Configure Logstash to process incoming logs.
4. Store processed logs in Elasticsearch.
5. Visualize security events using Kibana dashboards.
6. Deploy Suricata to monitor network and host activities.
7. Analyze generated alerts and investigate suspicious events.

## Key Findings

- Successfully centralized security logs from the host.
- Real-time monitoring improved visibility into system events.
- Kibana dashboards simplified log analysis and visualization.
- Suricata detected and generated alerts for suspicious activities.
- ELK Stack provided efficient log storage and search capabilities.

## Results

The implemented HIDS successfully collected, processed, and visualized security events. The integration of ELK Stack, Filebeat, and Suricata enabled effective monitoring and analysis of system activities, improving threat detection and incident investigation capabilities.

## Security Implications

- Enhanced visibility into host activities.
- Early detection of suspicious behavior.
- Improved incident response through centralized logging.
- Better understanding of security events using visual dashboards.
- Supports proactive monitoring and threat analysis.

## Conclusion

This project demonstrates how an open-source SIEM solution can be implemented using the ELK Stack and Suricata to build an effective Host-Based Intrusion Detection System. It highlights the importance of centralized logging, real-time monitoring, and visualization in modern cybersecurity operations.

## Author

**Fawaz Abdul Azeez**
