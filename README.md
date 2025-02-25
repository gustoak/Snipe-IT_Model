# Snipe-IT Installation Guide

## Description
Snipe-IT is a powerful open-source IT asset management system designed for tracking hardware and software assets.

## Features
- Asset lifecycle tracking
- License management
- User and department assignment
- REST API for automation

## Docker Installation
To install Snipe-IT using Docker, run the following command:

```bash
docker run -d --name snipeit \
  -e APP_KEY=base64:YOUR_GENERATED_KEY \
  -e DB_HOST=db \
  -e DB_DATABASE=snipeit \
  -e DB_USERNAME=snipeit \
  -e DB_PASSWORD=yourpassword \
  -p 8080:80 snipe/snipe-it
```

## Resources
- **GitHub**: [https://github.com/snipe/snipe-it](https://github.com/snipe/snipe-it)
- **Documentation**: [https://snipe-it.readme.io/](https://snipe-it.readme.io/)

