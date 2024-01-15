# SCHUNK_Application

<h3>Description</h3> <p>This is SCHUNK's Setup- and Configuration Software for electromechanical grippers of the type EGU and EGK.
  Please connect the gripper with the network of your PC to gain access to our devices.
</p>
<h3>Compatible Systems</h3> <p>
  SCHUNK EGU and EGK gripping modules with industrial Ethernet. <br>
  Runs on Windows Systems with Windows 10 and greater.
</p>

![2024-01-12 14_55_30-SCHUNK](https://github.com/SCHUNK-SE-Co-KG/SCHUNK_Application/assets/156294426/fa93410e-6bb7-479f-b0b2-7076d1d7937c)

<h3>Release notes:</h3>
Information: Supported SCHUNK devices are EGU and EGK grippers with firmware version 5.1 or 5.2.

Fixed Bugs:

* Fixed a problem where firmware was not flashed correctly to the gripper module.
* Fixed “Prepare for shutdown” functionality did not work properly.
* Fixed a crash, when user was trying to write invalid parameter values to the gripper.

Improvements & new features:

* 200% Grip force on EGU grippers is now supported.
* The official gripper firmware releases 5.1 and 5.2 are now integrated for firmware update.
* In all GUI elements, comm. FW version is replaced with gripper FW version to avoid confusion.
* Some minor design changes.
* General stability and performance improvements.

Known issues:

* Sometimes the screen gets stuck at “Searching for devices” process. If this is happening to you, please retrigger “Search devices”.
* The parameters of a module are getting hidden when using the "Reconnect" function in “Configuration” menu. To display them again, use function “Refresh” in “…” menu of Parameters tab, or reconnect to the gripper module from device selection dialogue.
* When user changes IP configuration from an already connected device using "Configuration" menu, there is no automatic reconnect to the new IP address. Please reconnect manually using the device selection dialogue.
