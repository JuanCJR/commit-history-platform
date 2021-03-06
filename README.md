# commit-history-platform

## Description

This repo contain the backend and frontend repositories like submodules

## Clone repository

Clone this repo with the option --recurse-submodules:

```bash
$ git clone --recurse-submodules https://github.com/JuanCJR/commit-history-platform.git
```

This command will clone the backend (bff-commit-history) and the frontend (fe-commit-history) repository into the commit-history-platform folder.

## Installation

### Backend

Go to the bff-commit-history directory and installl dependencies

```bash
$ cd ./bff-commit-history

$ npm install
```

### Frontend

Go to the fe-commit-history directory and installl dependencies

```bash
$ cd ./fe-commit-history

$ npm install
```

## Configuration

Create the .env file for the backend and the frondend project

### bff - Backend .env example

```bash
APP_PORT=8081

GIT_API_URL=https://api.github.com
```

### fe - Frontend .env example

```bash
REACT_APP_BFF_API_URL=http://localhost:8081/api/historial-commits/v1
```

## Running the app

### Backend

```bash
$ cd ./bff-commit-history

$ npm run start

```

### Frontend

```bash
$ cd ./fe-commit-history

$ npm run start
```

Note: run the backend and frontend project in two different terminals.
