# Developing in .NET MAUI

## Installation

[Youtube Video showing how to configure Visual Studio Code for .NET Maui development](https://www.youtube.com/watch?v=1t2zzoW4D98)

[Microsoft .NET Maui installation instructions](https://learn.microsoft.com/en-us/dotnet/maui/get-started/installation?view=net-maui-9.0&viewFallbackFrom=net-maui-8.0&tabs=visual-studio-code#iosxcode-setup)

1. Download .NET Core installer
2. Download Android Studio and run the default install.  Don't install Microsoft OpenJDK from the command line.
3. [Download & Install Visual Studio Code](https://code.visualstudio.com/)
4. Add the .NET Maui Extension to Visual Studio Code
5. Add all the maui* Dotnet workflows
    1. dotnet workflow install maui
    2. dotnet workflow install maui-android
    3. dotnet workflow install maui-desktop
    4. dotnet workflow isntall maui-ios
    5. dotnet workflow install maui-maccatalyst
6. Configure XCode
    1. Download and install the latest XCode
    2. Make sure you run Xcode, agree to agreements, etc.
    3. Download Simulators in Xcode
    4. Install the XCode command line tools
        1. xcode-select --install
    
