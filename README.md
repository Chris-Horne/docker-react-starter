# Docker + React Starter

A lightweight development setup for running a React app inside a Docker container with live reload and simple configuration.

## 🛠 What's Included

- React app created with `create-react-app`
- Dockerfile for building the container
- `docker-compose.yml` for hot reload, volume mapping, and easy start
- Compatible with Windows, macOS, Linux

## 🚀 Quick Start

Make sure you have [Docker Desktop](https://www.docker.com/products/docker-desktop) installed.

```bash
git clone https://github.com/chris-horne/docker-react-starter.git
cd docker-react-starter
docker-compose up --build
