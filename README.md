# ShirayukiProject

 Getting Started
---------------
To get started with the ShirayukiProject sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

To initialize your local repository, use command:

```bash
repo init -u https://github.com/ShirayukiProject-Brokenlab/android_manifest.git -b tsunemori-13
```

Or, if you want to save your space and time:

```bash
repo init -u https://github.com/ShirayukiProject-Brokenlab/android_manifest.git -b tsunemori-13 --depth=1
```

Then sync up:

```bash
repo sync
```

Building the System
-------------------
 Initialize the ROM environment with the envsetup.sh script.

```bash
. build/envsetup.sh
```

Lunch your device after cloning all device sources if needed.

```bash
lunch yuki_devicecodename-buildtype
```

Start compilation

```bash
m otapackage
```

OR

```bash
m bacon
```

---------------------------------------------------------------------------------------------------------------------

[ShirayukiProject Telegram Channel](https://t.me/shirayukiproject) | [ShirayukiProject Telegram Group](https://t.me/shirayukiproject_chat)

---------------------------------------------------------------------------------------------------------------------
