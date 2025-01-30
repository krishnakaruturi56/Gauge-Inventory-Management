<h1>QR Code Sysrtem for Gauge Inventory Management</h1>

<h2> Problem Decsription: </h2>
MTech employs an MS Excel based system to track and manage the inventory, calibration and condition statuses, and location of gauges. While functional, this manual system is highly prone to human error, inefficiencies, and discrepancies due to the reliance on periodic data updates and continuous manual monitoring. Additionally, the complexity also increases exponentially with increasing number of gauges in circulation, creating significant risks of oversight, mismanagement, and delayed calibration activities. 

<h2> Solution:</h2>
A more robust, automated solution is required to enhance real-time tracking, improve accuracy, streamline data retrieval, and enable proactive notifications to ensure timely calibrations and maintenance, ultimately fostering a higher level of operational excellence and compliance.

<h3> Working Pronciple:</h3>
- <b>Centralized Database: A MySQL database was created to store and manage all critical data related to gauges, including inventory, condition, calibration status, and location.</b>
- <b>Unique Barcode Generation: Each gauge is assigned a unique barcode, generated automatically to represent the corresponding data in the system.</b>
- <b>API Integration: The barcode is linked to the gauge’s data in the MySQL database through an Google Drive API, enabling seamless interaction between the physical gauge and digital records. </b> 

<p align="center">
<br/>
<img src="https://imgur.com/p1vv3DR.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<p align="center">
<br/>
<img src="https://imgur.com/8htK8jn.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>


<h2> Key Benifits & Improvements:</h2>

- <b>Reduced Scrap: Early detection of insert damage leads to fewer defective parts.</b>
- <b>Extended Tool Life: Predictive tool change capabilities have led to a 25% increase in insert life for half of the inserts, reducing overall tool replacement costs.</b>
- <b>Labor Savings: Elimination of manual inspection removes the need for inspection operators</b>
- <b>Improved Operational Efficiency: Real-time detection and stoppage of the lathe increases production efficiency.</b>
<p align="center">
<br/>
<img src="https://imgur.com/o6PysRA.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
