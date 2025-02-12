# [Brute Force Analysis Playbook](#brute-force-analysis-playbook)

## Steps

1. **Initial Triage**  
   - Validate the alert and collect information:
     - Source IP  
     - Target system  
     - Number of attempts  

2. **Log Analysis**  
   - Review authentication logs for multiple failed login attempts.

3. **Source IP Investigation**  
   - Check the reputation of the source IP.

4. **Account Lockout**  
   - Temporarily lock the targeted accounts.

5. **Containment**  
   - Block the source IP at the firewall or IDS/IPS.

6. **Remediation**  
   - Educate users on creating strong passwords.  
   - Implement multi-factor authentication (MFA).  
   - Review and update account lockout policies.

## Reputation Check Tools

- [IPVoid](http://www.ipvoid.com)  
- [AbuseIPDB](https://www.abuseipdb.com)
