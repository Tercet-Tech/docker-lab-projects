# Docker Lab Projects

A collection of Docker projects and Compose stacks used in the Tercet Tech lab.

This repository contains the `docker-compose.yml` files and supporting configurations powering various services in the Tercet Tech lab environment.

> ⚠️ `.env` files are included as templates but must be updated with your own values (e.g., passwords, API keys, IPs) before deploying.

---

## 🦎 Built for Komodo, Flexible for Any Stack Manager

These stacks are designed to integrate directly with [Komodo](https://komo.do/), a powerful container management tool for self-hosted environments.  
Each stack follows a modular directory structure that Komodo can import and manage with ease.

However, they are also **fully compatible with standalone Docker Compose**, and can be adapted for use with other platforms like **Portainer** or **Dockge**.

---

## 📁 Layout

Each stack is organized with the following structure:

```

/stack-name
├── docker-compose.yml
├── .env
└── volumes/        # excluded from repo

```

This makes it easy to drop into Komodo, or clone and run directly using Docker Compose.

---

## 🛠 Contributions & Issues

These stacks are customized for the Tercet Tech lab setup, but being open-source, we welcome **contributions**, **suggestions for improvements**, and **forks**.

Feel free to:
- Submit a pull request with enhancements or fixes
- Open an issue if you encounter problems or have feature ideas
- Fork the repo and adapt it to your own lab setup


---

### 📄 [MIT License](https://github.com/Tercet-Tech/docker-lab-projects/blob/main/LICENSE)


