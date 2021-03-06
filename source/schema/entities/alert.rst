Alert Fields
============

 - For messages that are an alert, such as an IDS alert
 - For Vendor alert serverity levels the vendro_event_severity* fields will be used


.. list-table::
	:widths: 10 15 10 100
	:header-rows: 1
	:stub-columns: 1

	* - Field Name
	  - Example Values
	  - Field Mapping Type
	  - Notes
	* - alert_definitions_version
	  - 2020.01  |  4092348
	  - keyword
	  - Version or identification value that indicates the version a collection of signatures (A/V, etc.) is in use



.. table::
    :width: "30%", "10%", "10%", "50%"

+---------------------------+-----------------+------------+---------------------------+
| Field Name                | Example Values  | Field Type | Notes                     |
+===========================+=================+============+===========================+
| alert_definitions_version | 2020.02         | keyword    | Version or identification |
|                           |                 |            | value that indicates the  |
|                           | 4092348         |	           | version a collection of   |
|                           |                 |            | signatures (A/V, etc.) is |
+---------------------------+-----------------+------------+---------------------------+


.. csv-table:: Alerts
   :header: "Field Name", "Example Values", "Field Type", "Notes"
   :widths: 10, 15, 10, 100

   "alert_definitions_version", "2020.1 , 4092348", "keyword", "Version or identification value that indicates the version a collection of signatures (A/V, etc.) is in use"


.. csv-table:: Alerts CSV
   :file: /Volumes/TB3_External/nick_github/docs/build/html/schema/entities/alerts.csv
   :widths: 10, 15, 10, 100
   :header-rows: 1
   :delim: ,


.. csv-table:: Alerts CSV 2
   :file: alerts.csv
   :widths: 10, 15, 10, 100
   :header-rows: 1
   :delim: ,