ComputeWise
Version 1.0.0

A comprehensive Python library for network and Wi-Fi security analysis. ComputeWise allows you to monitor your computer's performance, ensure safety, scan your files, and check system specifications. The library also includes features for creating backups and detailed network analysis.

Features
Network and Wi-Fi Security Analysis: Monitor network activity, connected devices, and network interfaces.
System Performance Monitoring: Analyze signal strength, bandwidth usage, and channel interference.
File and Media Scanning: Search for specific files, media files, and clone them as needed.
Port Scanning and Vulnerability Checks: Scan open ports and check for common network vulnerabilities.
System Usage and Process Tracking: Track recent processes, program usage, and log application activities.
Photo Metadata Extraction: Extract metadata from images, including GPS location and capture date.
Wi-Fi Security Checks: Check Wi-Fi encryption, WPA3 support, and save security protocol history.
Installation
Using pip from GitHub
To install ComputeWise directly from the GitHub repository, use:

bash
Kodu kopyala
pip install git+https://github.com/username/ComputeWise.git
Replace username with your GitHub username or the owner of the repository.

Requirements
The following Python packages are required and will be installed automatically:

plaintext
Kodu kopyala
altgraph==0.17.4
attrs==24.2.0
beautifulsoup4==4.12.3
blinker==1.8.2
certifi==2024.7.4
charset-normalizer==3.3.2
click==8.1.7
et-xmlfile==1.1.0
Flask==3.0.3
h11==0.14.0
idna==3.7
itsdangerous==2.2.0
Jinja2==3.1.4
keyboard==0.13.5
macholib==1.16.3
MarkupSafe==2.1.5
openpyxl==3.1.5
outcome==1.3.0.post0
packaging==24.1
pillow==10.4.0
psutil==6.0.0
pyinstaller==6.10.0
pyinstaller-hooks-contrib==2024.8
PySocks==1.7.1
python-dotenv==1.0.1
requests==2.32.3
scapy==2.5.0
selenium==4.23.1
setuptools==73.0.1
sniffio==1.3.1
sortedcontainers==2.4.0
soupsieve==2.5
trio==0.26.2
trio-websocket==0.11.1
typing_extensions==4.12.2
urllib3==2.2.2
webdriver-manager==4.0.2
websocket-client==1.8.0
Werkzeug==3.0.3
wsproto==1.2.0
Usage
Below are examples of how to use some of the core functionalities provided by the ComputeWise library.

Example: Searching for Files
python
Kodu kopyala
from ComputeWise import search_files

# Search for all .txt files in the specified directory
files = search_files("/path/to/directory", ".txt")
print(files)
Example: Monitoring Network Activity
python
Kodu kopyala
from ComputeWise import get_network_activity

# Get current network activity
network_info = get_network_activity()
print(network_info)
Example: Scanning Open Ports
python
Kodu kopyala
from ComputeWise import scan_ports

# Scan ports from 1 to 1024 on localhost
open_ports = scan_ports(1, 1024)
print(open_ports)
Example: Extracting Photo Metadata
python
Kodu kopyala
from ComputeWise import get_image_metadata

# Extract metadata from an image file
metadata = get_image_metadata("/path/to/image.jpg")
print(metadata)
Example: Checking Wi-Fi Security
python
Kodu kopyala
from ComputeWise import check_wifi_encryption

# Check the Wi-Fi encryption type
wifi_security = check_wifi_encryption()
print(wifi_security)
Contributing
Contributions are welcome! If you'd like to contribute to ComputeWise, please fork the repository and use a feature branch. Pull requests are warmly welcome.

License
ComputeWise is licensed under the MIT License. See the LICENSE file for more information.

Contact
For any questions or feedback, feel free to reach out to the author:

Hasan Kayan
Email: hasankayanformal@gmail.com
Website: https://www.hasankayan.com



 pip install git+https://github.com/hasan-kayan/ComputeWise.git