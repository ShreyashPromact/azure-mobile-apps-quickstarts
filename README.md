# QuickStarts for Microsoft Azure Mobile Apps
 
With Microsoft Azure Mobile Apps you can add a scalable backend to your connected client applications in minutes.
To learn more, visit our [Developer Center](http://azure.microsoft.com/en-us/develop/mobile/).

## Getting Started

If you are new to Mobile Apps, you can get started by following our tutorials for connecting your Mobile
Apps cloud backend to [Windows Store apps](https://azure.microsoft.com/en-us/documentation/articles/app-service-mobile-windows-store-dotnet-get-started/),
[iOS apps](https://azure.microsoft.com/en-us/documentation/articles/app-service-mobile-ios-get-started/),
and [Android apps](https://azure.microsoft.com/en-us/documentation/articles/app-service-mobile-android-get-started/).  Tutorials are also available for Xamarin 
[Android](https://azure.microsoft.com/en-us/documentation/articles/app-service-mobile-xamarin-android-get-started/), 
[iOS](https://azure.microsoft.com/en-us/documentation/articles/app-service-mobile-xamarin-ios-get-started/), and 
[Forms](https://azure.microsoft.com/en-us/documentation/articles/app-service-mobile-xamarin-forms-get-started/) apps.

## Download Source Code

To get the source code of our SDKs and samples via **git** just type:

    git clone https://github.com/Azure/azure-mobile-apps-quickstarts.git
    cd ./azure-mobile-apps-quickstarts/
 
## Building Quickstarts

From the command line, run 

    C:\Windows\Microsoft.NET\Framework\v4.0.30319\MSBuild.exe .\Microsoft.WindowsAzure.Mobile.Build.msbuild

The build script downloads latest official nuget packages, updates quickstarts with required versions and dependencies, and packs required projects to appropriate quickstarts.

### Prerequisites

.Net Framework 4.0.