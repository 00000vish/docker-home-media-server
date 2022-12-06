#  Docker-Home-Media-Server
Docker-Home-Media-Server docker compose file automates setting up home media server with Radarr, Sonarr, Jackett, QBittorrent, Jellyfin and Portainer. 

# Run
``
sudo docker compose up
``

## Containers 
Docker-Home-Media-Server creates following containers

- Portainer -  [Portainer-Website](https://www.portainer.io/)  | [Portainer Docker Image](https://hub.docker.com/r/portainer/portainer)
- QBittorrent - [QBittorrent Website](https://www.qbittorrent.org/) | [QBittorrent Docker Image](https://hub.docker.com/r/linuxserver/qbittorrent)
- Radarr - [Radarr Website](https://radarr.video/) | [Radarr Docker Image](https://hub.docker.com/r/linuxserver/radarr)
- Sonarr - [Sonarr Website](https://sonarr.tv/) | [Sonarr Docker Image](https://hub.docker.com/r/linuxserver/sonarr)
- Jackett - [Jackett Website](https://github.com/Jackett/Jackett) | [Jackett Docker Image](https://hub.docker.com/r/linuxserver/jackett)
- Jellyfin - [Jellyfin Website](https://jellyfin.org/) | [Jellyfin Docker Image](https://hub.docker.com/r/linuxserver/jellyfin)

## Network
Docker-Home-Media-Server network configuration
| Container | Address | Port |
| ------ | ------ | ---- |
| Portainer | [plugins/dropbox/README.md][PlDb] | 9443 | 
| QBittorrent | [plugins/github/README.md][PlGh] | 8080 | 
| Radarr | [plugins/googledrive/README.md][PlGd] | 7878 | 
| Sonarr | [plugins/onedrive/README.md][PlOd] | 8989 | 
| Jackett | [plugins/medium/README.md][PlMe] | 9117 | 
| Jellyfin | [plugins/googleanalytics/README.md][PlGa] | 8096 | 



## License

MIT