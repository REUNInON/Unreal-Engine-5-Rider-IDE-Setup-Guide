# Unreal Engine 5 - JetBrains Rider IDE Setup Guide Windows 11 (2025)

## Required Installations

- Unreal Engine 5
- JetBrains Rider IDE
- Visual Studio 2022
- .NET SDK 9 & .NET SDK 8 & .NET SDK 6

## Setup Steps

1. Install Unreal Engine 5 via [Epic Games](https://www.unrealengine.com/en-US/download)
2. Install Rider via [Jetbrains Toolbox](https://www.jetbrains.com/toolbox-app/) (Recommended) or from [JetBrains Website](https://www.jetbrains.com/rider/download/#section=windows).
3. Install .NET SDKs from [Microsoft](https://dotnet.microsoft.com/en-us/download)

### Visual Studio 2026 Installation (It is required for setup)

1. Install Visual Studio 2022 from [Microsoft](https://visualstudio.microsoft.com/downloads/). If you are unsure, go with the Community Edition.
2. Make sure to check these *workloads* before installation:
    - **Desktop development with C++**
    - **Game development with C++** In **Installation Details** make sure to mark **Unreal Engine installer**  

    *What to do if you missed workload installation step:*
    - Open **Visual Studio Installer** app. (It is installed alongside of VS 2026).
    - Click on *Modify* button, then you can select the *workloads* that you've missed.

### Last Steps

1. Restart your computer. (Important).
2. Create new project (selecting C++ as game scripting language instead of Blueprints is recommended)/ open your project.
3. Edit -> Editor Preferences -> General -> Live Coding -> Uncheck Live Coding -> General -> Source Code -> as Source Code Editor select Rider Uproject
4. You can close editor preferences. Then install **RiderLink** plugin as prompted from Rider. (Alternatively from UE5).
5. Now you can open Rider Uproject or create new C++ classes for your game.
