# ASR Rules PoSh GUI

Attack Surface Reduction Rules can be set on different ways. If you don't use any Device Management and no Group Policies, there's only one way left: Powershell. But this is not as userfriendly as I hoped (especially the GUID). So I developed GUI for setting ASR Rules via Powershell. 

## Getting Started

Download the Powershell Script from here and run it: https://github.com/hemaurer/MDATP_PoSh_Scripts/tree/master/ASR%20GUI

### Prerequisites

1. You can set attack surface reduction rules for devices that are running any of the following editions and versions of Windows:

   * Windows 10 Pro, version 1709 or later
   * Windows 10 Enterprise, version 1709 or later
   * Windows Server, version 1803 (Semi-Annual Channel) or later
   * Windows Server 2019
   * Windows Server 2016
   * Windows Server 2012 R2
   * Windows Server 2022


2. The Powershell Script as well as the Exe have to run in admin mode to work properly.

### Development
For development and testing you might need to set the Powershell ExecutionPolicy to Unrestricted. Because of Security Risk it is recommended to set the policy to restricted after finishing development.

Before Development:
```
Set-ExecutionPolicy Unrestricted
```

After Development
```
Set-ExecutionPolicy Restricted
```

### Installing

There is no installation as the EXE is based on the Powershell Script.

## Built With

* Visual Studio
* Powershell ISE 5.0


## Authors

* Hermann Maurer

## Acknowledgments
Thanks to
* António Vasconcelos - [anvascon](https://github.com/anvascon)
* [anthonws](https://github.com/anthonws)

for Inspiration and initial Code base which is used in the "Report"-Function.
