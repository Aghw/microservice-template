# Microservice template

## Getting started locally

```bash
npm install

# Without environment variables
npm start

# With environment variables
APP_ID="app_id_value" npm start
```

## To deploy

```bash
now

# Environment variables
now -e APP_ID="app_id_value"
```