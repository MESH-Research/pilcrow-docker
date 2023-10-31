<h1 align="center">
    <a href="https://pilcrow.meshresearch.dev">
    <img src=".images/logo-100x100.png"/>
    <br />
    Pilcrow
    </a>
</h1>

# Docker Deployment

This repository hosts the Docker Compose recipes for Pilcrow.

For detailed deployment information [review the documentation.](https://pilcrow.meshresearch.dev/install/)

## Quick Start

- Clone this repository:

```sh
git clone https://github.com/mesh-research/pilcrow [destination]
```

- Copy the sample environment file

```sh
cd [destination]
cp sample.env .env
```

- Edit the .env file

```sh
nane .env
```

- Start stack

```sh
docker compose up -d
```
