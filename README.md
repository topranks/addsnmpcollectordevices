

This is a simple python script which can be used to add multiple devices to SNMP Collector.

Please see the project homepage for more info on the excellent SNMP Collector:

https://github.com/toni-moreno/snmpcollector


This script has been made more as an example of how the API interface in SNMP Collector can be used.  It's stupidly basic but hopefully it may help others work out what they need to do.  The functions that logon, check if an element is present and write/update elements are designed to be fairly agnostic to the use case.  In the example they are used to add devices, but I've used them to add nearly all the other types in my work environment.

To work out what the data to write to the API should look at you can do a packet capture while using the web GUI.  The JSON is easy to see in the HTTP packets for any particular element.  You can also use the IMPORT/EXPORT function in the GUI to see the formatting of this data.

Please note project is developed to work under Python 3 only.
