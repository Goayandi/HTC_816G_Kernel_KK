HTC 816G
===============

Build Command

kernel:

cd htc_816g
./mk -o=TARGET_BUILD_VARIANT=user htc_816g n k

Then, to create the boot.img:

./pack_bootimage.sh


lk.bin:

./mk -o=TARGET_BUILD_VARIANT=user htc_816g n lk
