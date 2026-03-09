

# 🧪 GeekLab Workshop (Tecweb 2026)

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Portainer](https://img.shields.io/badge/Portainer-13BEF9?style=for-the-badge&logo=portainer&logoColor=white)


## 🎯 Setup Portainer

### Install de Community Edition

- On your system command line run:

```bash
docker volume create portainer-data
```

```bash
docker run -d -p 8000:8000 -p 9443:9443 --name portainer --restart=always -v /var/run/docker.sock:/var/run/docker.sock -v portainer-data:/data portainer/portainer-ce:latest
```

- Access web page on: https://localhost:9443  (later we will open it on: https://lab.tecweb26.com:9443 )

- Create an admin `username` and `password`