# TM data
TM data - set of scripts for easy and user-friendly view of tranSMART data.
  - scripts folder contains R and MATLAB scripts;
  - sql folder contains SQL scripts for Oracle and PostgreSQL databases that create necessary views.

# Installing for Oracle
From `sql/oracle/` run script **tm_data_oracle.sql** using SQL Developer of sqlplus with database user `system`.

This script creates new tablespace tm_data with following views:
  - List of all studies;
  - List of all patients;
  - List of clinical attributes;
  - List of clinical values;
  - List of all values on Materialized View;
and indexes for following clinical values:
  - Patient number;
  - Subject id;
  - Clinical attribute;
  - Data value.