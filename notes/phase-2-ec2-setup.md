# Phase 2 - EC2 Setup

## Services Used
- EC2
- Security Groups
- EBS Root Volume

## Instance Details
- Ubuntu 24.04
- t2.micro
- 20GB gp3 storage

## Installed Software
- Nginx

## Ports Opened
- 22 SSH
- 80 HTTP
- 443 HTTPS

## Commands Used

### Update Server
sudo apt update && sudo apt upgrade -y

### Install Nginx
sudo apt install nginx -y

### Start Nginx
sudo systemctl start nginx

### Enable Nginx
sudo systemctl enable nginx
