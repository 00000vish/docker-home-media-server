# Docker-Home-Media-Server

Home media server setup using Radarr, Sonarr, Prowlarr, QBittorrent, and Jellyfin.

## Gluetun VPN Setup

Edit the Gluetun enviroment variables according to the [Gluetun wiki](https://github.com/qdm12/gluetun-wiki/tree/main/setup/providers).

(*No VPN? checkout branch => `main-no-vpn`*)

# Run

`sudo docker compose up`

## Network

| Container | Port |
| ------ | ---- |
| Jellyfin | 8096 |
| docker-whats-my-ip | 3000 |
| QBittorrent | 8080 |
| Radarr | 7878 |
| Sonarr | 8989 |
| FlareSolverr | 8191 |
| Prowlarr | 9696 |

## Containers

- QBittorrent - [QBittorrent Website](https://www.qbittorrent.org/) | [QBittorrent Docker Image](https://hub.docker.com/r/linuxserver/qbittorrent)
- Radarr - [Radarr Website](https://radarr.video/) | [Radarr Docker Image](https://hub.docker.com/r/linuxserver/radarr)
- Sonarr - [Sonarr Website](https://sonarr.tv/) | [Sonarr Docker Image](https://hub.docker.com/r/linuxserver/sonarr)
- FlareSolverr - [FlareSolverr Website](https://github.com/flaresolverr/flaresolverr) | [FlareSolverr Docker Image](https://hub.docker.com/r/flaresolverr/flaresolverr)
- Jellyfin - [Jellyfin Website](https://jellyfin.org/) | [Jellyfin Docker Image](https://hub.docker.com/r/linuxserver/jellyfin)
- Prowlarr - [Prowlarr Website](https://prowlarr.com/) | [Prowlarr Docker Image](https://hub.docker.com/r/linuxserver/prowlarr)
- Gluetun - [Gluetun Website](https://github.com/qdm12/gluetun) | [Gluetun Docker Image](https://hub.docker.com/r/qmcgaw/gluetun)
- docker-whats-my-ip - [docker-whats-my-ip Github](https://github.com/00000vish/docker-whats-my-ip) | [docker-whats-my-ip Image](https://hub.docker.com/r/00000vish/docker-whats-my-ip)

## License

MIT
