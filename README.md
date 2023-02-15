# HF filter bamk

KiCad files for a simple HF filter bank.

![screenshot](https://github.com/kazkojima/filterbank/blob/main/images/Figure_2.png)

There are 4 5-order Chebyshev bandpass filters for 0.5-2, 2-10, 10-28, 28-45MHz.
 [Actual characteristics](https://github.com/kazkojima/filterbank/blob/main/images/Figure_1.png) deviate slightly from target values.


A filter is selected with an analog demultiplexer/multiplexer TS3A5017PWR of which select inputs are drived with photo-isolators.
