# cst8919Lab3: Grafana Installation and Dashboard Creation for Ubuntu Server Performance

## Result and screenshots: 

### Task 1 & 2
Connected to Grafana server from PowerShell

![alt text](connect-Grafana-server.png)
Add inbound rule to allow conect to rafana server from internet (port 3000)
![alt text](inbound-rule.png)

### Task 5: Connect Grafana to Azure Monitor
- Connect to Grafana server from browser
![alt text](Grafana-login.png)
- Home page of Grafana server
![alt text](Grafana-home.png)
- Register application: in order to allow Grafana connect to Azure VM, we need to register Grafana in Azure Active Directory 
![alt text](Register-application.png)

![alt text](Register-application-secret.png)

- Add the role ‘Monitoring reader’ for Gafana 
![alt text](Add-monitoring-reader-role.png)

![alt text](Add-monitoring-reader-role-2.png)

- Create connection from Grafana to Azure VM 
![alt text](Create-connection-VM.png)

### Task 6: Create a Dashboard in Grafana

![alt text](Create-Dashboard.png)


