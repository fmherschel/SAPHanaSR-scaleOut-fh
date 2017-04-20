# SAP HANA System Replication (Scale-Out)

## Purpose

SAPHanaSR-scaleOut includes the resource agents for pacemaker based clusters to automize the System-Replication (takeover,
register) for two SAP HANA system replication sites.

## File structure

- `doc` contains readme, license and the PDF with a link to the latest best practice guides;
- `man` contains manual pages;
- `ra` contains the actual resource agents, `SAPHana` and `SAPHanaTopology`;
- `test` contains the Perl auxiliary library and scripts that are installed to `/usr/sbin` and `/usr/share/SAPHanaSR/tests`;

## Building

