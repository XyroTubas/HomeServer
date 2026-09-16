# 🏠 HomeServer

A personal home server project built to explore self-hosting, Linux system administration, storage management, networking, and home infrastructure through a real working environment.

The goal of this project is to build a private and maintainable platform for hosting personal services while learning how the different parts of a server environment work together.

## 🚀 Current Services

The server currently runs the following services:

* 🎬 **Jellyfin** — Personal media streaming
* 📸 **Immich** — Self-hosted photo and video management
* ☁️ **Nextcloud** — Personal cloud storage and file synchronization
* 🐳 **Portainer** — Docker container management

## 🧱 Project Structure

```text
HomeServer/
├── docker/
│   ├── immich/
│   ├── jellyfin/
│   ├── nextcloud/
│   └── portainer/
├── docs/
├── scripts/
├── .gitignore
└── README.md
```

## 🐳 Containers

Services are deployed using Docker Compose.

Sensitive configuration such as passwords, tokens and environment variables is kept outside the repository using `.env` files and is excluded through `.gitignore`.

## 💾 Storage

Persistent application data and personal media are stored separately from the Git repository.

The repository contains only configuration and documentation required to understand and reproduce the infrastructure without exposing personal data.

## 🔐 Privacy & Security

The server is designed primarily for personal use.

Public repositories never include:

* Passwords
* API tokens
* Private keys
* `.env` files
* Databases
* Backups
* Personal photos or documents
* Media libraries

## 📚 What I'm Learning

This project gives me practical experience with:

* Linux server administration
* Docker and Docker Compose
* Networking
* Storage and filesystem management
* Self-hosted applications
* Service troubleshooting
* Git and GitHub
* Infrastructure documentation

## 🛠️ Project Status

This is an ongoing project.

The infrastructure, documentation and services will continue to evolve as I improve the server and add new functionality.
