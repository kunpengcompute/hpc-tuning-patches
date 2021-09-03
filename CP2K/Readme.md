# CP2K

## Description 

CP2K is a quantum chemistry and solid state physics software package that can perform atomistic simulations of solid state, liquid, molecular, periodic, material, crystal, and biological systems. See [CP2K Home](https://www.cp2k.org/) for details.

The current code repository is a series of patches and scripts for performance optimization of CP2K v7.1 on Kunpeng chips.

## Software Stack Used

Compiler: the GNU Compiler Collection, see [GCC Home](http://www.gnu.org/software/gcc).

### Install Patches

```
cp 0001-support-aarch64.patch 0002-support-aarch64-with-optimization.patch ${CP2K_HOME}
cd ${CP2K_HOME}
git am 0001-support-aarch64.patch
git am 0002-support-aarch64-with-optimization.patch
```
