# Start here - Overview
# Repository list and description in alphabetical order

In addition a video that describes the installation and the workflow of AMR-Control can be found in this repository.

## Step by step tutorial-video
[Step by step video](https://github.com/flexmill/Overview/blob/main/FlexMill_Installation.mp4)


## AMRControl
[Link to the repository: https://github.com/flexmill/AMRControl](https://github.com/flexmill/AMRControl)

C# Code for operating the AMR through a Web-interface
In this repository all code, that is needed to control the AMR via Web-interface is located.
A detailled installation description can be found there.

## CAD_CAM_Automatization
[Link to the repository: https://github.com/flexmill/CAD_CAM_Automatization](https://github.com/flexmill/CAD_CAM_Automatization)

Automatization of the CAD and CAM process to generate 3D models, drawings and NC code for machining automatically. This software piece is not part of the developed ROSE-AP but developed within the DIH2 programme for the automatization of manufacturing and engineering prcesses in an agile manner. It could not be integrated in the ROSE-AP, because of licensed third party software (CATICA-V5), but the source code can be used for further development and if required configurations to parts of interest can be performed.

## Fiware-databroker-console
[Link to the repository: https://github.com/flexmill/Fiware-databroker-console](https://github.com/flexmill/Fiware-databroker-console)

Reads performance-data from Fiware, parses it and stores raw and parsed data in a database for visualisation with Superset on RAMP
In this repository the code, that retrieves performance-data from Fiware is located.
The software is runnning in a console window and needs a SQL-compatible Database for storing the data.

A detailled installation description can be found there.

The needed SQL-Structures can be found here: [https://github.com/flexmill/Data-structures](https://github.com/flexmill/Data-structures)

## fiware_connector_machiningcentre_tools
[Link to the repository: https://github.com/flexmill/fiware_connector_machiningcentre_tools](https://github.com/flexmill/fiware_connector_machiningcentre_tools)
Connects to machining centres and ERP system as well as Tool Database Wintool to read machining data, work orders and tool data. It processes these data and sends ot top the Fiware Context Broker in standardized manner for further processing of subsequent software pieces to get performance data as well as the automation of the tool logistics and tool replacement based on the tool life data. The repository also contains artificial machining data.

## Data structures
[Link to the repository: https://github.com/flexmill/Data-structures](https://github.com/flexmill/Data-structures)

All data-structures that are used by the project are stored here.
The SQL commands to generate the database-structure for Fiware-databroker-console are stored in the repository too.

## Superset-connector
Configuration to connect Superset on the RAMP-Plattform to the database that stores the data that has to be visualized.
This repository contains the configuration for RAMP to access and visualize the performance-data.
