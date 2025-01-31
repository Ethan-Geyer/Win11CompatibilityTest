# Win11CompatibilityTest
PowerShell script to test Windows 11 Compatibility
# Windows 11 Compatibility Checker Script
# This script checks if a machine meets the minimum requirements for Windows 11.

# Requires -RunAsAdministrator.
# It must be inside a root directory; "C:\temp" is known to work.
# PS1 execution must not be restricted. 
# Run "Set-ExecutionPolicy RemoteSigned" then "Y" to ensure PS1 file execution is enabled.
# If the PS1 file is located inside the temp folder, use "C:\Temp\Win11CompTestV3.ps1" to run the test.

# After completion, test results will be displayed in PowerShell. 
# The script will also create a .txt file named after the machine name with the results in the same folder where it was run.
