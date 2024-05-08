<h2>LAN Ethernet Direct Connection Problem</h2>

Date Reported: 11/24/2023 <br>
Date Resolved: 11/24/2023
<br>
<br>
<b>Observed Issue:</b>
<br>
<br>
Upon establishing a direct LAN Ethernet connection using a Type-C extension cable, the monitor displayed successfully, <br>
while other peripherals connected to the Type-C hub remained unresponsive. Internet and USB connectivity were unavailable.<br>
<br>
<b>Solution:</b>
<br>
<br>
After troubleshooting the connection, it was determined that the Type-C extension cable was the source of the issue. <br>
Replacing the extension cable with a Type-C hub adapter directly connected to the laptop resolved the connectivity problem, <br>
restoring functionality to all peripherals and network access.<br>

<b>Recommendation:</b><br>

To ensure consistent and reliable connectivity, it is recommended to utilize a Type-C hub adapter directly connected to the laptop, <br>
bypassing the need for a Type-C extension cable. This approach eliminates the potential for compatibility issues and ensures optimal <br> performance for all connected devices.

<hr>

<h2>Technical Analysis of Desktop Fan and Power Supply Fluctuation</h2>

Date Reported: 11/23/2023 <br>
Date Resolved: 11/23/2023<br>

<b>Initial Observation:</b>

Upon power on, the desktop fails to display anything, and the rear fan exhibits intermittent rotation, indicating a potential hardware malfunction.

<b>Troubleshooting Steps:</b>

<b>Internal Inspection:</b>
a. Open the desktop and check for loose connections and dust accumulation.
b. Remove and reseat all peripheral connections and perform thorough dust cleaning.

<b>Power Supply Check:</b>
a. Disconnect all power supply connections from the desktop components.
b. Power on the desktop with only the power supply connected to the motherboard.
c. If the power supply fan continues to spin consistently, the issue likely lies within the motherboard or other components.

<b>Motherboard Inspection:</b>
a. Reseat the RAM modules into different slots and perform additional dust cleaning.
b. Reconnect all internal cables and peripherals.

<b>Resolution:</b>

After completing these troubleshooting steps, the desktop successfully booted, and both fans maintained consistent rotation. The culprit was likely dust buildup causing intermittent connections and disruptions to the power flow.

<b>Conclusion:</b>

Regular dust cleaning and maintenance are crucial for ensuring optimal performance and preventing potential hardware malfunctions.

<hr>

<h2> Technical Report: Fixing IGSL Scholarship Adding Features</h2>

Date Report: 11/28/2023 <br>
Date Fixed: 11/28/2023

<b>Problem: </b>

The existing Bootstrap modal used for adding new scholarship entries was not functioning properly. The modal would appear and disappear rapidly, making it difficult for users to interact with the form.

<b>Analysis: </b>

Investigation revealed that the Bootstrap modal was being triggered too quickly, causing it to close before the user had a chance to enter the required information. Additionally, the modal's styling was not consistent with the rest of the application, which made it visually jarring.

<b>Solution:</b>

To address these issues, we decided to replace the Bootstrap modal with the Magic Popup library. Magic Popup is a lightweight and versatile library that offers more control over the modal's appearance and behavior.

<b>Implementation:</b>

Replaced Bootstrap modal with Magic Popup: The existing Bootstrap modal code was removed and replaced with the Magic Popup library.

Customized Magic Popup styling: The styling of the Magic Popup was customized to match the overall look and feel of the application.

Adjusted modal timing: The timing of the modal's appearance and disappearance was adjusted to ensure that users had sufficient time to interact with the form.

<b>Testing:</b>

After implementing the changes, thorough testing was conducted to ensure that the new modal was functioning correctly and providing a positive user experience.

<b>Results:</b>

The Magic Popup modal successfully replaced the problematic Bootstrap modal, providing a stable and consistent user experience. The modal now opens and closes smoothly, allowing users to easily enter the required information for adding new scholarship entries.

<b>Recommendation:</b>

We recommend continuing to use Magic Popup for modal functionality throughout the application to maintain consistency and ensure a seamless user experience. Additionally, we suggest regular maintenance and updates to the Magic Popup library to keep up with the latest developments and security enhancements.

