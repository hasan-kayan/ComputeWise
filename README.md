# ComputeWise 1.0.0
A Comprehensive Solution for Network, Wi-Fi, and System Security

### ComputeWise is an all-in-one Python library designed to elevate your network and system security monitoring. Whether you're looking to monitor your computer’s performance, analyze network activity, or check system specifications, ComputeWise provides a powerful set of tools to safeguard your environment. With features ranging from file and media scanning to Wi-Fi security analysis, ComputeWise is your go-to solution for network professionals, developers, and security enthusiasts.

## Key Features
🛡️ Network and Wi-Fi Security Analysis
Monitor real-time network activity and connected devices.
Analyze network interfaces and their security protocols.
Check Wi-Fi encryption status, including WPA3 support and security protocol history.
🚀 System Performance Monitoring
Analyze signal strength, bandwidth usage, and channel interference.
View real-time system usage and recent processes to track performance bottlenecks.
🗂️ File and Media Scanning
Search for and clone files with specific extensions across directories.
Extract metadata from media files such as capture date, GPS location, and more.
🔍 Port Scanning and Vulnerability Checks
Scan for open ports and common network vulnerabilities to assess security risks.
🔄 Backup and Recovery
Create comprehensive system backups, helping you recover important data in case of failures.
🧑‍💻 System Usage and Process Tracking
Track recent processes and applications running on your machine.
Log and review program usage for future audits.


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Installation 
```
pip install git+https://github.com/hasan-kayan/ComputeWise.git

```

### Requirements
ComputeWise automatically handles all dependencies during installation. Some of the key packages include:

Flask, Psutil, Openpyxl, Scapy, Requests, Selenium, Pillow, PyInstaller, and more (full list in the project)




## Quick Start Guide

1. File Scanning
```
from ComputeWise import search_files

files = search_files("/path/to/directory", ".txt")
print(files)
```

2. Network Activity Monitoring
Monitor real-time network data and active devices:
 ```
from ComputeWise import get_network_activity

network_info = get_network_activity()
print(network_info)
```
3. Port Scanning
Scan for open ports in a specific range:

```
from ComputeWise import scan_ports

open_ports = scan_ports(1, 1024)
print(open_ports)
```
4. Metadata Extraction from Photos
Retrieve metadata from image files, such as location and capture date:
```
from ComputeWise import get_image_metadata

metadata = get_image_metadata("/path/to/image.jpg")
print(metadata)
```
5. Wi-Fi Security Check
Check your Wi-Fi’s encryption and security status:
```
from ComputeWise import check_wifi_encryption

wifi_security = check_wifi_encryption()
print(wifi_security)
```

## Contributing
We warmly welcome contributions to enhance the functionality of ComputeWise. To contribute:

Fork the repository.
Create a feature branch.
Submit a pull request, and we’ll review it promptly!
Whether it’s bug fixes, new features, or improved documentation, every contribution counts.



