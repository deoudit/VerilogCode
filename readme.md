# Commands to compile file.v and file_test.v
# iverilog -o mysim file.v file_test.v
# Then run the mysim by using vvp (vvp mysim) in cmdline.
# If we have dumpfile in test module, then as we do vvp mysim then dump will be created with extension .vcd
# We can then run the gtkwave with (gtkwave dumpfile.vcd)
  