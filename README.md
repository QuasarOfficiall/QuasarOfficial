# QuasarOfficial
Quasar Build status Downloads License  Free, Thanks for using and supporting Quasar!
Quasar
Build status Downloads License

Free, Open-Source Remote Administration Tool for Windows

Quasar is a fast and light-weight remote administration tool coded in C#. The usage ranges from user support through day-to-day administrative work to employee monitoring. Providing high stability and an easy-to-use user interface, Quasar is the perfect remote administration solution for you.

Please check out the Getting Started guide.

Screenshots
remote-shell

remote-desktop

remote-files

Features
TCP network stream (IPv4 & IPv6 support)
Fast network serialization (Protocol Buffers)
Encrypted communication (TLS)
UPnP Support (automatic port forwarding)
Task Manager
File Manager
Startup Manager
Remote Desktop
Remote Shell
Remote Execution
System Information
Registry Editor
System Power Commands (Restart, Shutdown, Standby)
Keylogger (Unicode Support)
Reverse Proxy (SOCKS5)
Password Recovery (Common Browsers and FTP Clients)
... and many more!
Download
Latest stable release (recommended)
Latest development snapshot
Supported runtimes and operating systems
.NET Framework 4.5.2 or higher
Supported operating systems (32- and 64-bit)
Windows 11
Windows Server 2022
Windows 10
Windows Server 2019
Windows Server 2016
Windows 8/8.1
Windows Server 2012
Windows 7
Windows Server 2008 R2
For older systems please use Quasar version 1.3.0
Compiling
Open the project Quasar.sln in Visual Studio 2019+ with installed .NET desktop development features and restore the NuGET packages. Once all packages are installed the project can be compiled as usual by clicking Build at the top or by pressing F6. The resulting executables can be found in the Bin directory. See below which build configuration to choose from.

Building a client
Build configuration	Usage scenario	Description
Debug configuration	Testing	The pre-defined Settings.cs will be used, so edit this file before compiling the client. You can execute the client directly with the specified settings.
Release configuration	Production	Start Quasar.exe and use the client builder.
Contributing
See CONTRIBUTING.md

Roadmap
See ROADMAP.md

Documentation
See the wiki for usage instructions and other documentation.

License
Quasar is distributed under the MIT License.
Third-party licenses are located here.

Thank you!
I really appreciate all kinds of feedback and contributions. Thanks for using and supporting Quasar!
