SG13G2 LVS Tests
================

This directory contains the LVS test cases for SG13G2 technology.


Folder Structure
----------------

```text
📁 testcases
 ┣ 📜README.md                       This file to document the unit tests.
 ┣ 📁 unit                           Contains the unit test structures per device.
   ┣ 📁<device_group>_devices        Contains all LVS testcases for each group.
    ┣ 📁layout                       Layout gds file for each device.
    ┣ 📁netlist                      Spice netlist file for each device.
 ┣ 📁 extraction_checking            Contains a small test case to be used for testing the LVS switches.
 ```
