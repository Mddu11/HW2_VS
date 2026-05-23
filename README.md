node_modules
dist
.git
.gitignore
README.md
Dockerfile
npm-debug.log
.vscode
.idea# Frontend Docker

## Build

```bash
docker build -t yourlogin/frontend:1.0.0 -t yourlogin/frontend:latest .
```

## Run

```bash
docker run --rm -p 8080:80 yourlogin/frontend:1.0.0
```

## Check

Open:

http://localhost:8080

or:

```bash
curl http://localhost:8080
```

## Images

```bash
docker images
```