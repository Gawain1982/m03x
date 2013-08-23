[M03x](http://www.meizu.com)
=================

M03x repo is kernel source code for Meizu M030, M031, M032 smartphone(MX). With MX drivers, you can compile a MX smartphone kernel by yourself. Enjoy it!

HOW TO COMPILE
-----------

###1. Download source code###

  <code>git clone git@github.com:meizuosc/m03x.git</code>

###2. Compiling###

  <code>make mx_defconfig</code>
  
  <code>make -j8 ARCH=arm CROSS_COMPILE=arm-linux-gnueabi-</code>

  Note:
  + Make sure you have arm cross tool chain, maybe you can download [here](http://www.linaro.org/downloads)
  + If you get a poor cpu in your compiling host, you should use "-j4" or lower instead of "-j8"

Get Help
--------

Checkout our community http://bbs.meizu.cn (in Chinese)