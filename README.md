<img alt="SocialAPI - Social Media app" src="/assets/fastapi-social-media.png">
    <h1 align="center">SocialAPI</h1>

<p align="center">
    FastAPI backend for a social media app
</p>

<p align="center">
  <a href="https://twitter.com/anchit1909" target="_blank">
    <img src="https://img.shields.io/twitter/follow/anchit1909?style=flat&label=anchit1909&logo=twitter&color=0bf&logoColor=fff" alt="Anchit Sinha Twitter follower count" />
  </a>
  <a href="https://github.com/Anchit1909/blockbnb-decentralized-house-rental-platform" target="_blank">
    <img src="https://img.shields.io/github/stars/Anchit1909/social-media-fastapi?label=Anchit1909%2FSocialAPI" alt="SocialAPI repo star count" />
  </a>
</p>

<p align="center">
  <a href="#introduction"><strong>Introduction</strong></a> ·
  <a href="#tech-stack"><strong>Tech Stack</strong></a> ·
  <a href="#running-locally"><strong>Running Locally</strong></a> ·
  <a href="#author"><strong>Author</strong></a>
</p>
<br/>

## Introduction

SocialAPI is a backend for a social media app built using FastAPI. It has 4 main routes:

1. Post Route: Create, delete, update, and view posts.
2. Users Route: Create users and search users by ID.
3. Auth Route: User registration and login system.
4. Vote Route: Upvote system.

The application is deployed on a virtual machine using an Nginx server.

## Tech Stack

- [Python](https://www.python.org/)
- [FastAPI](https://fastapi.tiangolo.com/)
- [SQLAlchemy](https://www.sqlalchemy.org/)
- [Alembic](https://pypi.org/project/alembic/)
- [Pydantic](https://docs.pydantic.dev/latest/)
- [Docker](https://www.docker.com/)
- [Nginx](https://nginx.org/en/)

## Running Locally

### Cloning the repository to the local machine.

```bash
git clone
```

### Install all packages

```bash
pip install -r requirements.txt
```

### Storing API key in .env file.

Create a file in root directory of project named **.env.**. And store your API key in it, as shown in the .example.env file.

### Running the application.

Then, run the application in the command line and it will be available at `http://localhost:8000`.

```bash
uvicorn main:app --reload
```

### To get access of all the APIs in the application, visit:

```bash
http://localhost:8000/docs
```

## Author

- Anchit Sinha ([@anchit1909](https://twitter.com/anchit1909))
