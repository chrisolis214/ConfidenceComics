# ConfidenceComics

Project for building a website using the go programming language.

## Installation Instructions

1. Create folder: /var/run/ConfidenceServer
  - Make sure permissions are set to 755
  - owned by root
2. Move the systemd service file to the correct directory and restart the systemctl daemon
  - Correct directory is: /etc/systemd/system/confidenceserver.service
  - ALso change permissions to 755 and owned by root
3. Then run `sudo systemctl daemon-reload`
4. Copy cofidenceserver to /usr/bin directory
  - Also owned by root with 755 permissions
5. MAGIC!!!
