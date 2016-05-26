# AOSP 5.1 for HTC Butterfly (dlxub1) devices
Local manifest needed to build AOSP for the HTC Butterfly (dlxub1) phone.

Instructions: (TODO)

1. repo init -u https://android.googlesource.com/platform/manifest -b android-5.0.2_r3
2. repo sync
2. cd .repo
3. git clone https://github.com/coolshou/local_manifests_dlxub1.git local_manifests
4. cd ..
5. repo sync
6. cd kernel
7. git submodule init
8. git submodule update
9. cd ..


Now start normal build procress 



