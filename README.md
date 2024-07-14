<div align="center"><h1>RabbitMQ</h1></div>

<div align="center">
<img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white"/>
</div>

<div align="center">
This project is a part of: <b><a href="">Voltigo</a></b>
</div>

## Description

It's just wrapper for `RabbitMQ`, contains some configuration used explicitly for <b>Voltigo</b>.

# Running the project

- go inside the `docker` directory,
- call `docker-compose up -d`,
- the project is now reachable:
    - locally under: `127.0.0.1:8007`
    - within other voltigo-related containers under: `host.docker.internal:8007` 