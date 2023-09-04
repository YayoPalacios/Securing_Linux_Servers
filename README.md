# Securing Linux Servers - Cheat Sheet

This cheat sheet provides a quick reference for securing Linux servers.

| **Tasks**                              |
|----------------------------------------|
| Initial Server Setup                   |
| - Log in to the server using SSH        |
| - Update the system: `sudo apt update`  |
| - Change SSH port, disable root login   |
|                                        |
| Firewall Configuration                 |
| - Configure a firewall (UFW, etc.)      |
| - Allow necessary incoming/outgoing     |
|                                        |
| User Management                        |
| - Create a superuser with sudo privileges |
| - Disable password-based authentication |
| - Remove unnecessary default users      |
|                                        |
| SSH Configuration                       |
| - Generate SSH keys on the local machine |
| - Upload the public key for secure authentication |
| - Configure key-based authentication    |
|                                        |
| Security Updates                       |
| - Set up automatic security updates     |
|                                        |
| Web Server (if needed)                 |
| - Set up a web server (Nginx, Apache)   |
| - Configure SSL/TLS with Let's Encrypt  |
|                                        |
| Database (if needed)                   |
| - Install and secure the database       |
| - Avoid using default usernames/passwords |
|                                        |
| Monitoring & Logging                   |
| - Set up monitoring tools               |
| - Configure centralized logging         |
|                                        |
| Security Enhancements                  |
| - Consider implementing tools like fail2ban |
| - Enable automatic security updates     |
|                                        |
| Backups                                |
| - Regularly backup server data and configuration |
| - Store backups in a secure off-site location |
