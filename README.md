# Graduation Project - Full System

## Guideline

- Node version: `22.15.0`
- Docker version: `28.0.4`
- Docker Compose version: `v2.34.0`

This repository contains three submodules:

- `client` - ReactJS frontend for main user interface (port 3000)

```sh
 https://github.com/PhanThanhDat16/graduation-client.git
```

- `admin` - ReactJS frontend for admin dashboard (port 3001)

```sh
 https://github.com/PhanThanhDat16/graduation-admin.git
```

- `api` - NodeJS backend API (port 5000)

```sh
 https://github.com/PhanThanhDat16/graduation-api.git
```

---

## Installation

1. Clone the repository with submodules:

```sh
git clone --recurse-submodules https://github.com/PhanThanhDat16/my-project.git
```

- If you forgot --recurse-submodules, run after clone:

```sh
 git submodule update --init --recursive
```

2. Build Docker images:

```sh
docker-compose build
```

## Running the application

1. Start all services in development mode:

```sh
docker-compose up
```

2. Access the applications:

- Client: http://localhost:3000

- Admin: http://localhost:3001

- API: http://localhost:5000