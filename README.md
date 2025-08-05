iverilog -o btog_sim.out  btog_tb.v btog.v
vvp btog_sim.out
gtkwave btog.vcd
