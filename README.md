<h1>Azure Sentinental Map Live Cyber Attcks</h1>


<h2>Description</h2>
<b>I began by setting up a virtual machine and temporarily disabling the Windows Firewall for the simulation. I then established a Log Analytics Workspace and configured Azure Sentinel for advanced threat detection. I intentionally triggered a Remote Desktop login failure, then analyzed events in the Event Viewer. The project then focused on geolocation data, utilizing a PowerShell script and Geolocation.io API key. Data was stored in a custom log, with relevant fields extracted for analysis like the longitude and latitude. Finally, Azure Sentinel was created to visualize the geolocation data, providing a live cyber attack on a world map.</b>



<h2>Azure Virtual Machine Setup:</h2>

<p>Created a virtual machine on Azure.
Temporarily disabled the Windows Firewall on the virtual machine to simulate a scenario of live cyber attacks.</p>
<img width="720" alt="Screenshot 2023-11-10 at 11 05 49 AM" src="https://github.com/Bamlak11/Azure-CyberAttack-SIEM/assets/77420100/aea162e7-082d-44a9-a316-cdda7f3c3b80">



<h2>Log Analytics Workspace and Security Center Integration:</h2>

<p>Established a Log Analytics Workspace in Azure for collecting, analyzing, and acting on telemetry data from the virtual machine.
Integrated the Security Center with the virtual machine to enable the collection of security-related logs.</p>


<h2>Azure Sentinel Configuration:</h2>

<p>Established a connection between the Log Analytics Workspace and the virtual machine to facilitate seamless log transfer.
Configured Azure Sentinel to enable advanced threat hunting, detection, and response capabilities.</p>


<h2>Authentication Failure Testing:</h2>

<p>Attempted to log into the virtual machine using Remote Desktop, intentionally causing a login failure.
Reviewed Event Viewer logs on the virtual machine to analyze recorded events, including the login failure.</p>
<img width="720" alt="Screenshot 2023-11-10 at 10 20 59 AM" src="https://github.com/Bamlak11/Azure-CyberAttack-SIEM/assets/77420100/a0371fcc-b601-4157-a417-d2292bd527e9">



<h2>Geolocation Data Collection:</h2>

<p>Retrieved a crucial PowerShell script for obtaining geolocation data from potential attackers.
Obtained an API key from Geolocation.io to access geolocation information in the PowerShell script.
Executed the PowerShell script to collect geolocation data, enhancing cybersecurity capabilities with geospatial context.</p>
<img width="720" alt="Screenshot 2023-11-10 at 9 59 22 AM" src="https://github.com/Bamlak11/Azure-CyberAttack-SIEM/assets/77420100/e092fd43-b6c3-4109-a740-09e8256ef4e6">



<h2>Custom Log and Field Extraction:</h2>

<p>Defined a custom log in the Log Analytics Workspace to store collected geolocation data.
Extracted relevant fields from raw custom log data to facilitate easier analysis and visualization.</p>


<h2>Azure Sentinel Visualization:</h2>

<p>Configured Azure Sentinel to visualize geolocation data on a map using latitude and longitude information.
Ensured optimal map plot sizes for a clear presentation of the geolocation data.
<img width="720" alt="Screenshot 2023-11-10 at 9 38 28 AM" src="https://github.com/Bamlak11/Azure-CyberAttack-SIEM/assets/77420100/1ec9df0f-2429-441b-9756-15068ff0ef80">


  
</p>
