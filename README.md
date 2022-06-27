## PYNQ Board Repository for the Zynq UltraScale+ RFSoC ZCU208
This repository contains source files and instructions for building PYNQ to run on the 
[ZCU208 board](https://www.xilinx.com/products/boards-and-kits/zcu208.html).

### ZCU208 Board Files

Clone this repo, download the ZCU208 petalinux BSP from [here](https://www.xilinx.com/support/download/index.html/content/xilinx/en/downloadNav/embedded-design-tools.html), and place it in the ZCU208 folder.

You can then build the image from the PYNQ repo's sdbuild folder with
```
make BOARDDIR=~/where/you/cloned/this/repo/to
```

### Support

Please ask questions on the <a href="https://discuss.pynq.io" target="_blank">PYNQ support forum</a>.

### Licenses

Please see the [LICENSE](LICENSE) file for how the repository and packages are licensed.
