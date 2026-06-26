# juice-shop-lab
# OWASP Juice Shop Deployment Lab

This repository documents the setup and deployment of the OWASP Juice Shop web application using Docker inside a Kali Linux environment.

## Setup & Installation Steps

1. **Pull the Docker Image:**
```bash
sudo docker pull bkimminich/juice-shop
```
2. run container:
sudo docker run -d -p 3000:3000 --name juice bkimminich/juice-shop

