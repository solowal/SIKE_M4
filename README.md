# SIKE_M4
Copyright (c) Hwajeong Seo, Amir Jalali, and Reza Azarderakhsh

Cryptology ePrint URL: https://eprint.iacr.org/2020/410

Lightweight Implementation of SIKE Round 2 on ARM Cortex-M4

- SIKE_M4.tar.gz: pqm4 testbench package
$ make
$ ./monitor.sh &
$ ./st-flash write ./bin/crypto_kem_sikep434_m4_speed.bin 0x8000000
