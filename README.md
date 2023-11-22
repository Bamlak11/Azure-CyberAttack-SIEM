<h1>Azure Sentinental Map Live Cyber Attcks</h1>


<h2>Description</h2>




<h2>Azure Virtual Machine Setup:</h2>

<p>Created a virtual machine on Azure.
Temporarily disabled the Windows Firewall on the virtual machine to simulate a scenario with the firewall turned off.</p>

<h2>Log Analytics Workspace and Security Center Integration:</h2>

<p>Established a Log Analytics Workspace in Azure for collecting, analyzing, and acting on telemetry data from the virtual machine.
Integrated the Security Center with the virtual machine to enable the collection of security-related logs.</p>

<h2>Azure Sentinel Configuration:</h2>

<p>Established a connection between the Log Analytics Workspace and the virtual machine to facilitate seamless log transfer.
Configured Azure Sentinel, Microsoft's cloud-native SIEM solution, to enable advanced threat hunting, detection, and response capabilities.</p>

<h2>Authentication Failure Testing:</h2>

<p>Attempted to log into the virtual machine using Remote Desktop, intentionally causing a login failure.
Reviewed Event Viewer logs on the virtual machine to analyze recorded events, including the login failure.</p>

<h2>Geolocation Data Collection:</h2>

<p>Retrieved a crucial PowerShell script for obtaining geolocation data from potential attackers.
Obtained an API key from Geolocation.io to access geolocation information in the PowerShell script.
Executed the PowerShell script to collect geolocation data, enhancing cybersecurity capabilities with geospatial context.</p>

<h2>Custom Log and Field Extraction:</h2>

<p>Defined a custom log in the Log Analytics Workspace to store collected geolocation data.
Extracted relevant fields from raw custom log data to facilitate easier analysis and visualization.</p>

<h2>Azure Sentinel Visualization:</h2>

<p>Configured Azure Sentinel to visualize geolocation data on a map using latitude and longitude information.
Ensured optimal map plot sizes for a clear and comprehensible presentation of geolocation data.
<img src=

  
</p>
