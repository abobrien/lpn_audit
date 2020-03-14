# lpn_audit
Audit LPNs against a CSV export from a core WMS system

A typical warehouse management system (WMS) like JDA (rebranded to Blue Yonder in 2020), Manhattan, or SAP has a pick feature which instructs warehouse associates to select and scan parts from a rack\bin in a warehouse. Due to the human error, sometimes the physical items that are removed from the warehouse rack\bin are not the ones that WMS directed the user to select. Audit tools like the example code provided are often employed to detect errors in the pick process to correct inventory and ensure accurate delivery of ordered goods to the end customer.

This Python application leverages core langauge capabilites and the pandas package to compare data derived from a CSV file to user input data. Matches and inconsistencies are displayed to provide an overall accuracy rating. In a warehouse environment, this information would be leveraged to return inaccurate picks to inventory and identify corrections needed to deliver an accurate order to the end customer.
