## Virtual SOC – Red Team vs Blue Team Simulation

### Objective
Simulate a real-world cyberattack and detect it using a SIEM.

### Tools Used
- Oracle VirtualBox
- Ubuntu
- Windows 11
- Wazuh SIEM
- Nmap

### Attack Scenario
The Red Team performed network reconnaissance and simulated unauthorized access attempts against a Windows host.

### Detection & Response
The Blue Team analyzed logs using Splunk and identified:
- Port scanning activity
- Multiple failed login attempts
- Source IP of attacker

### Outcome
Attack was successfully detected and documented with timestamps and evidence.