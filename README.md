# Baby tools shop

This project provides a minimal, fully containerized application setup using Docker. All necessary dependencies, migrations, and startup steps are handled during the image build, making the application ready to run immediately through an exposed port.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Quickstart](#Quickstart)
- [Usage](#Usage)

### Prerequisites

- Python 3.9
- Django 4.0.2
- Virtual Machine
- Docker engine

### Quickstart

- Clone the repository: 

```bash
ggit clone <REPOSITORY_URL>
cd <REPOSITORY_NAME>
```
- Build Docker image

```bash
docker build -t <Image-Name> .
```

- Start Docker Container

```bash
docker run -dt -p 8080:8080 <Image-Name>
```

### Usage


