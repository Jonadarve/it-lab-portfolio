
## System Update and User setup
- ran 'apt update' and 'apt upgrade' to bring system current
- manually upgraded 2 packages: 'gzip', 'ubuntu-drivers-common'
- created non-root user and added to 'sudo' group for admin privileges

## Ubuntu Server post-install tasks
- installed OpenSSH server
- verified SSH is running
- captured local IP address

## Comands used 
'sudo apt update'
'sudo apt upgrade'
'apt list --upgradeable'
'sudo apt install'
'sudo adduser'
'sudo usermod -aG'

## Notes
- will use SSH from host machine for remote terminal access
- panning to install 'fail2ban' later for basic SSH hardening