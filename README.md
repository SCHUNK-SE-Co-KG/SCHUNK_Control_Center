# SCHUNK_Control_Center

<h3>Description</h3> <p>This is SCHUNK's Setup- and Configuration Software for electromechanical grippers of the type EGU and EGK.
  Please connect the gripper with the network of your PC to gain access to our devices.
</p>
<h3>Compatible Systems</h3> <p>
  SCHUNK EGU and EGK gripping modules with industrial Ethernet. <br>
  Runs on Windows Systems with Windows 10 and greater.
</p>

![2024-01-12 14_55_30-SCHUNK](https://github.com/SCHUNK-SE-Co-KG/SCHUNK_Application/assets/156294426/fa93410e-6bb7-479f-b0b2-7076d1d7937c)

<h3>Release notes:</h3>
Information: Supported SCHUNK devices are EGU, EGK and EZU grippers with firmware version 5.1, 5.2 or 5.3 and the EGP 40-IL-GKS gripper.

Fixed Bugs:

- Fixed an issue with parameters containing invalid data
- Fixed wrong display of some parameter data 
- Smaller issues within the scripting feature in Mechatronic Gripper app are fixed
- Several smaller improvements and Bug fixes


Improvements & new features:

- You can now enable a console in the settings, to view all data communicated with modules
- The EGP 40-IL-GKS is now supported
- You can now connect via Wireless to supported Grippers 


Known issues:

- Flashing the version 6.1 via wireless connection to a gripper, may fail depending on the state of the gripper. Try the flashing process again.
- The app sometimes does not recognize a failed shutdown of the connected gripper. 
- After switching the language some inputs are marked as invalid depending on the used decimal separator. 
- Performance issues via Modbus and IO-Link
