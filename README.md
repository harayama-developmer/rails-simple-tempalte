# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

---

## Build image

### Development

```bash
docker-compose run --service-ports app
```

### Production

```bash
DOCKER_BUILDKIT=1 docker build -t rails-simple-template .
docker run -p 3000:3000 rails-simple-template
```
