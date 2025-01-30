<h1>QR Code Sysrtem for Gauge Inventory Management</h1>

<h2> Problem Decsription: </h2>
MTech employs an MS Excel based system to track and manage the inventory, calibration and condition statuses, and location of gauges. While functional, this manual system is highly prone to human error, inefficiencies, and discrepancies due to the reliance on periodic data updates and continuous manual monitoring. Additionally, the complexity also increases exponentially with increasing number of gauges in circulation, creating significant risks of oversight, mismanagement, and delayed calibration activities. 

<h2> Solution:</h2>
A more robust, automated solution is required to enhance real-time tracking, improve accuracy, streamline data retrieval, and enable proactive notifications to ensure timely calibrations and maintenance, ultimately fostering a higher level of operational excellence and compliance.

<h2> Working Pronciple:</h2>
  
- <b>Centralized Database: A MySQL database was created to store and manage all critical data related to gauges, including inventory, condition, calibration status, and location.</b>
- <b>Unique Barcode Generation: Each gauge is assigned a unique barcode, generated automatically to represent the corresponding data in the system.</b>
- Test Code: https://github.com/krishnakaruturi56/QR-Code-Generation-Test-Code
- <b>API Integration: The barcode is linked to the gauge’s data in the MySQL database through an Google Drive API, enabling seamless interaction between the physical gauge and digital records. </b> 
<p align="center">
<br/>
<img src="https://imgur.com/nTkkcc8.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<p align="center">
<br/>
<img src="https://imgur.com/FxB7c0m.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>


<h2> Key Benifits & Improvements:</h2>

- <b> Real-Time Access: Scanning the barcode with a mobile device retrieves real-time data from the database, such as calibration due dates, gauge condition, and location.</b>
- <b> Automated Notifications: The system is configured to send notifications when calibrations are approaching their due dates, ensuring proactive maintenance.</b>
- <b> Improved Traceability: The solution enhances the traceability of gauges, providing quick and accurate access to historical data.</b>
- <b> Efficiency & Accuracy: The integration of the database, API, and barcode system streamlines gauge management, improving overall operational efficiency.</b>

