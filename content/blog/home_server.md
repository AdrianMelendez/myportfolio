---
title: "My Home Server Setup"
date: 2026-02-19T14:00:00+01:00
draft: false
tags: ["Home Server", "Docker", "Self-Hosted"]
categories: ["Personal Projects"]
socialLinks:
    github: https://github.com/AdrianMelendez
    linkedin: https://linkedin.com/adrian-melendez-lorenzo/---
title: "My Home Server Setup"
date: 2026-02-19T14:00:00+01:00
draft: false
tags: ["Home Server", "Docker", "Self-Hosted"]
categories: ["Personal Projects"]
share: false
---

# My Home Server Setup

Over the past few years, I’ve been building a personal home server to centralize my digital life and experiment with self-hosted services. The goal is to have a secure, manageable, and mostly automated infrastructure that I can access both locally and remotely. Here’s a summary of what I’m running today:

## Photo Gallery

- **Immich** – My main photo storage and gallery solution. It’s fast, modern, and keeps all my images organized without relying on third-party cloud providers.

## Media Library

- **Jellyfin** – I use Jellyfin as an alternative to Plex for streaming movies and TV series. It’s completely self-hosted and supports multiple devices.

## Remote Access

- **WireGuard** – A lightweight and secure VPN that allows me to access my home network when I’m outside. This makes all services accessible securely from anywhere.

## Password Management

- **Vaultwarden** – My self-hosted password manager. It keeps all credentials safe and centralized, with easy multi-device access.

## Reverse Proxy / Public Access

- **Pangolin** – Handles routing and making specific services publicly accessible. While slightly complex to configure, it has excellent documentation.  
- Alternative options: Traefik or Nginx.

## Document Management

- **Paperless** – For scanning, indexing, and storing important documents.  
- Alternative growing project: Papra.


## Dashboard / Homepage

- **Glance** – A personalized homepage showing system status, links, and quick access to services.

## Container Management

- **Portainer** – To manage all Docker containers and stacks easily, with a clean web interface.

---

Setting up this stack has been a rewarding experience in self-hosted infrastructure, networking, and automation. It allows me to experiment safely with new services, maintain control over my data, and create a personal cloud environment without relying on external providers.

In future posts, I plan to dive deeper into individual services, how I configure them, and tips for running a secure and reliable home server.

