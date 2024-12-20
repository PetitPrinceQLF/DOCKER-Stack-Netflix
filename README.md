<h2 align="center">
  Netflix x Docker
</h2>

---

<div align="center">
  <img alt="Demo" src="./assets_readme/images/background.png" />
</div>

<br/>

<div align="center">

[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com) &nbsp;
[![forthebadge](https://forthebadge.com/images/badges/open-source.svg)](https://forthebadge.com) &nbsp;
[![forthebadge](https://forthebadge.com/images/badges/powered-by-netflix.svg)](https://forthebadge.com) &nbsp;
<img alt="Powered by Docker" src="./assets_readme/images/powered-by-docker.svg" />
</div>

---

## About RudyFlix

**Netflix x Docker** is a self-hosted media server solution that lets you create your own personal streaming platform, just like Netflix. By leveraging powerful tools like Plex, Radarr, Sonarr, and more, RudyFlix allows you to organize, download, and stream your favorite media seamlessly. All components are managed using Docker for ease of setup and maintenance. Customize it to suit your needs and enjoy your content anywhere, anytime.

---

## Installing Netflix x Docker

To set up **Netflix with Docker**, follow these steps:

### Step 1: Clone the Repository

Linux and macOS:

```bash
sudo git clone https://github.com/PetitPrinceQLF/DOCKER-Stack-Netflix.git
```

Windows:

```bash
git clone https://github.com/PetitPrinceQLF/DOCKER-Stack-Netflix.git
```

### Step 2: Customize Your Stack

1. Modify the Docker Compose file to change the network names based on your preferences.
2. Enter your VPN details in the `gluetun` service configuration:
   ```yaml
   - OPENVPN_USER=<your_vpn_username>
   - OPENVPN_PASSWORD=<your_vpn_password>
   ```

### Step 3: Start the Services

Run the following command in the project directory:

```bash
docker-compose up -d
```

---

## Credit

Special thanks to the developers of the Docker images used in this project:

- [LinuxServer.io](https://www.linuxserver.io/) for Plex, Radarr, Sonarr, Prowlarr, and Qbittorrent.
- [FlareSolverr](https://github.com/FlareSolverr/FlareSolverr) for CAPTCHA bypass.
- [Gluetun](https://github.com/qdm12/gluetun) for VPN tunneling.

## Contact

If you have any questions, feel free to reach out at [rudy@galaxynetwork.fr](mailto:rudy@galaxynetwork.fr).

---

### Show Your Support

Give a ⭐ if you like this project!
