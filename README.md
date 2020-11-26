# skarab_bsp_images
Firmware images for the SKARAB board

Golden image
------------
skarab_fgbe_1gbe_XXXX-XX-XX_XXXX_golden.*, XXXX-XX-XX_XXXX = timestamp \
*.hex = HEX flash programming file for casperfpga's virtex_flash_reconfig() function \
*.bin = Binary programming file for casperfpga's upload_to_ram_and_program() function \
*.mcs = HEX flash programming file via JTAG (for board recovery only) \
*.prm = ASCII file containing memory map of the output MCS file (used with *.mcs file only)

Multiboot image
---------------
skarab_fgbe_1gbe_XXXX-XX-XX_XXXX_multiboot.*, XXXX-XX-XX_XXXX = timestamp \
*.hex = HEX flash programming file for casperfpga's virtex_flash_reconfig() function \
*.bin = Binary programming file for casperfpga's upload_to_ram_and_program() function \
*.mcs = HEX flash programming file via JTAG (for board recovery only) \
*.prm = ASCII file containing memory map of the output MCS file (used with *.mcs file only)

Spartan image
-------------
frm123701u2r1.ufp \
*.ufp = SPARTAN configuration flash programming file for casperfpga's spartan_flash_reconfig() function

Recovery image
--------------
top.bit \
*.bit = Xilinx Vivado bit file - can be used via JTAG to recover board if all else fails or casperfpga's upload_to_ram_and_program() function 
