# 010101100110110101000110011101010101100100110010010101100110101101001001010001010011000101101000011000100110110101000110011011100101101001
<div>

[![Github All Releases](https://img.shields.io/github/downloads/KhanhNguyen9872/0101011101010111001110010011000101100100010010000101011001101001010110100101011000111001010101110101/total.svg?style=for-the-badge)](https://github.com/KhanhNguyen9872/0101011101010111001110010011000101100100010010000101011001101001010110100101011000111001010101110101/releases/latest) [![Github All Releases](https://img.shields.io/github/release/KhanhNguyen9872/0101011101010111001110010011000101100100010010000101011001101001010110100101011000111001010101110101.svg?style=for-the-badge)](https://github.com/KhanhNguyen9872/0101011101010111001110010011000101100100010010000101011001101001010110100101011000111001010101110101/releases/latest)

</div>

## Introduction

Hi, when we released, people were upset because it used the .apks format, which was burdensome to install than a traditional .apk file. Even though we wrote clear instructions on how to install the new Vanced build, people still couldn't figure it out.  

Then we thought, "why don't we make a manager for vanced, which will download, update and uninstall Vanced and MicroG, have an easy and user-friendly UI and be less than 10mb?" and that's how Vanced Manager was born.  

## Features

- Vanced manager can easily install and uninstall Vanced and MicroG.
- It has various settings for customization and better experience. 
- The Manager comes with an easy-to-use Interface.  

</br>

<div class="note">
  <p><strong>NOTE: </strong>Background download/installation feature is no longer supported due to problems with some ROMs, please <b>DO NOT</b> report issues regarding background activity.</p>
</div>

<!-- ##### Background download/installation feature is no longer supported due to problems with some ROMs, please do NOT report issues regarding background activity. -->

## Contributions
Pull Requests should be made to the [Dev](https://github.com/YTVanced/VancedManager) Branch as that is the working branch, master is for Release code only.

For anyone who wants to provide translations please submit them to this [link](https://crowdin.com/project/vanced-manager) as we also use it for YouTube Vanced. Any issues with translations should be posted there too.

## TODO
- [ ] Clean up the ViewModel and DataModel code
- [ ] Migrate to Jetpack Compose when it's officially released

## Building

<div>

</div>

## Using Android Studio
Clone the Repository, open it in Android Studio and build the application.

## Google Advanced Protection Program
If you are using this feature on your Google account, you must either disable it or log out from your Google account before installing Youtube Vanced via Vanced Manager.
The Google Advanced Protection Program does not allow the installation of apps from unknown sources. These security measures are tied to the protected account and not the device. After the installation, you will be able to log back in or enroll again into the program.

## Using Command Line
#### On Windows:
```powershell
.\gradlew.bat assembleDebug
```
#### On Linux/macOS:
```bash
chmod +x gradlew
./gradlew assembleDebug
```

