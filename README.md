kernel_ZOPO
===========

ZOPO kernel source code

ZOPO has never released the kernel source of ZP980 and ZP990

this repo fork of https://github.com/PaoloW8/kernel_ZOPO



this kernel is compatible with ZOPO model: 980, 990, C3

to choose which model to compile you have to edit the file build.sh and change the variable MODEL (valid values are 990a, 990b, 980a, 980b, C3)

for the 980 and 990 there are variants that differ in the accelerometer sensor, try first with the A version...if the rotation of the screen (in landscape) is upside down recompile with B version

you also need to edit the path of toolchain


for compile:
./build.sh

for clean
./clean.sh

for create swapsd
./swap.sh