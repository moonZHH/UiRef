# APP UI Layout Snapshot

These are three eclipse projects.

UiRef is the main project and it depends on the soot framework.

The functionality of this project is to dynamically retrieve the UI layout of a running app.

To use the project, you just need to import the three eclipse projects into the eclipse IDE.

In the MainImpl.java, you need to explicitly change the values of the "apkRootDirectoryPath" variable.

Before running the project, you need to launch a Android emulator.

The configuration for the emulator is presented as follow.
Name: 200inch_API_23
CPU/ABI: Google APIs Intel Atom (x86)
Target: google_apis [Google APIs] (API level 23)
Skin: 2160x4096
hw.dPad: no
hw.lcd.height: 4096
runtime.network.speed: full
hw.accelerometer: yes
hw.device.name: 200inch
vm.heapSize: 256
skin.dynamic: yes
hw.device.manufacturer: User
hw.lcd.width: 2160
hw.gps: yes
hw.initialOrientation: Portrait
skin.path.backup: _no_skin
image.androidVersion.api: 23
hw.audioInput: yes
image.sysdir.1: system-images/android-23/google_apis/x86/
tag.id: google_apis
showDeviceFrame: no
hw.camera.back: emulated
hw.mainKeys: yes
AvdId: 200inch_API_23
hw.camera.front: emulated
hw.lcd.density: 120
avd.ini.displayname: 200inch API 23
hw.gpu.mode: auto
hw.ramSize: 2048
hw.trackBall: no
PlayStore.enabled: false
hw.battery: yes
hw.cpu.ncore: 1
hw.sdCard: no
tag.display: Google APIs
runtime.network.latency: none
hw.keyboard: yes
hw.sensors.proximity: yes
disk.dataPartition.size: 1G
hw.sensors.orientation: yes
avd.ini.encoding: UTF-8
hw.gpu.enabled: yes
