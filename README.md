# Docker-Home-Media-Server

Docker-Home-Media-Server docker compose file automates setting up home media server with Radarr, Sonarr, Jackett, QBittorrent, and Jellyfin.

# Run

`sudo docker compose up`

## Containers

Docker-Home-Media-Server creates following containers

- QBittorrent - [QBittorrent Website](https://www.qbittorrent.org/) | [QBittorrent Docker Image ](https://hub.docker.com/r/linuxserver/qbittorrent)
- Radarr - [Radarr Website](https://radarr.video/) | [Radarr Docker Image ](https://hub.docker.com/r/linuxserver/radarr)
- Sonarr - [Sonarr Website](https://sonarr.tv/) | [Sonarr Docker Image ](https://hub.docker.com/r/linuxserver/sonarr)
- Jackett - [Jackett Website](https://github.com/Jackett/Jackett) | [Jackett Docker Image ](https://hub.docker.com/r/linuxserver/jackett)
- Jellyfin - [Jellyfin Website](https://jellyfin.org/) | [Jellyfin Docker Image ](https://hub.docker.com/r/linuxserver/jellyfin)
- docker-whats-my-ip - [docker-whats-my-ip Github ](https://github.com/00000vish/docker-whats-my-ip)

## Network

Docker-Home-Media-Server network configuration
| Container | Docker Address | Port |
| ------ | ------ | ---- |
| QBittorrent | 192.168.101.104 | 8080 |
| Radarr | 192.168.101.103 | 7878 |
| Sonarr | 192.168.101.102 | 8989 |
| Jackett | 192.168.101.106 | 9117 |
| Jellyfin | 192.168.101.105 | 8096 |
| docker-whats-my-ip | 192.168.101.105 | 3000 |

## License

MIT
