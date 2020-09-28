# Golang banking app

[![Fintech-Backend](https://img.shields.io/badge/wborbajr-FintechAPI-red)]()
[![License](https://img.shields.io/github/license/wborbajr/fintech-backend)]()
[![Code Size](https://img.shields.io/github/languages/code-size/wborbajr/fintech-backend)]()
[![Repo Size](https://img.shields.io/github/repo-size/wborbajr/fintech-backend)]()
[![GO](https://img.shields.io/github/go-mod/go-version/wborbajr/fintech-backend)]()
[![Languages](https://img.shields.io/github/languages/count/wborbajr/fintech-backend)]()
[![Build](https://img.shields.io/github/workflow/status/wborbajr/fintech-backend/Go)]()
[![Docker Build](https://img.shields.io/docker/build/wborbajr/fintech-backend)]()

Golang banking App backend

## Run

- Setup a PostgreSQL db
- You need to setup your connection string in the two files, vulnerable-db.go, and migrations.go
- Start migration by commenting migration in main.go and commenting API
- Type  (that will migrate to your db):
```
go run main.go
```
- Comment migration and uncomment api
- Type:
```
go run main.go
```

### Adapted from
duomly.com
