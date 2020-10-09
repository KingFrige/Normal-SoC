Normal SoC
============

一般的、标准化的SoC设计策略与设计方向

topology - diplomacy
---------------------
- address map
- bus node
- bus protocol -> amba/tilelink
- performance evaluation


config - parameter
--------------------
- reuse
- gradient


clock tree
--------------
- internal generate
- div
- source select -> mux
- sdc


reset tree
--------------
- source
- sync clock
- order 


power domain
--------------
- dut group
- upf
- power evaluation


memory system
--------------
- cache node
- memory size
- memory topology -> location
- performance evaluation


regmapper
--------------
- register config input


gpio map
--------------
- pad share
- pin matrix


dma channel
------------
- connect
- reuse channel


interrupt connect
------------------
- connect
- map
- low power wake up


doc
--------------
- code <-> doc


syn flow
-----------------


fpga version
-----------------


testbench -> verification
--------------------------


software
-----------------


reference
------------
[rocket-chip](https://github.com/chipsalliance/rocket-chip)
[fusesoc](https://github.com/olofk/fusesoc)
[SoC-Gulp](https://github.com/KingFrige/SoC-Gulp)
[duh](https://github.com/sifive/duh)
[wake](https://github.com/sifive/wake)
[wit](https://github.com/sifive/wit)
[block-pio-sifive](https://github.com/sifive/block-pio-sifive)

