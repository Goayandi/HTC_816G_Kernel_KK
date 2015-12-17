QUMO QUEST 510 or CUBOT X6
===============

Build Command

kernel:

cd q510_qumo
./mk -o=TARGET_BUILD_VARIANT=user q510_qumo n k

Then, to create the boot.img:

./pack_bootimage.sh


lk.bin:

./mk -o=TARGET_BUILD_VARIANT=user q510_qumo n lk
