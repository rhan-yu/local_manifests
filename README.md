# Download Android source with local_manifests
 Refer to http://source.android.com/source/downloading.html

$ repo init -u https://android.googlesource.com/platform/manifest -b android-16.0.0_r3
$ git clone https://github.com/rhan-yu/local_manifests .repo/local_manifests -b arpi-16
$ repo sync

# Build for Raspberry Pi 5
 https://github.com/android-rpi/device_arpi_rpi5

Use -j[n] option on sync & build steps, if build host has a good number of CPU cores.
