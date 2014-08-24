:data-transition-duration: 2000
:skip-help: true
:css: presentation.css
:data-scale: 5

.. title: Toolchain for ARM Embedded System

----

Toolchain for ARM Embedded System
=================================

.. note::

    Update from the last debconf "Embedded ARM development in Debian", try to
    summarize the story from october 2013 to now

----

Embedded System
===============

* Without an OS
* You need to handle the hardware resources or you will be very close

----

Cortex-A/R/M
============

* Cortex-A (Application use), instruction set ARMv7-A 
* Cortex-R (Real-time use), instruction set ARMv7-R
* Cortex-M (Microcontroller use), instruction set (ARMv6-M, ARMv7-M, ARMv7E-M)

----

What do we have in debian today?
================================

* A gcc built using gcc-4.8-source debian package (with some patches to support
  this achitectures)
* Everything is in /usr/lib/arm-none-eabi

----

What do we have in debian today?
================================

* It is possible to have multiple standard c libraries and standard c++
  libraries.
* Multiple instruction sets (v6-m, v7-m, v7e-m, v7-ar)
  * Also with fpu or without fpu (softfpu)

----

What do we have in debian today?
================================

* Two firmware uploaders (lpc21isp, lm4tools)
* Working with upstream to get ready newlib-nano

----

What did not tried
==================

* Specs files

.. note::
    The current approach let us focus on to have a good toolchain for embedded
    system. And keep the packaging really simple.

----

We need help
============

* Documentation
* More documentation
* Upload others standard C and C++ libraries

.. note::
    Howto start a project from scratch

----

Questions?
==========

----

More Questions?
===============

----

Last chance
===========

----

End
===

Thank you!
