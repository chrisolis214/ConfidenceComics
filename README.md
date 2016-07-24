# ConfidenceComics

Project for building a website using the go programming language.

## Installation Instructions

1. Create folder: /var/run/ConfidenceServer
  - Make sure permissions are set to 755 and owned by root

2. Move the file confidenceserver.service
  - Correct directory is: /etc/systemd/system/
  - Also change permissions to 755 and owned by root

3. Then run `sudo systemctl daemon-reload`

4. Copy confidenceserver script to /usr/bin directory
  - Also change permission to 755 and being owned by root

5. MAGIC!!!
