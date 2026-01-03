## Project : Infrastructure Health Monitoring System

### Description
Comprehensive infrastructure monitoring tool that tracks CPU, memory, disk, network metrics across multiple servers and generates health reports with predictive analytics.

### Features
- Multi-server monitoring
- Real-time resource utilization
- Predictive failure detection
- Automated alerting system
- Health score calculation
- Custom threshold configuration

### Tech Stack
- Python 3.8+
- psutil for system metrics
- matplotlib for charts
- threading for concurrent monitoring

### Installation
```bash
pip install psutil matplotlib pandas numpy
python infra_monitor.py
```

### Usage
```python
# Monitor multiple servers
monitor = InfraMonitor()
monitor.add_server("web-server-01", "192.168.1.10")
monitor.generate_health_report()
```

### Output
- Real-time resource utilization graphs
- Health score dashboard
- Anomaly detection charts
- Predictive failure warnings

---
