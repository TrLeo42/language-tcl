# language-tcl package

This package provides syntax highlighting in atom.io for the Tcl programming language. It was created from the TextMate bundle.
[oscimpDigital](https://github.com/oscimp/oscimpDigital)'s keywords for Vivado programmation through tcl scripts have been added :
 - add_ip_and_conf: adds an IP and configures parameters, using only the OscimpDigital name and no need to provide the Xilinx VLNV – Vendor, Library, Name, and Version – identifier
 -  connect_proc: connect to AXI bus. The argument is the least significant byte with respect to the 0x43C0000 base address (start at 0x00000 and increment by 0x10000 for each new block to be consistent with Vivado’s allocation of 64 KB blocks for each IP),
 -  connect_proc_clk: connect the clock to the PS clock
 -  connect_proc_rst: connect the reset to the PS reset
 -  connect_intf: connects interface to interface or signal to signal
 -  connect_to_fpga_pins: same as Make external
