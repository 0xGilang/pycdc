# Decompyle++ 
***A Python Byte-code Disassembler/Decompiler***

Decompyle++ aims to translate compiled Python byte-code back into valid
and human-readable Python source code. While other projects have achieved
this with varied success, Decompyle++ is unique in that it seeks to
support byte-code from any version of Python.

Decompyle++ includes both a byte-code disassembler (pycdas) and a 
decompiler (pycdc).

As the name implies, Decompyle++ is written in C++.
If you wish to contribute, please fork us on github at 
https://github.com/zrax/pycdc

## Building Decompyle++
* Generate a project or makefile with [CMake](http://www.cmake.org) (See CMake's documentation for details)
  * The following options can be passed to CMake to control debug features:

    | Option | Description |
    | --- | --- |
    | `-DCMAKE_BUILD_TYPE=Debug` | Produce debugging symbols |
    | `-DENABLE_BLOCK_DEBUG=ON` | Enable block debugging output |
    | `-DENABLE_STACK_DEBUG=ON` | Enable stack debugging output |

* Build the generated project or makefile
  * For projects (e.g. MSVC), open the generated project file and build it
  * For makefiles, just run `make`
  * To run tests (on \*nix or MSYS), run `make check`

## Usage
**To run pycdas**, the PYC Disassembler:
`./pycdas [PATH TO PYC FILE]`
The byte-code disassembly is printed to stdout.

**To run pycdc**, the PYC Decompiler: 
`./pycdc [PATH TO PYC FILE]`
The decompiled Python source is printed to stdout.
Any errors are printed to stderr.

## Authors, Licence, Credits
Decompyle++ is the work of Michael Hansen and Darryl Pogue.

Additional contributions from:
* charlietang98
* Najimi Ajimu
* Kunal Parmar
* Olivier Iffrig
* Zlodiy

It is released under the terms of the GNU General Public License, version 3;
See LICENSE file for details.

## **Install PYCDC On Termux**
```
$ chmod 777 pycdc.cpp
$ chmod 777 pycdas.cpp
$ ls
$ cmake .
$ make
$ ls
$ mv pycdc $PREFIX/bin
$ mv pycdas $PREFIX/bin
```
# **Contact Me🔥☕**
<p align="left">
<a href="https://www.github.com/Ruphas-Mafahl-XD"><img height="30" width="40" src="https://camo.githubusercontent.com/b079fe922f00c4b86f1b724fbc2e8141c468794ce8adbc9b7456e5e1ad09c622/68747470733a2f2f6564656e742e6769746875622e696f2f537570657254696e7949636f6e732f696d616765732f7376672f6769746875622e737667"></a>
<a href="https://fb.com/AryaTrickers2020" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="AryaTrickers2020" height="30" width="40" /></a>
<a href="https://instagram.com/mizari.rhein" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="mizari.rhein" height="30" width="40" /></a>
<a href="https://youtube.com/channel/UCzEhsJYu90gM5A8lmv1axYQ" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="UCzEhsJYu90gM5A8lmv1axYQ" height="30" width="40" /></a>
<a href="https://wa.me/6289694295787?text=Halo+Bang+Arya" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/whatsapp.svg" alt="6289694295787" height="30" width="40" /></a>
<a href="https://www.messenger.com/AryaTrickers2020"><img height="30" width="40" src="https://camo.githubusercontent.com/0b9b5efe8bd5edcdaec78496cf9ddaf6d98cd2b2574e23d5deca0b5e7eae583a/68747470733a2f2f6564656e742e6769746875622e696f2f537570657254696e7949636f6e732f696d616765732f7376672f6d657373656e6765722e737667"></a>

# **Donasi💎**
* Donasi saya  <a href="https://saweria.co/AryaAdinata">DISINI!</a>
, Atau saya akan menjamsut anda💀

------
------
