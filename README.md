# SecureSDT

SecureSDT (Standard Deployment Toolkit) is used to securely configure Windows 10 systems to STIG standards.

## Getting Started

SecureSDT is designed with a simple GUI and meant to be executed through the .exe file included in the package. Simply double click the .exe and select the options that you would like to apply to the system. 

### Prerequisites

1) Windows 10 or Windows 11 system
2) Admin privileges on system

### Installing

Copy entire package to system. The .exe will not install anything, it will only run the application.

## Built With

* [Windows PowerShell ISE](https://www.microsoft.com/en-us/) - Code editor
* [Windows Hyper-V](https://www.microsoft.com/en-us/) - VM test environment
* [Disa](https://www.disa.mil/) - Used to configure computer system with STIG standards
* [PS2EXE-GUI](https://gallery.technet.microsoft.com/scriptcenter/PS2EXE-GUI-Convert-e7cb69d5) - Used to convert .ps file to .exe file

## Authors

* **Gustavo Rayos** - *Initial work* - [gustavorayos.com](https://www.gustavorayos.com)

## Acknowledgments

* Hat tip to developers and posters on forums (Stack Overflow, Reddit, YouTube, etc)
* Inspiration

## Screenshots

User interface

![SecureSDT](https://github.com/gustavorayos/SecureSDT/assets/8792052/ec06ccfc-cd51-4513-acde-a8816331710f)

Before running SecureSDT SCAP score

![Windows-PreSTIG-SCAP](https://github.com/gustavorayos/SecureSDT/assets/8792052/1f8de440-72b9-40c2-941f-c780595e3048)

After running SecureSDT SCAP score

![Windows-PostSTIG-SCAP](https://github.com/gustavorayos/SecureSDT/assets/8792052/fa12b7c4-bdb6-4e19-ae08-4925a1afa7fa)

