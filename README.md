# SCHUNK_Control_Center

<h3>Description</h3> <p>This is SCHUNK's Setup- and Configuration Software for electromechanical grippers of the type EGU, EGK and EZU and the SCHUNK FT-Sensor.
  Please connect the device with the network of your PC to gain access to your devices.
</p>
<h3>Compatible Systems</h3> <p>
  SCHUNK EGU, EZU and EGK gripping modules with industrial Ethernet. <br>
  SCHUNK FT-Sensor with Firmware >= 2.1 <br>
  Runs on Windows Systems with Windows 11
</p>

![2024-01-12 14_55_30-SCHUNK](https://github.com/SCHUNK-SE-Co-KG/SCHUNK_Application/assets/156294426/fa93410e-6bb7-479f-b0b2-7076d1d7937c)

<h3>Release notes:</h3>
Information: Supported SCHUNK devices are EGU, EGK and EZU grippers with firmware version 5.1+ and the EGP 40-IL-GKS gripper.
Supported operating systems: Windows 11

<h4>Mechatronic Grippers</h4>

- Compatible Devices: EGP 40-IL-GKS, EZU, EGU (v5.1+), EGK (v5.1+)
- Supported Communication: PROFINET, EtherNet/IP, EtherCAT via EoE, ModBus, IO-Link, Wireless

Features
- Introduced new ROS communication interface to connect to grippers that are e.g. connected to a UR robot using SCHUNK Polyscope X robot plugin.
- Minor UI changes to improve experience.

Bug fixes
- Fixed an issue where you where not able to see manually added grippers.
- Fixed some problems when filtering found grippers using the search bar.

<h4>FTS</h4>

- Compatible Devices: FTS (v2.1.0+)
- Supported Communication: PROFINET, EtherNet/IP, EtherCAT via EoE

Features
- Added new FTS Firmware 2.3.2
- Reworked UI for better experience with different display resolutions
- Added new "Data monitoring" tab to get signal statisitcs
- Overrange limits can now be exported to file
- Displayed mechanical overrange limits are now in µm/m
- New tooltips to explain functions to the user
