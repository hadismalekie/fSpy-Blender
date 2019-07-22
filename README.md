# What is this?

This is the official [fSpy](https://fspy.io) importer add-on for [Blender](https://blender.org). The two images below show an fSpy project (top) and a matching Blender camera created by the importer (bottom).

![An example fSpy project](readme_images/help_fspy.jpg)

![A matching Blender camera](readme_images/help_blender.jpg)

# Getting started

## 1. Download the add-on

Download the latest version from [the releases page](https://github.com/stuffmatic/fSpy-Blender/releases). Make sure you download the file called `fSpy-Blender-x.y.z.zip`.

### ⚠️ __Important note for mac users__ ⚠️

Safari seems to unzip downloaded zip archives automatically by default. Since the add-on must be installed as a zip file, you have to do one of the following

* Disable the auto-unzip behaviour and download the add-on again
* Manually re-archive the automatically unzipped folder and point Blender to this file when installing

## 2. Install the add-on

Open the preferences window by selecting Preferences from the Edit menu

![Edit -> Preferences](readme_images/help_edit_preferences.png)

Select the _Add-ons_ tab and press the _Install_ button

![Install add-on](readme_images/help_addons_install.png)

Select the downloaded zip-file and press _Install Add-on from file_

![Select the zip file](readme_images/help_select_zip.png)

Locate the fSpy importer in the add-on list and enable it by pressing the checkbox.

![Enable add-on](readme_images/help_enable_addon.png)

## 3. Import an fSpy project file

Once the add-on is installed and activated, fSpy project files can be imported by selecting _fSpy_ from the _Import_ menu. This will create a camera with the same name as the imported project file.

![Import menu](readme_images/help_import_menu.png)

### Import settings

At the bottom left in the importer's file browser, there is a panel with import settings.

![Import settings](readme_images/help_import_settings.png)

__Update existing import (if any)__ - If checked, any previously created camera with a name matching the project filename will be updated. If unchecked, a new camera will be created on each import. 

__Import background image__ - If checked, the image from the fSpy project file will be used as the background image for the Blender camera.
