# Home Server

### Requirements 
- install [docker](https://docs.docker.com/engine/install/)

### Cloning Project
```
git clone https://github.com/migueloliveiradev/home-server.git
```

### Setup Environment Settings 

- Settings shared
```
cp .env.shared.example .env.shared
```
```
nano .env.shared
```

- Navidrome
```
cp navidrome/.env.example navidrome/.env
```
```
nano navidrome/.env
```
- Tailscale
```
cp tailscale/.env.example tailscale/.env
```
```
nano tailscale/.env
```

### Starting projects
```
sudo docker compose up -d 
```
