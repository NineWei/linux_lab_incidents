# Project: Linux Lab with Incident Simulations

This is a personal lab project created to practice Linux commands, simulate common failures, and understand how logs, incidents, and containers work.

## Tools used
- Ubuntu Server 24.04.2 (on VM)
- Docker
- NGINX
- Terminal (Bash)

## Simulations performed

### Disk space full
```bash
sudo dd if=/dev/zero of=~/bigfile bs=1M count=512
df -h
rm ~/bigfile
