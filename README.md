# Check-token-privs
Checking a process tokens privileges using the Windows API 

This is a follow on from Opentoken.py, I've added some code to check the tokens privileges to see if a specific priv is enabled or disabled, you can replace SEDebugPrivilege with another priv you want to check for example SESecurityPrivilege, or any of the other privs in the processes token.