<hr>


<h2>Technical Report: Addressing Student's Laptop Performance Issues</h2>

Date Reported: 11/28/2023 <br>
Date Fixed: 11/28/2023

<b>Issue: </b>

A student reported experiencing slow boot times and sluggish navigation on their laptop, hindering their productivity and overall user experience.

<b>Investigation:</b>

To understand the root cause of the performance issues, further investigation was necessary. This could involve:

Collecting system specifications: Gathering information about the laptop's hardware, such as CPU, RAM, and storage, to identify potential bottlenecks.

Checking resource utilization: Monitoring CPU, RAM, and disk usage patterns to identify any excessive resource consumption that could be causing the slowdown.

Analyzing startup programs: Identifying any unnecessary or resource-intensive programs that are automatically launching at startup and contributing to the slow boot times.

Assessing disk health: Checking the health of the hard drive or SSD to ensure it's not experiencing any physical or performance issues.

Scanning for malware or viruses: Running a thorough scan for malware or viruses that could be affecting system performance.

<b>Recommended Solution:</b>

Based on the findings of the investigation, an appropriate solution could be implemented, such as:

Optimizing startup programs: Disabling unnecessary startup programs to reduce the load on the system during boot.

Upgrading hardware: Upgrading RAM or switching to a solid-state drive (SSD) if the laptop's hardware is outdated or insufficient.

Performing disk maintenance: Defragmenting the hard drive or running disk cleanup tools to improve disk performance.

Removing malware or viruses: Removing any detected malware or viruses to restore system performance and security.

<b>Referral to Kuya Andy: </b>

Considering the complexity of troubleshooting laptop performance issues and the potential need for hardware upgrades, it was suggested to refer the student to Kuya Andy. Kuya Andy is a trusted technician with expertise in laptop repair and upgrades. He can provide a comprehensive assessment of the student's laptop, identify the underlying issues, and recommend the most suitable solution.

<b>Conclusion:</b>





The student's laptop performance issues were addressed by recommending Kuya Andy for further assistance. Kuya Andy's expertise in laptop repair and upgrades will ensure that the student's laptop is diagnosed and repaired effectively, restoring optimal performance and a seamless user experience.

<hr>


<h2>Technical Report: Resolving Google Search Bar Issue in New Chrome Tabs</h2>

<b>Issue:</b>

Users reported encountering an issue where the Google search bar was not displaying on the current tab when creating a new tab in Chrome. This issue disrupted the user's ability to seamlessly search the web using the integrated Google search functionality.

<b>Investigation:</b>

To identify the root cause of this issue, an investigation was conducted. This involved:

Reviewing user reports: Analyzing user reports to understand the specific circumstances and context in which the issue occurred.

Replicating the issue: Attempting to reproduce the issue in a controlled environment to gain further insights.

Checking browser settings: Reviewing the user's Chrome settings to identify any potential configuration conflicts.

<b>Diagnosis:</b>

The investigation revealed that the issue stemmed from the Chrome setting "On startup," which was configured to open a specific page instead of the default new tab page. This configuration prevented the Google search bar from rendering correctly on the new tab.

<b>Solution:</b>

<b>To resolve the issue, the following solution was implemented:</b>

Changing startup settings: The "On startup" setting was modified to open the new tab page instead of the specific page.
Testing:

After implementing the solution, thorough testing was conducted to ensure that the Google search bar was consistently displaying on the current tab when creating new tabs.

<b>Results:</b>

The implemented solution effectively resolved the issue, and the Google search bar was now reliably displayed on the current tab when creating new tabs. Users were able to seamlessly search the web without encountering the previous disruption.

<b>Recommendations:</b>

<b>To prevent similar issues from recurring, we recommend:</b>

Educating users: Provide clear instructions and guidance to users regarding Chrome settings, especially those related to startup behavior.

Monitoring settings changes: Implement mechanisms to monitor for any changes to critical settings that could affect user experience.

Regularly updating Chrome: Ensure that users are running the latest version of Chrome to benefit from bug fixes and performance enhancements.
