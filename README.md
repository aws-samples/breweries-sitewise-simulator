# Amazonian Breweries OPC UA Server Getting Started

## Summary

Amazonian Breweries is a Python based program to exercise the capabilities of IoT SiteWise (Monitor), IoT Greengrass, IoT TwinMaker, and other IoT based AWS services that constantly runs and produces factory like data via OPC UA (a cross-platform, open-source, IEC62541 standard for data exchange from sensors to cloud applications developed by the OPC Foundation). 

## Prerequisites

1. [Python3](https://www.python.org/downloads/)
   - Verify your python3 path and version (3.10.0+). 
     ```
     python3 --version

     ```
2. Install the OPC UA Server Python Library

  With pip:

    pip install opcua

  Ubuntu:

    apt install python-opcua        # Library
    apt install python-opcua-tools  # Command-line tools

  Dependencies:

    cryptography, dateutil, lxml and pytz.


