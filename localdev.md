= Option 1 Local Command line =
*Cygwin
*Local dev reuses existing Linux VMs or container hosting for sandbox development

= Option 2 Windows Subsystem for Linux (WSL) =

*Install WSL
**Summary of instructions from https://dev.to/mattetti/setting-up-a-windows-linux-dev-env-2oi
    Launch PowerShell as Administrator (click the start menu, type PowerShell, expand the options and pick run as Administrator).
    Type dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
    Type dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
    Restart your machine manually
    Install flavour of Linux from Microsoft Store
    Launch the flavour and configure it
