# Checklist

- [ ] Update the system packages (`apt update && apt upgrade` or equivalent).
- [ ] Create a non-root user with sudo privileges.
- [ ] Disable root login via SSH.
- [ ] Configure SSH key authentication and disable password authentication.
- [ ] Change the default SSH port (optional but recommended).
- [ ] Setup a firewall (e.g., UFW or iptables) and allow only necessary ports.
- [ ] Install Fail2Ban to protect against brute-force attacks.
- [ ] Enable automatic security updates.
- [ ] Secure shared memory (optional).
- [ ] Verify time synchronization (NTP).
