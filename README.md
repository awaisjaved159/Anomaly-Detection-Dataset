# Anomaly-Detection-Dataset
For building the windows based HIHP we are using three different utilities that are running on the windows machine.
1.	Sysmon (For logging all the system events)
2.	Scappy (Our own python-based code that will monitor network logs)
Sysmon logs
System Monitor (Sysmon) is a Windows system service and device driver that, once installed on a system, remains resident across system reboots to monitor and log system activity to the Windows event log. It provides detailed information about process creations, network connections, and changes to file creation time.
By collecting the events it generates using Windows Event Collection or SIEM agents and subsequently analyzing them, we can identify malicious or anomalous activity and understand how intruders and malware operate on our network.
The core of effective Sysmon use is in writing good XML configurations. Olaf Hartong has provided a modular Sysmon configuration called Sysmon-modular which logs the event ID’s directly to the ATT&CK framework. It provides customizable and rapid deployment of Sysmon configuration files.
