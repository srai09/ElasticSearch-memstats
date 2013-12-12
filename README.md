ElasticSearch-memstats
======================

Nagios plugin to monitor ElasticSearch Memory Stats. It checks the percentage Heap utilization and throws an alert if greater than Critical threshold.

Can also use the script to plot cacti graphs. For now it outputs the following for Cacti: 
Total_Heap_Size: Heap_Used: G1_Eden_Space_Used: G1_Survivor_Space_Used: G1_Old_Gen_Space_Used:
