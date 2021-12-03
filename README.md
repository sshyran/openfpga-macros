# OpenFPGA ready-to-use Macros

This repository provide the following GDS-ready eFPGA IPs using OpenFPGA prototyping tool.


## Available FPGA Macros

- `SOFA_CHD`: Skywater Opensource FPGA (SOFA) - Custom High-Density Design
    - Open-source 12x12 FPGA with adapted QuickLogic' soft-adder CLB architecture ([documentation](https://skywater-openfpga.readthedocs.io/en/latest/datasheet/sofa_chd/), [github](https://github.com/lnis-uofu/SOFA))
    - Designed with Skywater130nm PDK with HD standard cell library + Custom Transmission Gate Cells
    - Base K4 architecture from VPR with 60 vertical and horizontal channels
    - Fabricated with eFabless Open MPW shuttle program ([slot-039](https://foss-eda-tools.googlesource.com/third_party/shuttle/mpw-one/slot-039))

- `SOFA_HD`: Skywater Opensource FPGA (SOFA) - High-Density Design
    - Open-source 12x12 FPGA ([documentation](https://skywater-openfpga.readthedocs.io/en/latest/datasheet/sofa_hd/), [github](https://github.com/lnis-uofu/SOFA))
    - Designed with Skywater130nm PDK with HD standard cell library
    - Base K4 architecture from VPR with 40 vertical and horizontal channels
    - No adders (carry-chain) or flipflop reset pins
    - Fabricated with eFabless Open MPW shuttle program ([slot-017](https://foss-eda-tools.googlesource.com/third_party/shuttle/mpw-one/slot-017))

- `SOFA_QLHD`: Skywater Opensource FPGA (SOFA) - QuickLogic' soft-adder High-Density Design
    - Opensource 12x12 FPGA with adapted QuickLogic' soft-adder CLB architecture ([documentation](https://skywater-openfpga.readthedocs.io/en/latest/datasheet/qlsofa_hd/), [github](https://github.com/lnis-uofu/SOFA))
    - Designed with Skywater130nm PDK with HD standard cell library
    - Base K4 architecture from VPR with 60 vertical and horizontal channels
    - Fabricated with eFabless Open MPW shuttle program ([slot-036](https://foss-eda-tools.googlesource.com/third_party/shuttle/mpw-one/slot-036))

