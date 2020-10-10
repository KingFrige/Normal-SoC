Normal SoC
============

一般的、标准化的SoC设计策略与设计方向

以IP为中心的SoC设计，以IP为中心的testcase复用原则

topology - diplomacy
---------------------
- address map
- bus node
- bus protocol -> amba/tilelink
- performance evaluation
- Integration mode


config - parameter
--------------------
- reuse
- gradient
- parameter transfer


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
- chip IO
- test mode


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

- Architecture diagram
- address map info
- clock tree
- reset tree
- memory system
- dma channel
- gpio map info
- interrupt info


syn flow
-----------------
- sdc
- Power
- Area
- Perfomance


verification
--------------------------
- fm scripts
- testbench
- case demo
- coverage collection
- case reuse


software
-----------------
- dts
- register macro
- demo case
- General firmware layer


fpga version
-----------------
- xdc
- FPGA-IP

reference
------------
[rocket-chip](https://github.com/chipsalliance/rocket-chip)

[fusesoc](https://github.com/olofk/fusesoc)

[SoC-Gulp](https://github.com/KingFrige/SoC-Gulp)

[duh](https://github.com/sifive/duh)

[wake](https://github.com/sifive/wake)

[wit](https://github.com/sifive/wit)

[block-pio-sifive](https://github.com/sifive/block-pio-sifive)

[freedom-e-sdk](https://github.com/sifive/freedom-e-sdk)

[chipyard](https://github.com/ucb-bar/chipyard)


