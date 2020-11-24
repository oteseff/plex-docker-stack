# plex-docker-stack
Plex server running in docker with Sonarr, Radarr and qBittorrent with VPN support 

Create a .env in the same folder as your docker-compose file with the following:

PUID=1000
PGID=1000
TZ=America/Los_Angeles
USERDIR=/path/to/home
MOUNTDIR=/path/to/dir
USERNAME=VPN_Username
PASSWORD=VPN_Password
SERVERIP=IP_of_host
