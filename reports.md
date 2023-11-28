<h2>LAN Ethernet Direct Connection Problem</h2>

Date Reported: 2023–11–24 <br>
Date Resolved: 2023–11–24
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

Date Reported: 2023-11-23 <br>
Date Resolved: 2023-11-23<br>

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

Date Report: 11.28.2023
Date Fixed: 11.28.2023

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