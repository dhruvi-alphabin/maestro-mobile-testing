# Automation Task: Demo Application Tesitng
This is automation testing for the Demo application of `wdio` using Maestro mobile tesitng framework.

## Pre-Requisites
1. Install iTerm or Powershell in your system
2. Install android studio in your machine
3. Add ANDROID_HOME to your system environment variable.
    1. To check if your ANDOIRD_HOME setup is correctly done, open a terminal and run this command `adb --version`.
4. Install Java JDK 11 and set JAVA_HOME
    1. Run `java --version` to check if the java is installed correctly.

## Installation
To create test cases using Maestro for mobile testing, install the Maestro using bellow commands:
    1. Open the Terminal or iTerm
    2. Type the below commands for Installation of Maestro:
```
brew install Maestro
```
OR
```
curl -Ls "https://get.maestro.mobile.dev" | bash
```

## Upgrading the CLI
Run the installation script again to upgrade the Maestro of CLI
```
curl -Ls "https://get.maestro.mobile.dev" | bash
```

## Connecting to Your Device
Any local emulator or physically connected USB device will be instantly detected by `maestro test` and used.

## Execution
Follow the steps to execute our test case:
1. Navigate to the directory where you've created a test cases.
    ```
    cd maestro-automation
    ```
2. Execute our test cases using below command:
    ```
    maestro test main.yaml
    ```

## Uninstalling Maestro
If you want to uninstall Maestro then simply run the below command:
```
brew uninstall maestro
```
