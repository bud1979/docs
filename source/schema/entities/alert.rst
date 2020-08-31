Alert Fields
============

 - For messages that are an alert, such as an IDS alert
 - For Vendor alert serverity levels the vendro_event_severity* fields will be used


.. list-table::
	:widths: 10 30 10 100
	:header-rows: 1
	:stub-columns: 1

	* - Field Name
	  - Example Values
	  - Field Mapping Type
	  - Notes
	* - alert_definitions_version
	  - 2020.01    4092348
	  - keyword
	  - Version or identification value that indicates the version a collection of signatures (A/V, etc.) is in use



+---------------------------+-----------------+------------+---------------------------+
| Field Name                | Example Values  | Field Type | Notes                     |
+===========================+=================+============+===========================+
| alert_definitions_version | 2020.02         | keyword    | Version or identification |
+---------------------------+ 4092348         |            | value that indicates the  |
|                           |                 |	           | version a collection of   |
|                           |                 |            | signatures (A/V, etc.) is |
+---------------------------+-----------------+------------+---------------------------+


+----------------------------------------------------------+
|                Results                                   |
+------------------------------+---------------------------+
|                              |        Contestant         |
| Filed Name                   +---------+--------+--------+
|                              |  John   | Andrea | Robert |
+------------------------------+---------+--------+--------+
| alert_definitions_version    | 2020.02 |   2:05 |   1:15 |
|                              | 4092348 |        |        |
+------------------------------+---------+--------+--------+
| Running                      | 15:30   |  14:10 |  15:45 |
+------------------------------+---------+--------+--------+