# Granular sampler for Daisy (STR-500)
This is a granular sampling system that runs on a Daisy Seed microcontroller.

Written in Pure Data. The easiest way to get it running on a Seed is to use PlugData for compiling. I use the "Huge + SDRAM" QSPI setting in the compiler to allow for the relatively long sampling time.

This granular patch is essentially the same as the ys.granular system also available here on my github: https://github.com/yannseznec/ys.granular
The main difference is that this version does not use the [clone] object, which is not supported by the Heavy compiler required by the Daisy Seed. There are probably a few other similar changes that I can't remember right now.

This patch is particularly designed for use with a Gametrak string controller, resulting in a gestural sampling machine that I call the STR-500. More details on that coming at some point, you can see videos of it on my instagram if you like: https://www.instagram.com/p/DPdloWzjOOb/