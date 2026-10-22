# TREE full benchmark report

- Per-case hard timeout: **1800 seconds**
- Workers: **12**
- Discovered: **454**
- Completed: **454**
- Success: **311**
- Fail: **123**
- Timeout: **20**

| # | Suite | Case | Status | Wall time (s) | Reason |
|---:|---|---|---|---:|---|
| 1 | lfr | `CIDAR_Lab_Past_Devices/Chemostat_Chip/Chemostat_Chip_fromLFR.json` | fail | 0.276 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=36, E=50, components=1, cycle_rank=15; cycle-closing connection(s): channel_22, channel_29, channel_30, channel_31, channel_32, channel_33, channel_34, channel_43, channel_44, channel_45, channel_46, channel_47, channel_48, channel_49, channel_50 |
| 2 | lfr | `CIDAR_Lab_Past_Devices/Dna_Synthesizer/Dna_Synthesizer_fromLFR.json` | fail | 0.270 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=65, E=74, components=1, cycle_rank=10; cycle-closing connection(s): channel_60, channel_64, channel_67, channel_68, channel_69, channel_70, channel_71, channel_72, channel_73, channel_74 |
| 3 | lfr | `CIDAR_Lab_Past_Devices/Dual_Lane_Droplet/Dual_Lane_Droplet_fromLFR.json` | success | 1.739 |  |
| 4 | lfr | `CIDAR_Lab_Past_Devices/Genetic_Clock_Testing_Tool/Genetic_Clock_Testing_Tool_fromLFR.json` | fail | 0.230 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=9, E=10, components=1, cycle_rank=2; cycle-closing connection(s): channel_9, channel_10 |
| 5 | lfr | `CIDAR_Lab_Past_Devices/Glycoform/Glycoform_fromLFR.json` | success | 1.384 |  |
| 6 | lfr | `CIDAR_Lab_Past_Devices/Grad_Cells/Grad_Cells_fromLFR.json` | fail | 0.231 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=9, E=12, components=1, cycle_rank=4; cycle-closing connection(s): channel_4, channel_6, channel_8, channel_12 |
| 7 | lfr | `CIDAR_Lab_Past_Devices/Gradient/Gradient_fromLFR.json` | fail | 0.274 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=48, E=57, components=1, cycle_rank=10; cycle-closing connection(s): channel_40, channel_42, channel_44, channel_46, channel_50, channel_52, channel_53, channel_54, channel_55, channel_56 |
| 8 | lfr | `CIDAR_Lab_Past_Devices/Hasty_Cell_Traps/Hasty_Cell_Traps_fromLFR.json` | fail | 0.274 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=6, E=8, components=1, cycle_rank=3; cycle-closing connection(s): channel_4, channel_6, channel_8 |
| 9 | lfr | `CIDAR_Lab_Past_Devices/Hmlp_Dual_Bank/Hmlp_Dual_Bank_fromLFR.json` | fail | 0.266 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=43, E=63, components=1, cycle_rank=21; cycle-closing connection(s): channel_36, channel_38, channel_40, channel_41, channel_42, channel_45, channel_46, channel_47, channel_48, channel_50, channel_51, channel_53, channel_54, channel_55, channel_56, channel_57, channel_58, channel_59, channel_60, channel_62, channel_63 |
| 10 | lfr | `CIDAR_Lab_Past_Devices/Incubator/Incubator_fromLFR.json` | fail | 0.268 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=22, E=26, components=1, cycle_rank=5; cycle-closing connection(s): channel_20, channel_21, channel_24, channel_25, channel_26 |
| 11 | lfr | `CIDAR_Lab_Past_Devices/Inlet_16/Inlet_16_fromLFR.json` | fail | 0.269 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=57, E=73, components=1, cycle_rank=17; cycle-closing connection(s): channel_49, channel_50, channel_51, channel_54, channel_57, channel_61, channel_62, channel_64, channel_65, channel_66, channel_67, channel_68, channel_69, channel_70, channel_71, channel_72, channel_73 |
| 12 | lfr | `CIDAR_Lab_Past_Devices/Kinetics/Kinetics_fromLFR.json` | success | 1.173 |  |
| 13 | lfr | `CIDAR_Lab_Past_Devices/Logic_04/Logic_04_fromLFR.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=31, E=45, components=1, cycle_rank=15; cycle-closing connection(s): channel_21, channel_22, channel_23, channel_26, channel_29, channel_30, channel_31, channel_32, channel_33, channel_34, channel_38, channel_39, channel_40, channel_41, channel_44 |
| 14 | lfr | `CIDAR_Lab_Past_Devices/Mfd_005_Chip/Mfd_005_Chip_fromLFR.json` | success | 1.218 |  |
| 15 | lfr | `CIDAR_Lab_Past_Devices/Microalgal_Bioassay/Microalgal_Bioassay_fromLFR.json` | fail | 0.116 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=11, E=14, components=1, cycle_rank=4; cycle-closing connection(s): channel_9, channel_10, channel_11, channel_12 |
| 16 | lfr | `CIDAR_Lab_Past_Devices/Microdroplet/Microdroplet_fromLFR.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=22, E=27, components=1, cycle_rank=6; cycle-closing connection(s): channel_19, channel_21, channel_22, channel_25, channel_26, channel_27 |
| 17 | lfr | `CIDAR_Lab_Past_Devices/Microreactor/Microreactor_fromLFR.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=8, E=10, components=1, cycle_rank=3; cycle-closing connection(s): channel_7, channel_8, channel_10 |
| 18 | lfr | `CIDAR_Lab_Past_Devices/Mix_Incubate_Express/Mix_Incubate_Express_fromLFR.json` | success | 1.120 |  |
| 19 | lfr | `CIDAR_Lab_Past_Devices/Multi_Input/Multi_Input_fromLFR.json` | fail | 0.217 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=17, E=22, components=1, cycle_rank=6; cycle-closing connection(s): channel_14, channel_15, channel_19, channel_20, channel_21, channel_22 |
| 20 | lfr | `CIDAR_Lab_Past_Devices/MUX_96_Chambers/MUX_96_Chambers_fromLFR.json` | fail | 0.217 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=146, E=240, components=1, cycle_rank=95; cycle-closing connection(s): channel_52, channel_54, channel_56, channel_58, channel_60, channel_62, channel_64, channel_66, channel_68, channel_70, channel_72, channel_74, channel_76, channel_78, channel_80, channel_82, channel_84, channel_86, channel_88, channel_90, channel_92, channel_94, channel_96, channel_98, channel_100, channel_102, channel_104, channel_106, channel_108, channel_110, channel_112, channel_114, channel_116, channel_118, channel_120, channel_122, channel_124, channel_126, channel_128, channel_130, channel_132, channel_134, channel_136, channel_138, channel_140, channel_142, channel_144, channel_146, channel_148, channel_150, channel_152, channel_154, channel_156, channel_158, channel_160, channel_162, channel_164, channel_166, channel_168, channel_170, channel_172, channel_174, channel_176, channel_178, channel_210, channel_211, channel_212, channel_213, channel_214, channel_215, channel_216, channel_217, channel_218, channel_219, channel_220, channel_221, channel_222, channel_223, channel_224, channel_225, channel_226, channel_227, channel_228, channel_229, channel_230, channel_231, channel_232, channel_233, channel_234, channel_235, channel_236, channel_237, channel_238, channel_239, channel_240 |
| 21 | lfr | `CIDAR_Lab_Past_Devices/Net_MUX/Net_MUX_fromLFR.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=32, E=50, components=1, cycle_rank=19; cycle-closing connection(s): channel_15, channel_18, channel_20, channel_21, channel_25, channel_26, channel_27, channel_28, channel_30, channel_31, channel_34, channel_37, channel_40, channel_41, channel_42, channel_43, channel_45, channel_47, channel_49 |
| 22 | lfr | `CIDAR_Lab_Past_Devices/Nine_To_One_MUX/Nine_To_One_MUX_fromLFR.json` | fail | 0.165 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=28, E=35, components=1, cycle_rank=8; cycle-closing connection(s): channel_25, channel_27, channel_29, channel_31, channel_32, channel_33, channel_34, channel_35 |
| 23 | lfr | `CIDAR_Lab_Past_Devices/Number_Declarations/Number_Declarations_fromLFR.json` | success | 0.919 |  |
| 24 | lfr | `CIDAR_Lab_Past_Devices/Olfactory/Olfactory_fromLFR.json` | fail | 0.165 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=13, E=16, components=1, cycle_rank=4; cycle-closing connection(s): channel_12, channel_14, channel_15, channel_16 |
| 25 | lfr | `CIDAR_Lab_Past_Devices/Pump_Passthrough/Pump_Passthrough_fromLFR.json` | success | 0.718 |  |
| 26 | lfr | `CIDAR_Lab_Past_Devices/Ring/Ring_fromLFR.json` | success | 0.969 |  |
| 27 | lfr | `CIDAR_Lab_Past_Devices/Root_Chip/Root_Chip_fromLFR.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=22, E=23, components=1, cycle_rank=2; cycle-closing connection(s): channel_22, channel_23 |
| 28 | lfr | `CIDAR_Lab_Past_Devices/Rotary_16/Rotary_16_fromLFR.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=63, E=93, components=1, cycle_rank=31; cycle-closing connection(s): channel_34, channel_35, channel_36, channel_37, channel_38, channel_39, channel_52, channel_53, channel_55, channel_56, channel_57, channel_58, channel_59, channel_60, channel_70, channel_73, channel_74, channel_75, channel_77, channel_78, channel_81, channel_82, channel_84, channel_85, channel_86, channel_87, channel_88, channel_89, channel_90, channel_91, channel_93 |
| 29 | lfr | `CIDAR_Lab_Past_Devices/Rotary_Cells/Rotary_Cells_fromLFR.json` | fail | 0.115 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=15, E=20, components=1, cycle_rank=6; cycle-closing connection(s): channel_4, channel_6, channel_8, channel_18, channel_19, channel_20 |
| 30 | lfr | `CIDAR_Lab_Past_Devices/Seeding/Seeding_fromLFR.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=23, E=38, components=1, cycle_rank=16; cycle-closing connection(s): channel_4, channel_6, channel_8, channel_10, channel_14, channel_16, channel_18, channel_20, channel_22, channel_29, channel_30, channel_31, channel_32, channel_33, channel_37, channel_38 |
| 31 | lfr | `CIDAR_Lab_Past_Devices/Three_Reagent_Mix/Three_Reagent_Mix_fromLFR.json` | fail | 0.165 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=9, E=10, components=1, cycle_rank=2; cycle-closing connection(s): channel_9, channel_10 |
| 32 | lfr | `COVID/Aj_Rtpcr_8_Primer/Aj_Rtpcr_8_Primer_fromLFR.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=38, E=48, components=1, cycle_rank=11; cycle-closing connection(s): channel_21, channel_28, channel_31, channel_35, channel_36, channel_38, channel_43, channel_44, channel_45, channel_47, channel_48 |
| 33 | lfr | `COVID/Arize/Arize_fromLFR.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=39, E=44, components=1, cycle_rank=6; cycle-closing connection(s): channel_22, channel_23, channel_32, channel_36, channel_37, channel_38 |
| 34 | lfr | `COVID/Covid_Crispr/Covid_Crispr_fromLFR.json` | success | 0.920 |  |
| 35 | lfr | `COVID/Crispr/Crispr_fromLFR.json` | success | 1.220 |  |
| 36 | lfr | `COVID/Detectr/Detectr_fromLFR.json` | success | 1.470 |  |
| 37 | lfr | `COVID/Elisa/Elisa_fromLFR.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=8, E=8, components=1, cycle_rank=1; cycle-closing connection(s): channel_8 |
| 38 | lfr | `COVID/Gel_Electrophoresis/Gel_Electrophoresis_fromLFR.json` | fail | 0.165 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=12, E=14, components=1, cycle_rank=3; cycle-closing connection(s): channel_9, channel_12, channel_13 |
| 39 | lfr | `COVID/Hybri_Detect/Hybri_Detect_fromLFR.json` | success | 1.119 |  |
| 40 | lfr | `COVID/Part_1_Rna_Prep/Part_1_Rna_Prep_fromLFR.json` | success | 1.170 |  |
| 41 | lfr | `COVID/Part_2_Rt_Step/Part_2_Rt_Step_fromLFR.json` | success | 1.171 |  |
| 42 | lfr | `COVID/Part_3_Gel/Part_3_Gel_fromLFR.json` | success | 1.221 |  |
| 43 | lfr | `COVID/Rt_Pcr/Rt_Pcr_fromLFR.json` | success | 0.972 |  |
| 44 | lfr | `Distribute_Expressions/And_Annotation_Test/And_Annotation_Test_fromLFR.json` | success | 3.380 |  |
| 45 | lfr | `Distribute_Expressions/Dist_Expression_1/Dist_Expression_1_fromLFR.json` | success | 0.920 |  |
| 46 | lfr | `Distribute_Expressions/Dist_Expression_2/Dist_Expression_2_fromLFR.json` | success | 1.020 |  |
| 47 | lfr | `Distribute_Expressions/Dist_Expression_3/Dist_Expression_3_fromLFR.json` | success | 0.919 |  |
| 48 | lfr | `Distribute_Library/Cell_Traps_4/Cell_Traps_4_fromLFR.json` | success | 0.871 |  |
| 49 | lfr | `Distribute_Library/Hv_Storage_Grid_04/Hv_Storage_Grid_04_fromLFR.json` | success | 0.919 |  |
| 50 | lfr | `Distribute_Library/Hv_Storage_Grid_08/Hv_Storage_Grid_08_fromLFR.json` | success | 0.971 |  |
| 51 | lfr | `Distribute_Library/Hv_Storage_Grid_16/Hv_Storage_Grid_16_fromLFR.json` | success | 0.917 |  |
| 52 | lfr | `Distribute_Library/Hv_Storage_Grid_32/Hv_Storage_Grid_32_fromLFR.json` | success | 0.925 |  |
| 53 | lfr | `Distribute_Library/Hv_Storage_Grid_64/Hv_Storage_Grid_64_fromLFR.json` | success | 0.972 |  |
| 54 | lfr | `Distribute_Library/MUX_02_In/MUX_02_In_fromLFR.json` | success | 1.421 |  |
| 55 | lfr | `Distribute_Library/MUX_02_Out/MUX_02_Out_fromLFR.json` | success | 1.424 |  |
| 56 | lfr | `Distribute_Library/MUX_04_In/MUX_04_In_fromLFR.json` | success | 10.548 |  |
| 57 | lfr | `Distribute_Library/MUX_04_Out/MUX_04_Out_fromLFR.json` | success | 7.039 |  |
| 58 | lfr | `Distribute_Library/MUX_08_In/MUX_08_In_fromLFR.json` | timeout | 1800.018 | exceeded 1800s |
| 59 | lfr | `Distribute_Library/MUX_08_Out/MUX_08_Out_fromLFR.json` | timeout | 1800.019 | exceeded 1800s |
| 60 | lfr | `Distribute_Library/MUX_16_In/MUX_16_In_fromLFR.json` | timeout | 1800.017 | exceeded 1800s |
| 61 | lfr | `Distribute_Library/MUX_16_Out/MUX_16_Out_fromLFR.json` | timeout | 1800.019 | exceeded 1800s |
| 62 | lfr | `Distribute_Library/MUX_32_In/MUX_32_In_fromLFR.json` | timeout | 1800.021 | exceeded 1800s |
| 63 | lfr | `Distribute_Library/MUX_32_Out/MUX_32_Out_fromLFR.json` | timeout | 1800.017 | exceeded 1800s |
| 64 | lfr | `Distribute_Library/MUX_64_In/MUX_64_In_fromLFR.json` | timeout | 1800.017 | exceeded 1800s |
| 65 | lfr | `Distribute_Library/MUX_64_Out/MUX_64_Out_fromLFR.json` | timeout | 1800.019 | exceeded 1800s |
| 66 | lfr | `Distribute_Library/Single_Storage_Grid_01/Single_Storage_Grid_01_fromLFR.json` | success | 0.870 |  |
| 67 | lfr | `Distribute_Library/Single_Storage_Grid_02/Single_Storage_Grid_02_fromLFR.json` | success | 0.868 |  |
| 68 | lfr | `Distribute_Library/Single_Storage_Grid_04/Single_Storage_Grid_04_fromLFR.json` | success | 0.868 |  |
| 69 | lfr | `Distribute_Library/Single_Storage_Grid_08/Single_Storage_Grid_08_fromLFR.json` | success | 0.869 |  |
| 70 | lfr | `Distribute_Library/Single_Storage_Grid_16/Single_Storage_Grid_16_fromLFR.json` | success | 0.869 |  |
| 71 | lfr | `Distribute_Library/Single_Storage_Grid_32/Single_Storage_Grid_32_fromLFR.json` | success | 0.870 |  |
| 72 | lfr | `Distribute_Library/Single_Storage_Grid_64/Single_Storage_Grid_64_fromLFR.json` | success | 0.868 |  |
| 73 | lfr | `Distribute_Library/Transposer_02/Transposer_02_fromLFR.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=4, E=4, components=1, cycle_rank=1; cycle-closing connection(s): channel_4 |
| 74 | lfr | `Distribute_Library/Transposer_03/Transposer_03_fromLFR.json` | fail | 0.116 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=6, E=8, components=1, cycle_rank=3; cycle-closing connection(s): channel_5, channel_6, channel_8 |
| 75 | lfr | `Distribute_Library/Transposer_04/Transposer_04_fromLFR.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=23, E=35, components=1, cycle_rank=13; cycle-closing connection(s): channel_15, channel_16, channel_20, channel_21, channel_22, channel_26, channel_28, channel_29, channel_30, channel_31, channel_32, channel_33, channel_34 |
| 76 | lfr | `Distribute_Library/Transposer_08/Transposer_08_fromLFR.json` | success | 0.869 |  |
| 77 | lfr | `Distribute_Library/Transposer_16/Transposer_16_fromLFR.json` | success | 0.868 |  |
| 78 | lfr | `Distribute_Library/Transposer_32/Transposer_32_fromLFR.json` | success | 0.870 |  |
| 79 | lfr | `Distribute_Library/Transposer_64/Transposer_64_fromLFR.json` | success | 0.868 |  |
| 80 | lfr | `Drop_Ref/Droplet_Generator_1/Droplet_Generator_1_fromLFR.json` | success | 0.918 |  |
| 81 | lfr | `Drop_Ref/Droplet_Generator_2/Droplet_Generator_2_fromLFR.json` | success | 1.170 |  |
| 82 | lfr | `Drop_Ref/Droplet_Generator_3/Droplet_Generator_3_fromLFR.json` | fail | 0.165 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=20, E=24, components=1, cycle_rank=5; cycle-closing connection(s): channel_17, channel_19, channel_22, channel_23, channel_24 |
| 83 | lfr | `Drop_Ref/Droplet_Generator_4/Droplet_Generator_4_fromLFR.json` | fail | 0.165 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=12, E=12, components=1, cycle_rank=1; cycle-closing connection(s): channel_12 |
| 84 | lfr | `Drop_Ref/Dropx_Test_1/Dropx_Test_1_fromLFR.json` | success | 0.867 |  |
| 85 | lfr | `Drop_Ref/Dropx_Test_2/Dropx_Test_2_fromLFR.json` | success | 1.019 |  |
| 86 | lfr | `Drop_Ref/Dropx_Test_3/Dropx_Test_3_fromLFR.json` | success | 1.071 |  |
| 87 | lfr | `Drop_Ref/Dropx_Test_4/Dropx_Test_4_fromLFR.json` | fail | 0.165 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=8, E=8, components=1, cycle_rank=1; cycle-closing connection(s): channel_8 |
| 88 | lfr | `Drop_Ref/Dx_1/Dx_1_fromLFR.json` | success | 1.067 |  |
| 89 | lfr | `Drop_Ref/Dx_10/Dx_10_fromLFR.json` | success | 1.021 |  |
| 90 | lfr | `Drop_Ref/Dx_11/Dx_11_fromLFR.json` | success | 1.170 |  |
| 91 | lfr | `Drop_Ref/Dx_12/Dx_12_fromLFR.json` | success | 1.122 |  |
| 92 | lfr | `Drop_Ref/Dx_13/Dx_13_fromLFR.json` | success | 1.272 |  |
| 93 | lfr | `Drop_Ref/Dx_14/Dx_14_fromLFR.json` | fail | 0.168 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=9, E=10, components=1, cycle_rank=2; cycle-closing connection(s): channel_8, channel_9 |
| 94 | lfr | `Drop_Ref/Dx_15/Dx_15_fromLFR.json` | success | 0.970 |  |
| 95 | lfr | `Drop_Ref/Dx_2/Dx_2_fromLFR.json` | success | 1.121 |  |
| 96 | lfr | `Drop_Ref/Dx_3/Dx_3_fromLFR.json` | success | 1.119 |  |
| 97 | lfr | `Drop_Ref/Dx_4/Dx_4_fromLFR.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=18, E=18, components=1, cycle_rank=1; cycle-closing connection(s): channel_18 |
| 98 | lfr | `Drop_Ref/Dx_5/Dx_5_fromLFR.json` | success | 1.170 |  |
| 99 | lfr | `Drop_Ref/Dx_6/Dx_6_fromLFR.json` | success | 1.019 |  |
| 100 | lfr | `Drop_Ref/Dx_7/Dx_7_fromLFR.json` | success | 1.119 |  |
| 101 | lfr | `Drop_Ref/Dx_8/Dx_8_fromLFR.json` | success | 1.321 |  |
| 102 | lfr | `Drop_Ref/Dx_9/Dx_9_fromLFR.json` | success | 1.121 |  |
| 103 | lfr | `Expressions/Expression_1/Expression_1_fromLFR.json` | success | 0.969 |  |
| 104 | lfr | `Expressions/Expression_10/Expression_10_fromLFR.json` | success | 0.970 |  |
| 105 | lfr | `Expressions/Expression_11/Expression_11_fromLFR.json` | success | 0.918 |  |
| 106 | lfr | `Expressions/Expression_12/Expression_12_fromLFR.json` | success | 1.571 |  |
| 107 | lfr | `Expressions/Expression_13/Expression_13_fromLFR.json` | success | 0.918 |  |
| 108 | lfr | `Expressions/Expression_14/Expression_14_fromLFR.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=58, E=60, components=1, cycle_rank=3; cycle-closing connection(s): channel_13, channel_15, channel_55 |
| 109 | lfr | `Expressions/Expression_15/Expression_15_fromLFR.json` | success | 1.320 |  |
| 110 | lfr | `Expressions/Expression_2/Expression_2_fromLFR.json` | success | 0.918 |  |
| 111 | lfr | `Expressions/Expression_3/Expression_3_fromLFR.json` | success | 1.019 |  |
| 112 | lfr | `Expressions/Expression_4/Expression_4_fromLFR.json` | success | 1.019 |  |
| 113 | lfr | `Expressions/Expression_5/Expression_5_fromLFR.json` | success | 1.070 |  |
| 114 | lfr | `Expressions/Expression_6/Expression_6_fromLFR.json` | success | 1.120 |  |
| 115 | lfr | `Expressions/Expression_7/Expression_7_fromLFR.json` | success | 1.120 |  |
| 116 | lfr | `Expressions/Expression_8/Expression_8_fromLFR.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=10, E=10, components=1, cycle_rank=1; cycle-closing connection(s): channel_6 |
| 117 | lfr | `Expressions/Expression_9/Expression_9_fromLFR.json` | success | 0.921 |  |
| 118 | lfr | `Ghissues/Issue_10/Issue_10_fromLFR.json` | fail | 0.171 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=24, E=36, components=1, cycle_rank=13; cycle-closing connection(s): channel_20, channel_21, channel_23, channel_25, channel_26, channel_27, channel_29, channel_30, channel_31, channel_33, channel_34, channel_35, channel_36 |
| 119 | lfr | `Ghissues/Issue_15/Issue_15_fromLFR.json` | success | 0.975 |  |
| 120 | lfr | `Ghissues/Issue_2/Issue_2_fromLFR.json` | success | 0.871 |  |
| 121 | lfr | `Ghissues/Issue_3/Issue_3_fromLFR.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=20, E=28, components=1, cycle_rank=9; cycle-closing connection(s): channel_13, channel_15, channel_20, channel_21, channel_22, channel_23, channel_24, channel_26, channel_28 |
| 122 | lfr | `Ghissues/Issue_6/Issue_6_fromLFR.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=35, E=51, components=1, cycle_rank=17; cycle-closing connection(s): channel_20, channel_31, channel_32, channel_33, channel_34, channel_37, channel_38, channel_41, channel_42, channel_44, channel_45, channel_46, channel_47, channel_48, channel_49, channel_50, channel_51 |
| 123 | lfr | `Ghissues/Issue_7/Issue_7_fromLFR.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=44, E=52, components=1, cycle_rank=9; cycle-closing connection(s): channel_26, channel_30, channel_40, channel_45, channel_46, channel_47, channel_48, channel_49, channel_50 |
| 124 | lfr | `Ghissues/Issue_8/Issue_8_fromLFR.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=48, E=57, components=1, cycle_rank=10; cycle-closing connection(s): channel_26, channel_36, channel_42, channel_48, channel_50, channel_51, channel_52, channel_54, channel_55, channel_56 |
| 125 | lfr | `Ghissues/Issue_9/Issue_9_fromLFR.json` | fail | 0.168 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=47, E=62, components=1, cycle_rank=16; cycle-closing connection(s): channel_34, channel_36, channel_37, channel_44, channel_48, channel_50, channel_52, channel_53, channel_54, channel_55, channel_56, channel_57, channel_59, channel_60, channel_61, channel_62 |
| 126 | lfr | `Graph_Coverage/Tree_Fanin/Tree_Fanin_fromLFR.json` | success | 1.072 |  |
| 127 | lfr | `Graph_Coverage/Tree_Fanout/Tree_Fanout_fromLFR.json` | success | 1.124 |  |
| 128 | lfr | `Literature_Benchmarks/Device_1_Sc_Rna_Seq/Device_1_Sc_Rna_Seq_fromLFR.json` | fail | 0.169 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=9, E=9, components=1, cycle_rank=1; cycle-closing connection(s): channel_9 |
| 129 | lfr | `Literature_Benchmarks/Device_2_Artificial_Cells/Device_2_Artificial_Cells_fromLFR.json` | success | 1.225 |  |
| 130 | lfr | `Literature_Benchmarks/Device_4_Molecular_Diagnostics/Device_4_Molecular_Diagnostics_fromLFR.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=9, E=9, components=1, cycle_rank=1; cycle-closing connection(s): channel_5 |
| 131 | lfr | `Literature_Benchmarks/Device_5_Bacteria_Diagnostics/Device_5_Bacteria_Diagnostics_fromLFR.json` | success | 1.226 |  |
| 132 | lfr | `Literature_Benchmarks/Device_6_Organic_Chemical_Synthesis/Device_6_Organic_Chemical_Synthesis_fromLFR.json` | success | 2.475 |  |
| 133 | lfr | `Literature_Benchmarks/Device_7_Enzyme_Screening/Device_7_Enzyme_Screening_fromLFR.json` | success | 10.754 |  |
| 134 | lfr | `Literature_Benchmarks/library/mip_biosensor/mip_biosensor_fromLFR.json` | success | 0.918 |  |
| 135 | lfr | `Mars/Antibiotic_Resistance/Antibiotic_Resistance_fromLFR.json` | success | 1.219 |  |
| 136 | lfr | `Mars/Cell_Lysis/Cell_Lysis_fromLFR.json` | success | 1.124 |  |
| 137 | lfr | `Mars/Dna_Digest/Dna_Digest_fromLFR.json` | success | 1.274 |  |
| 138 | lfr | `Mars/Fluorescence/Fluorescence_fromLFR.json` | success | 1.119 |  |
| 139 | lfr | `Mars/Ligation/Ligation_fromLFR.json` | success | 1.974 |  |
| 140 | lfr | `Mars/Pcr/Pcr_fromLFR.json` | success | 1.120 |  |
| 141 | lfr | `Mars/Sorting/Sorting_fromLFR.json` | success | 0.969 |  |
| 142 | lfr | `Mars/Transformation/Transformation_fromLFR.json` | success | 1.071 |  |
| 143 | lfr | `Protocols/Cell_Sorting/Cell_Sorting_fromLFR.json` | success | 0.920 |  |
| 144 | lfr | `Protocols/Directed_Evolution/Directed_Evolution_fromLFR.json` | fail | 0.168 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=27, E=42, components=1, cycle_rank=16; cycle-closing connection(s): channel_13, channel_24, channel_26, channel_28, channel_29, channel_30, channel_31, channel_33, channel_34, channel_35, channel_36, channel_37, channel_38, channel_39, channel_40, channel_41 |
| 145 | lfr | `Technology_Mapping/Cycle/Cycle_fromLFR.json` | success | 0.969 |  |
| 146 | lfr | `Technology_Mapping/Instance_Mapping/Instance_Mapping_fromLFR.json` | success | 0.870 |  |
| 147 | lfr | `Technology_Mapping/N_Greater_M_Map/N_Greater_M_Map_fromLFR.json` | success | 1.070 |  |
| 148 | lfr | `Technology_Mapping/N_Less_M_Map/N_Less_M_Map_fromLFR.json` | success | 1.070 |  |
| 149 | lfr | `Technology_Mapping/One_To_One_Mapping/One_To_One_Mapping_fromLFR.json` | success | 0.919 |  |
| 150 | lfr | `Technology_Mapping/Tree_Bus/Tree_Bus_fromLFR.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=11, E=18, components=1, cycle_rank=8; cycle-closing connection(s): channel_4, channel_6, channel_8, channel_10, channel_12, channel_14, channel_16, channel_18 |
| 151 | lfr | `Technology_Mapping/Tree_Fanin_Mapping/Tree_Fanin_Mapping_fromLFR.json` | success | 1.171 |  |
| 152 | lfr | `Technology_Mapping/Tree_Fanout_Mapping_1/Tree_Fanout_Mapping_1_fromLFR.json` | success | 1.120 |  |
| 153 | lfr | `Technology_Mapping/Tree_Fanout_Mapping_2/Tree_Fanout_Mapping_2_fromLFR.json` | success | 1.119 |  |
| 154 | lfr | `Technology_Mapping/Tree_Fanout_Mapping_3/Tree_Fanout_Mapping_3_fromLFR.json` | success | 1.121 |  |
| 155 | lfr | `Technology_Mapping/Tree_Storage_Bus_Mapping/Tree_Storage_Bus_Mapping_fromLFR.json` | fail | 0.117 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=20, E=43, components=1, cycle_rank=24; cycle-closing connection(s): channel_19, channel_20, channel_21, channel_22, channel_23, channel_24, channel_25, channel_26, channel_28, channel_29, channel_30, channel_31, channel_32, channel_33, channel_34, channel_35, channel_36, channel_37, channel_38, channel_39, channel_40, channel_41, channel_42, channel_43 |
| 156 | lfr | `Transport_Networks/Distribute_Network_Examples/Distribute_Network_Examples_fromLFR.json` | timeout | 1800.010 | exceeded 1800s |
| 157 | lfr | `Transport_Networks/One_To_8/One_To_8_fromLFR.json` | timeout | 1800.017 | exceeded 1800s |
| 158 | lfr | `Transport_Networks/One_To_One/One_To_One_fromLFR.json` | success | 0.918 |  |
| 159 | mint | `Base/Crossing_H/Crossing_H_fromMINT.json` | success | 1.823 |  |
| 160 | mint | `Base/Crossing_V/Crossing_V_fromMINT.json` | success | 1.976 |  |
| 161 | mint | `Base/Grad_Gen_H/Grad_Gen_H_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=11, E=12, components=1, cycle_rank=2; cycle-closing connection(s): c10, c11 |
| 162 | mint | `Base/Grad_Gen_V/Grad_Gen_V_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=11, E=12, components=1, cycle_rank=2; cycle-closing connection(s): c10, c11 |
| 163 | mint | `Base/Grid_4_Mixer/Grid_4_Mixer_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=24, E=38, components=1, cycle_rank=15; cycle-closing connection(s): c6, c7, c8, c13, c14, c15, c20, c21, c22, c27, c28, c29, c31, c32, c33 |
| 164 | mint | `Base/Horizontal_MUX_01/Horizontal_MUX_01_fromMINT.json` | success | 1.623 |  |
| 165 | mint | `Base/Logic_Test_01/Logic_Test_01_fromMINT.json` | success | 1.020 |  |
| 166 | mint | `Base/Logic_Test_02/Logic_Test_02_fromMINT.json` | success | 1.170 |  |
| 167 | mint | `Base/Logic_Test_03/Logic_Test_03_fromMINT.json` | success | 1.371 |  |
| 168 | mint | `Base/Long_Cell_Trap_Two_Port/Long_Cell_Trap_Two_Port_fromMINT.json` | success | 0.920 |  |
| 169 | mint | `Base/MUX_8/MUX_8_fromMINT.json` | success | 1.573 |  |
| 170 | mint | `Base/Net_Multi_Test/Net_Multi_Test_fromMINT.json` | success | 14.056 |  |
| 171 | mint | `Base/Net_Test/Net_Test_fromMINT.json` | success | 1.371 |  |
| 172 | mint | `Base/Net_Valve_Test/Net_Valve_Test_fromMINT.json` | success | 37.169 |  |
| 173 | mint | `Base/Node_Long_Cell_Trap_01/Node_Long_Cell_Trap_01_fromMINT.json` | success | 1.095 |  |
| 174 | mint | `Base/Node_Long_Cell_Trap_02/Node_Long_Cell_Trap_02_fromMINT.json` | success | 1.069 |  |
| 175 | mint | `Base/Node_Long_Cell_Trap_03/Node_Long_Cell_Trap_03_fromMINT.json` | success | 1.068 |  |
| 176 | mint | `Base/Node_Long_Cell_Trap_04/Node_Long_Cell_Trap_04_fromMINT.json` | success | 1.069 |  |
| 177 | mint | `Base/Node_Test_01/Node_Test_01_fromMINT.json` | success | 4.930 |  |
| 178 | mint | `Base/Nonplanar/Nonplanar_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=4, E=6, components=1, cycle_rank=3; cycle-closing connection(s): c4, c5, c6 |
| 179 | mint | `Base/Port_Bank_01/Port_Bank_01_fromMINT.json` | success | 0.667 |  |
| 180 | mint | `Base/Port_Multi_Connection/Port_Multi_Connection_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=4, E=4, components=1, cycle_rank=1; cycle-closing connection(s): c4 |
| 181 | mint | `Base/Square_Cell_Trap_Chambers/Square_Cell_Trap_Chambers_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=17, E=20, components=1, cycle_rank=4; cycle-closing connection(s): c15, c17, c19, c20 |
| 182 | mint | `Base/Square_Cell_Trap_Ports/Square_Cell_Trap_Ports_fromMINT.json` | success | 5.984 |  |
| 183 | mint | `Base/Super_MUX_1024/Super_MUX_1024_fromMINT.json` | success | 306.905 |  |
| 184 | mint | `Base/Super_MUX_128/Super_MUX_128_fromMINT.json` | success | 20.554 |  |
| 185 | mint | `Base/Super_MUX_16/Super_MUX_16_fromMINT.json` | success | 2.477 |  |
| 186 | mint | `Base/Super_MUX_2/Super_MUX_2_fromMINT.json` | success | 2.574 |  |
| 187 | mint | `Base/Super_MUX_256/Super_MUX_256_fromMINT.json` | success | 48.859 |  |
| 188 | mint | `Base/Super_MUX_32/Super_MUX_32_fromMINT.json` | success | 4.473 |  |
| 189 | mint | `Base/Super_MUX_4/Super_MUX_4_fromMINT.json` | success | 1.221 |  |
| 190 | mint | `Base/Super_MUX_512/Super_MUX_512_fromMINT.json` | success | 119.495 |  |
| 191 | mint | `Base/Super_MUX_64/Super_MUX_64_fromMINT.json` | success | 8.943 |  |
| 192 | mint | `Base/Super_MUX_8/Super_MUX_8_fromMINT.json` | success | 1.672 |  |
| 193 | mint | `Base/Test_MUX_01/Test_MUX_01_fromMINT.json` | success | 260.275 |  |
| 194 | mint | `Base/Test_MUX_02/Test_MUX_02_fromMINT.json` | success | 1.321 |  |
| 195 | mint | `Base/Three_Port_Channel/Three_Port_Channel_fromMINT.json` | success | 0.870 |  |
| 196 | mint | `Base/Transposer_Test/Transposer_Test_fromMINT.json` | success | 4.634 |  |
| 197 | mint | `Base/Tree_Test_01/Tree_Test_01_fromMINT.json` | success | 2.528 |  |
| 198 | mint | `Base/Tree_Test_02/Tree_Test_02_fromMINT.json` | success | 0.919 |  |
| 199 | mint | `Base/Tree_Valve_Test/Tree_Valve_Test_fromMINT.json` | success | 3.577 |  |
| 200 | mint | `CIDAR_Lab_Past_Devices/Chemostat_Chip/Chemostat_Chip_fromMINT.json` | fail | 0.176 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=36, E=50, components=1, cycle_rank=15; cycle-closing connection(s): channel_19, channel_20, channel_21, channel_22, channel_23, channel_24, channel_25, channel_37, channel_38, channel_39, channel_40, channel_41, channel_42, channel_43, channel_44 |
| 201 | mint | `CIDAR_Lab_Past_Devices/Dna_Synthesizer/Dna_Synthesizer_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=65, E=74, components=1, cycle_rank=10; cycle-closing connection(s): channel_60, channel_61, channel_62, channel_63, channel_64, channel_65, channel_66, channel_67, channel_68, channel_69 |
| 202 | mint | `CIDAR_Lab_Past_Devices/Droplet_Merger_Simple/Droplet_Merger_Simple_fromMINT.json` | success | 1.123 |  |
| 203 | mint | `CIDAR_Lab_Past_Devices/Dual_Lane_Droplet/Dual_Lane_Droplet_fromMINT.json` | success | 1.621 |  |
| 204 | mint | `CIDAR_Lab_Past_Devices/Flow_Focus/Flow_Focus_fromMINT.json` | success | 0.869 |  |
| 205 | mint | `CIDAR_Lab_Past_Devices/Genetic_Clock_Testing_Tool/Genetic_Clock_Testing_Tool_fromMINT.json` | fail | 0.116 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=9, E=10, components=1, cycle_rank=2; cycle-closing connection(s): channel_9, channel_10 |
| 206 | mint | `CIDAR_Lab_Past_Devices/Glycoform/Glycoform_fromMINT.json` | success | 1.069 |  |
| 207 | mint | `CIDAR_Lab_Past_Devices/Grad_Cells/Grad_Cells_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=9, E=12, components=1, cycle_rank=4; cycle-closing connection(s): channel_6, channel_7, channel_8, channel_11 |
| 208 | mint | `CIDAR_Lab_Past_Devices/Gradient/Gradient_fromMINT.json` | fail | 0.168 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=48, E=57, components=1, cycle_rank=10; cycle-closing connection(s): channel_45, channel_47, channel_48, channel_49, channel_50, channel_52, channel_53, channel_54, channel_55, channel_56 |
| 209 | mint | `CIDAR_Lab_Past_Devices/Grid_02/Grid_02_fromMINT.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=8, E=10, components=1, cycle_rank=3; cycle-closing connection(s): channel_vertical_1_2, channel_in_2, channel_out_2 |
| 210 | mint | `CIDAR_Lab_Past_Devices/Hasty_Cell_Traps/Hasty_Cell_Traps_fromMINT.json` | fail | 0.171 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=6, E=8, components=1, cycle_rank=3; cycle-closing connection(s): channel_6, channel_7, channel_8 |
| 211 | mint | `CIDAR_Lab_Past_Devices/Hmlp_Dual_Bank/Hmlp_Dual_Bank_fromMINT.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=43, E=63, components=1, cycle_rank=21; cycle-closing connection(s): channel_32, channel_35, channel_36, channel_38, channel_39, channel_41, channel_42, channel_44, channel_45, channel_47, channel_48, channel_50, channel_51, channel_53, channel_54, channel_56, channel_57, channel_59, channel_60, channel_62, channel_63 |
| 212 | mint | `CIDAR_Lab_Past_Devices/Incubator/Incubator_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=22, E=26, components=1, cycle_rank=5; cycle-closing connection(s): channel_18, channel_20, channel_22, channel_24, channel_26 |
| 213 | mint | `CIDAR_Lab_Past_Devices/Inlet_16/Inlet_16_fromMINT.json` | fail | 0.171 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=57, E=73, components=1, cycle_rank=17; cycle-closing connection(s): channel_42, channel_50, channel_51, channel_52, channel_53, channel_54, channel_55, channel_56, channel_57, channel_58, channel_59, channel_60, channel_61, channel_62, channel_63, channel_64, channel_71 |
| 214 | mint | `CIDAR_Lab_Past_Devices/Kinetics/Kinetics_fromMINT.json` | success | 0.920 |  |
| 215 | mint | `CIDAR_Lab_Past_Devices/Logic_04/Logic_04_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=31, E=49, components=1, cycle_rank=19; cycle-closing connection(s): channel_15, channel_16, channel_24, channel_25, channel_26, channel_28, channel_29, channel_38, channel_39, channel_40, channel_41, channel_42, channel_43, channel_44, channel_45, channel_46, channel_47, channel_48, channel_49 |
| 216 | mint | `CIDAR_Lab_Past_Devices/Mfd_005_Chip/Mfd_005_Chip_fromMINT.json` | success | 1.124 |  |
| 217 | mint | `CIDAR_Lab_Past_Devices/Microalgal_Bioassay/Microalgal_Bioassay_fromMINT.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=11, E=14, components=1, cycle_rank=4; cycle-closing connection(s): channel_5, channel_9, channel_10, channel_11 |
| 218 | mint | `CIDAR_Lab_Past_Devices/Microdroplet/Microdroplet_fromMINT.json` | fail | 0.171 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=26, E=31, components=1, cycle_rank=6; cycle-closing connection(s): channel_21, channel_23, channel_25, channel_27, channel_29, channel_31 |
| 219 | mint | `CIDAR_Lab_Past_Devices/Microreactor/Microreactor_fromMINT.json` | fail | 0.170 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=8, E=11, components=1, cycle_rank=4; cycle-closing connection(s): channel_8, channel_9, channel_10, channel_11 |
| 220 | mint | `CIDAR_Lab_Past_Devices/Mix_Incubate_Express/Mix_Incubate_Express_fromMINT.json` | success | 0.970 |  |
| 221 | mint | `CIDAR_Lab_Past_Devices/Mixer_Trap_Simple/Mixer_Trap_Simple_fromMINT.json` | success | 0.870 |  |
| 222 | mint | `CIDAR_Lab_Past_Devices/Multi_Input/Multi_Input_fromMINT.json` | fail | 0.168 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=17, E=22, components=1, cycle_rank=6; cycle-closing connection(s): channel_12, channel_14, channel_16, channel_18, channel_20, channel_22 |
| 223 | mint | `CIDAR_Lab_Past_Devices/MUX_96_Chambers/MUX_96_Chambers_fromMINT.json` | fail | 0.168 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=146, E=240, components=1, cycle_rank=95; cycle-closing connection(s): channel_64, channel_65, channel_66, channel_67, channel_68, channel_69, channel_70, channel_71, channel_72, channel_73, channel_74, channel_75, channel_76, channel_77, channel_78, channel_79, channel_80, channel_81, channel_82, channel_83, channel_84, channel_85, channel_86, channel_87, channel_88, channel_89, channel_90, channel_91, channel_92, channel_159, channel_160, channel_161, channel_162, channel_163, channel_164, channel_165, channel_166, channel_167, channel_168, channel_169, channel_170, channel_171, channel_172, channel_173, channel_174, channel_175, channel_176, channel_177, channel_178, channel_179, channel_180, channel_181, channel_182, channel_183, channel_184, channel_185, channel_186, channel_187, channel_188, channel_189, channel_190, channel_191, channel_192, channel_193, channel_194, channel_195, channel_196, channel_197, channel_198, channel_199, channel_200, channel_201, channel_202, channel_203, channel_204, channel_205, channel_206, channel_207, channel_208, channel_209, channel_210, channel_211, channel_212, channel_213, channel_214, channel_215, channel_216, channel_217, channel_218, channel_219, channel_220, channel_221, channel_222, channel_223, channel_224 |
| 224 | mint | `CIDAR_Lab_Past_Devices/Net_MUX/Net_MUX_fromMINT.json` | fail | 0.168 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=32, E=50, components=1, cycle_rank=19; cycle-closing connection(s): channel_26, channel_32, channel_33, channel_34, channel_35, channel_36, channel_37, channel_38, channel_39, channel_40, channel_42, channel_43, channel_44, channel_45, channel_46, channel_47, channel_48, channel_49, channel_50 |
| 225 | mint | `CIDAR_Lab_Past_Devices/Nine_To_One_MUX/Nine_To_One_MUX_fromMINT.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=28, E=35, components=1, cycle_rank=8; cycle-closing connection(s): channel_20, channel_21, channel_22, channel_23, channel_24, channel_25, channel_26, channel_27 |
| 226 | mint | `CIDAR_Lab_Past_Devices/Number_Declarations/Number_Declarations_fromMINT.json` | success | 0.869 |  |
| 227 | mint | `CIDAR_Lab_Past_Devices/Olfactory/Olfactory_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=13, E=16, components=1, cycle_rank=4; cycle-closing connection(s): channel_10, channel_12, channel_14, channel_16 |
| 228 | mint | `CIDAR_Lab_Past_Devices/Pump_Passthrough/Pump_Passthrough_fromMINT.json` | success | 0.874 |  |
| 229 | mint | `CIDAR_Lab_Past_Devices/Ring/Ring_fromMINT.json` | success | 0.919 |  |
| 230 | mint | `CIDAR_Lab_Past_Devices/Root_Chip/Root_Chip_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=22, E=23, components=1, cycle_rank=2; cycle-closing connection(s): channel_22, channel_23 |
| 231 | mint | `CIDAR_Lab_Past_Devices/Rotary_16/Rotary_16_fromMINT.json` | fail | 0.175 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=63, E=109, components=1, cycle_rank=47; cycle-closing connection(s): channel_35, channel_36, channel_38, channel_40, channel_41, channel_42, channel_43, channel_45, channel_46, channel_47, channel_56, channel_58, channel_59, channel_60, channel_61, channel_78, channel_79, channel_80, channel_81, channel_82, channel_83, channel_84, channel_85, channel_86, channel_87, channel_88, channel_89, channel_90, channel_91, channel_92, channel_93, channel_94, channel_95, channel_96, channel_97, channel_98, channel_99, channel_100, channel_101, channel_102, channel_103, channel_104, channel_105, channel_106, channel_107, channel_108, channel_109 |
| 232 | mint | `CIDAR_Lab_Past_Devices/Rotary_Cells/Rotary_Cells_fromMINT.json` | fail | 0.172 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=15, E=20, components=1, cycle_rank=6; cycle-closing connection(s): channel_10, channel_11, channel_12, channel_18, channel_19, channel_20 |
| 233 | mint | `CIDAR_Lab_Past_Devices/Seeding/Seeding_fromMINT.json` | fail | 0.171 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=23, E=38, components=1, cycle_rank=16; cycle-closing connection(s): channel_9, channel_11, channel_12, channel_13, channel_14, channel_24, channel_25, channel_26, channel_27, channel_28, channel_29, channel_30, channel_31, channel_32, channel_36, channel_38 |
| 234 | mint | `CIDAR_Lab_Past_Devices/Single_Port/Single_Port_fromMINT.json` | success | 0.819 |  |
| 235 | mint | `CIDAR_Lab_Past_Devices/Three_Reagent_Mix/Three_Reagent_Mix_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=9, E=10, components=1, cycle_rank=2; cycle-closing connection(s): channel_8, channel_10 |
| 236 | mint | `Constraints/Array_Constraint/Array_Constraint_fromMINT.json` | success | 4.180 |  |
| 237 | mint | `Constraints/Orthogonal_Constraint/Orthogonal_Constraint_fromMINT.json` | success | 0.969 |  |
| 238 | mint | `Constraints/Orthogonal_Constraint_Large/Orthogonal_Constraint_Large_fromMINT.json` | success | 1.421 |  |
| 239 | mint | `Constraints/Position_Constraint/Position_Constraint_fromMINT.json` | success | 0.874 |  |
| 240 | mint | `Constraints/Relative_Orientation_Constraint/Relative_Orientation_Constraint_fromMINT.json` | success | 0.925 |  |
| 241 | mint | `Constraints/Tree_Constraint/Tree_Constraint_fromMINT.json` | success | 0.919 |  |
| 242 | mint | `COVID/Aj_Rtpcr_8_Primer/Aj_Rtpcr_8_Primer_fromMINT.json` | fail | 0.116 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=38, E=56, components=1, cycle_rank=19; cycle-closing connection(s): channel_19, channel_38, channel_39, channel_40, channel_41, channel_42, channel_43, channel_44, channel_46, channel_47, channel_48, channel_49, channel_50, channel_51, channel_52, channel_53, channel_54, channel_55, channel_56 |
| 243 | mint | `COVID/Arize/Arize_fromMINT.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=39, E=44, components=1, cycle_rank=6; cycle-closing connection(s): channel_25, channel_31, channel_33, channel_38, channel_40, channel_44 |
| 244 | mint | `COVID/Covid_Crispr/Covid_Crispr_fromMINT.json` | success | 0.930 |  |
| 245 | mint | `COVID/Crispr/Crispr_fromMINT.json` | success | 1.070 |  |
| 246 | mint | `COVID/Detectr/Detectr_fromMINT.json` | success | 1.270 |  |
| 247 | mint | `COVID/Elisa/Elisa_fromMINT.json` | fail | 0.172 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=8, E=8, components=1, cycle_rank=1; cycle-closing connection(s): channel_8 |
| 248 | mint | `COVID/Gel_Electrophoresis/Gel_Electrophoresis_fromMINT.json` | fail | 0.172 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=12, E=14, components=1, cycle_rank=3; cycle-closing connection(s): channel_10, channel_12, channel_14 |
| 249 | mint | `COVID/Hybri_Detect/Hybri_Detect_fromMINT.json` | success | 1.030 |  |
| 250 | mint | `COVID/Part_1_Rna_Prep/Part_1_Rna_Prep_fromMINT.json` | success | 1.020 |  |
| 251 | mint | `COVID/Part_2_Rt_Step/Part_2_Rt_Step_fromMINT.json` | success | 0.975 |  |
| 252 | mint | `COVID/Part_3_Gel/Part_3_Gel_fromMINT.json` | success | 1.074 |  |
| 253 | mint | `COVID/Rt_Pcr/Rt_Pcr_fromMINT.json` | success | 0.925 |  |
| 254 | mint | `Distribute_Expressions/And_Annotation_Test/And_Annotation_Test_fromMINT.json` | success | 3.583 |  |
| 255 | mint | `Distribute_Expressions/Dist_Expression_1/Dist_Expression_1_fromMINT.json` | success | 0.825 |  |
| 256 | mint | `Distribute_Expressions/Dist_Expression_2/Dist_Expression_2_fromMINT.json` | success | 0.926 |  |
| 257 | mint | `Distribute_Expressions/Dist_Expression_3/Dist_Expression_3_fromMINT.json` | success | 0.919 |  |
| 258 | mint | `Distribute_Library/Cell_Traps_4/Cell_Traps_4_fromMINT.json` | success | 0.819 |  |
| 259 | mint | `Distribute_Library/Hv_Storage_Grid_04/Hv_Storage_Grid_04_fromMINT.json` | success | 0.818 |  |
| 260 | mint | `Distribute_Library/Hv_Storage_Grid_08/Hv_Storage_Grid_08_fromMINT.json` | success | 0.819 |  |
| 261 | mint | `Distribute_Library/Hv_Storage_Grid_16/Hv_Storage_Grid_16_fromMINT.json` | success | 0.819 |  |
| 262 | mint | `Distribute_Library/Hv_Storage_Grid_32/Hv_Storage_Grid_32_fromMINT.json` | success | 0.819 |  |
| 263 | mint | `Distribute_Library/Hv_Storage_Grid_64/Hv_Storage_Grid_64_fromMINT.json` | success | 0.819 |  |
| 264 | mint | `Distribute_Library/MUX_02_In/MUX_02_In_fromMINT.json` | success | 1.270 |  |
| 265 | mint | `Distribute_Library/MUX_02_Out/MUX_02_Out_fromMINT.json` | success | 1.270 |  |
| 266 | mint | `Distribute_Library/MUX_04_In/MUX_04_In_fromMINT.json` | success | 17.472 |  |
| 267 | mint | `Distribute_Library/MUX_04_Out/MUX_04_Out_fromMINT.json` | success | 16.674 |  |
| 268 | mint | `Distribute_Library/MUX_08_In/MUX_08_In_fromMINT.json` | timeout | 1800.011 | exceeded 1800s |
| 269 | mint | `Distribute_Library/MUX_08_Out/MUX_08_Out_fromMINT.json` | timeout | 1800.017 | exceeded 1800s |
| 270 | mint | `Distribute_Library/MUX_16_In/MUX_16_In_fromMINT.json` | timeout | 1800.018 | exceeded 1800s |
| 271 | mint | `Distribute_Library/MUX_16_Out/MUX_16_Out_fromMINT.json` | timeout | 1800.021 | exceeded 1800s |
| 272 | mint | `Distribute_Library/MUX_32_In/MUX_32_In_fromMINT.json` | timeout | 1800.019 | exceeded 1800s |
| 273 | mint | `Distribute_Library/MUX_32_Out/MUX_32_Out_fromMINT.json` | timeout | 1800.025 | exceeded 1800s |
| 274 | mint | `Distribute_Library/MUX_64_In/MUX_64_In_fromMINT.json` | timeout | 1800.022 | exceeded 1800s |
| 275 | mint | `Distribute_Library/MUX_64_Out/MUX_64_Out_fromMINT.json` | timeout | 1800.023 | exceeded 1800s |
| 276 | mint | `Distribute_Library/Single_Storage_Grid_01/Single_Storage_Grid_01_fromMINT.json` | success | 0.871 |  |
| 277 | mint | `Distribute_Library/Single_Storage_Grid_02/Single_Storage_Grid_02_fromMINT.json` | success | 0.873 |  |
| 278 | mint | `Distribute_Library/Single_Storage_Grid_04/Single_Storage_Grid_04_fromMINT.json` | success | 0.819 |  |
| 279 | mint | `Distribute_Library/Single_Storage_Grid_08/Single_Storage_Grid_08_fromMINT.json` | success | 0.877 |  |
| 280 | mint | `Distribute_Library/Single_Storage_Grid_16/Single_Storage_Grid_16_fromMINT.json` | success | 0.870 |  |
| 281 | mint | `Distribute_Library/Single_Storage_Grid_32/Single_Storage_Grid_32_fromMINT.json` | success | 0.829 |  |
| 282 | mint | `Distribute_Library/Single_Storage_Grid_64/Single_Storage_Grid_64_fromMINT.json` | success | 0.825 |  |
| 283 | mint | `Distribute_Library/Transposer_02/Transposer_02_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=4, E=4, components=1, cycle_rank=1; cycle-closing connection(s): channel_4 |
| 284 | mint | `Distribute_Library/Transposer_03/Transposer_03_fromMINT.json` | fail | 0.168 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=6, E=8, components=1, cycle_rank=3; cycle-closing connection(s): channel_5, channel_7, channel_8 |
| 285 | mint | `Distribute_Library/Transposer_04/Transposer_04_fromMINT.json` | fail | 0.172 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=23, E=35, components=1, cycle_rank=13; cycle-closing connection(s): channel_19, channel_22, channel_23, channel_24, channel_25, channel_27, channel_28, channel_29, channel_30, channel_32, channel_33, channel_34, channel_35 |
| 286 | mint | `Distribute_Library/Transposer_08/Transposer_08_fromMINT.json` | success | 0.821 |  |
| 287 | mint | `Distribute_Library/Transposer_16/Transposer_16_fromMINT.json` | success | 0.818 |  |
| 288 | mint | `Distribute_Library/Transposer_32/Transposer_32_fromMINT.json` | success | 0.868 |  |
| 289 | mint | `Distribute_Library/Transposer_64/Transposer_64_fromMINT.json` | success | 0.821 |  |
| 290 | mint | `Drop_Ref/Droplet_Generator_1/Droplet_Generator_1_fromMINT.json` | success | 0.919 |  |
| 291 | mint | `Drop_Ref/Droplet_Generator_2/Droplet_Generator_2_fromMINT.json` | success | 1.181 |  |
| 292 | mint | `Drop_Ref/Droplet_Generator_3/Droplet_Generator_3_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=22, E=26, components=1, cycle_rank=5; cycle-closing connection(s): channel_18, channel_20, channel_22, channel_24, channel_26 |
| 293 | mint | `Drop_Ref/Droplet_Generator_4/Droplet_Generator_4_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=16, E=16, components=1, cycle_rank=1; cycle-closing connection(s): channel_16 |
| 294 | mint | `Drop_Ref/Dropx_Test_1/Dropx_Test_1_fromMINT.json` | success | 0.920 |  |
| 295 | mint | `Drop_Ref/Dropx_Test_2/Dropx_Test_2_fromMINT.json` | success | 1.069 |  |
| 296 | mint | `Drop_Ref/Dropx_Test_3/Dropx_Test_3_fromMINT.json` | success | 1.129 |  |
| 297 | mint | `Drop_Ref/Dropx_Test_4/Dropx_Test_4_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=8, E=8, components=1, cycle_rank=1; cycle-closing connection(s): channel_8 |
| 298 | mint | `Drop_Ref/Dx_1/Dx_1_fromMINT.json` | success | 1.072 |  |
| 299 | mint | `Drop_Ref/Dx_10/Dx_10_fromMINT.json` | success | 1.020 |  |
| 300 | mint | `Drop_Ref/Dx_10_Ref/Dx_10_Ref_fromMINT.json` | success | 1.033 |  |
| 301 | mint | `Drop_Ref/Dx_11/Dx_11_fromMINT.json` | success | 1.170 |  |
| 302 | mint | `Drop_Ref/Dx_11_Ref/Dx_11_Ref_fromMINT.json` | success | 1.220 |  |
| 303 | mint | `Drop_Ref/Dx_12/Dx_12_fromMINT.json` | success | 1.071 |  |
| 304 | mint | `Drop_Ref/Dx_12_Ref/Dx_12_Ref_fromMINT.json` | success | 1.071 |  |
| 305 | mint | `Drop_Ref/Dx_13/Dx_13_fromMINT.json` | success | 1.271 |  |
| 306 | mint | `Drop_Ref/Dx_13_Ref/Dx_13_Ref_fromMINT.json` | success | 1.329 |  |
| 307 | mint | `Drop_Ref/Dx_14/Dx_14_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=9, E=10, components=1, cycle_rank=2; cycle-closing connection(s): channel_8, channel_10 |
| 308 | mint | `Drop_Ref/Dx_14_Ref/Dx_14_Ref_fromMINT.json` | fail | 0.175 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=15, E=15, components=1, cycle_rank=1; cycle-closing connection(s): channel_incubate4 |
| 309 | mint | `Drop_Ref/Dx_15/Dx_15_fromMINT.json` | success | 0.970 |  |
| 310 | mint | `Drop_Ref/Dx_15_Ref/Dx_15_Ref_fromMINT.json` | success | 0.971 |  |
| 311 | mint | `Drop_Ref/Dx_1_Ref/Dx_1_Ref_fromMINT.json` | success | 1.022 |  |
| 312 | mint | `Drop_Ref/Dx_2/Dx_2_fromMINT.json` | success | 1.127 |  |
| 313 | mint | `Drop_Ref/Dx_2_Ref/Dx_2_Ref_fromMINT.json` | success | 1.124 |  |
| 314 | mint | `Drop_Ref/Dx_3/Dx_3_fromMINT.json` | success | 1.073 |  |
| 315 | mint | `Drop_Ref/Dx_3_Ref/Dx_3_Ref_fromMINT.json` | success | 1.075 |  |
| 316 | mint | `Drop_Ref/Dx_4/Dx_4_fromMINT.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=20, E=20, components=1, cycle_rank=1; cycle-closing connection(s): channel_19 |
| 317 | mint | `Drop_Ref/Dx_4_Ref/Dx_4_Ref_fromMINT.json` | success | 1.224 |  |
| 318 | mint | `Drop_Ref/Dx_5/Dx_5_fromMINT.json` | success | 1.177 |  |
| 319 | mint | `Drop_Ref/Dx_5_Ref/Dx_5_Ref_fromMINT.json` | success | 1.229 |  |
| 320 | mint | `Drop_Ref/Dx_6/Dx_6_fromMINT.json` | success | 1.028 |  |
| 321 | mint | `Drop_Ref/Dx_6_Ref/Dx_6_Ref_fromMINT.json` | success | 1.019 |  |
| 322 | mint | `Drop_Ref/Dx_7/Dx_7_fromMINT.json` | success | 1.219 |  |
| 323 | mint | `Drop_Ref/Dx_7_Ref/Dx_7_Ref_fromMINT.json` | success | 1.230 |  |
| 324 | mint | `Drop_Ref/Dx_8/Dx_8_fromMINT.json` | success | 1.276 |  |
| 325 | mint | `Drop_Ref/Dx_8_Ref/Dx_8_Ref_fromMINT.json` | success | 1.278 |  |
| 326 | mint | `Drop_Ref/Dx_9/Dx_9_fromMINT.json` | success | 1.119 |  |
| 327 | mint | `Drop_Ref/Dx_9_Ref/Dx_9_Ref_fromMINT.json` | success | 1.169 |  |
| 328 | mint | `Expressions/Expression_1/Expression_1_fromMINT.json` | success | 1.068 |  |
| 329 | mint | `Expressions/Expression_10/Expression_10_fromMINT.json` | success | 1.019 |  |
| 330 | mint | `Expressions/Expression_11/Expression_11_fromMINT.json` | success | 0.887 |  |
| 331 | mint | `Expressions/Expression_12/Expression_12_fromMINT.json` | fail | 0.175 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=26, E=49, components=1, cycle_rank=24; cycle-closing connection(s): channel_11, channel_13, channel_15, channel_17, channel_19, channel_21, channel_23, channel_25, channel_27, channel_29, channel_31, channel_33, channel_35, channel_37, channel_39, channel_41, channel_42, channel_43, channel_44, channel_45, channel_46, channel_47, channel_48, channel_49 |
| 332 | mint | `Expressions/Expression_13/Expression_13_fromMINT.json` | success | 0.937 |  |
| 333 | mint | `Expressions/Expression_14/Expression_14_fromMINT.json` | fail | 0.116 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=60, E=70, components=1, cycle_rank=11; cycle-closing connection(s): channel_15, channel_38, channel_62, channel_63, channel_64, channel_65, channel_66, channel_67, channel_68, channel_69, channel_70 |
| 334 | mint | `Expressions/Expression_15/Expression_15_fromMINT.json` | success | 1.242 |  |
| 335 | mint | `Expressions/Expression_2/Expression_2_fromMINT.json` | success | 0.971 |  |
| 336 | mint | `Expressions/Expression_3/Expression_3_fromMINT.json` | success | 1.019 |  |
| 337 | mint | `Expressions/Expression_4/Expression_4_fromMINT.json` | success | 1.034 |  |
| 338 | mint | `Expressions/Expression_5/Expression_5_fromMINT.json` | success | 1.033 |  |
| 339 | mint | `Expressions/Expression_6/Expression_6_fromMINT.json` | success | 1.076 |  |
| 340 | mint | `Expressions/Expression_7/Expression_7_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=11, E=19, components=1, cycle_rank=9; cycle-closing connection(s): channel_6, channel_8, channel_10, channel_12, channel_14, channel_16, channel_17, channel_18, channel_19 |
| 341 | mint | `Expressions/Expression_8/Expression_8_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=10, E=10, components=1, cycle_rank=1; cycle-closing connection(s): channel_7 |
| 342 | mint | `Expressions/Expression_9/Expression_9_fromMINT.json` | success | 1.036 |  |
| 343 | mint | `Ghissues/Issue_10/Issue_10_fromMINT.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=24, E=36, components=1, cycle_rank=13; cycle-closing connection(s): channel_20, channel_22, channel_23, channel_24, channel_26, channel_27, channel_28, channel_30, channel_31, channel_32, channel_34, channel_35, channel_36 |
| 344 | mint | `Ghissues/Issue_15/Issue_15_fromMINT.json` | success | 1.042 |  |
| 345 | mint | `Ghissues/Issue_2/Issue_2_fromMINT.json` | success | 0.875 |  |
| 346 | mint | `Ghissues/Issue_3/Issue_3_fromMINT.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=20, E=28, components=1, cycle_rank=9; cycle-closing connection(s): channel_18, channel_19, channel_20, channel_22, channel_23, channel_24, channel_26, channel_27, channel_28 |
| 347 | mint | `Ghissues/Issue_6/Issue_6_fromMINT.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=35, E=51, components=1, cycle_rank=17; cycle-closing connection(s): channel_26, channel_29, channel_30, channel_32, channel_33, channel_35, channel_36, channel_38, channel_39, channel_41, channel_42, channel_44, channel_45, channel_47, channel_48, channel_50, channel_51 |
| 348 | mint | `Ghissues/Issue_7/Issue_7_fromMINT.json` | fail | 0.181 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=44, E=52, components=1, cycle_rank=9; cycle-closing connection(s): channel_41, channel_43, channel_44, channel_45, channel_47, channel_48, channel_49, channel_50, channel_51 |
| 349 | mint | `Ghissues/Issue_8/Issue_8_fromMINT.json` | fail | 0.168 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=48, E=57, components=1, cycle_rank=10; cycle-closing connection(s): channel_45, channel_46, channel_47, channel_48, channel_49, channel_52, channel_54, channel_55, channel_56, channel_57 |
| 350 | mint | `Ghissues/Issue_9/Issue_9_fromMINT.json` | fail | 0.171 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=47, E=62, components=1, cycle_rank=16; cycle-closing connection(s): channel_32, channel_34, channel_36, channel_38, channel_40, channel_42, channel_44, channel_46, channel_48, channel_50, channel_52, channel_54, channel_56, channel_58, channel_60, channel_62 |
| 351 | mint | `Graph_Coverage/Tree_Fanin/Tree_Fanin_fromMINT.json` | success | 1.135 |  |
| 352 | mint | `Graph_Coverage/Tree_Fanout/Tree_Fanout_fromMINT.json` | success | 1.084 |  |
| 353 | mint | `Grid/Grid_03/Grid_03_fromMINT.json` | fail | 0.120 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=13, E=20, components=1, cycle_rank=8; cycle-closing connection(s): c5, c6, c10, c11, c15, c16, c18, c19 |
| 354 | mint | `Grid/Grid_04/Grid_04_fromMINT.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=20, E=34, components=1, cycle_rank=15; cycle-closing connection(s): c6, c7, c8, c13, c14, c15, c20, c21, c22, c27, c28, c29, c31, c32, c33 |
| 355 | mint | `Grid/Grid_05/Grid_05_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=29, E=52, components=1, cycle_rank=24; cycle-closing connection(s): c7, c8, c9, c10, c16, c17, c18, c19, c25, c26, c27, c28, c34, c35, c36, c37, c43, c44, c45, c46, c48, c49, c50, c51 |
| 356 | mint | `Grid/Grid_06/Grid_06_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=40, E=74, components=1, cycle_rank=35; cycle-closing connection(s): c8, c9, c10, c11, c12, c19, c20, c21, c22, c23, c30, c31, c32, c33, c34, c41, c42, c43, c44, c45, c52, c53, c54, c55, c56, c63, c64, c65, c66, c67, c69, c70, c71, c72, c73 |
| 357 | mint | `Grid/Grid_07/Grid_07_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=53, E=100, components=1, cycle_rank=48; cycle-closing connection(s): c9, c10, c11, c12, c13, c14, c22, c23, c24, c25, c26, c27, c35, c36, c37, c38, c39, c40, c48, c49, c50, c51, c52, c53, c61, c62, c63, c64, c65, c66, c74, c75, c76, c77, c78, c79, c87, c88, c89, c90, c91, c92, c94, c95, c96, c97, c98, c99 |
| 358 | mint | `Grid/Grid_08/Grid_08_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=68, E=130, components=1, cycle_rank=63; cycle-closing connection(s): c10, c11, c12, c13, c14, c15, c16, c25, c26, c27, c28, c29, c30, c31, c40, c41, c42, c43, c44, c45, c46, c55, c56, c57, c58, c59, c60, c61, c70, c71, c72, c73, c74, c75, c76, c85, c86, c87, c88, c89, c90, c91, c100, c101, c102, c103, c104, c105, c106, c115, c116, c117, c118, c119, c120, c121, c123, c124, c125, c126, c127, c128, c129 |
| 359 | mint | `Grid/Grid_09/Grid_09_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=85, E=164, components=1, cycle_rank=80; cycle-closing connection(s): c11, c12, c13, c14, c15, c16, c17, c18, c28, c29, c30, c31, c32, c33, c34, c35, c45, c46, c47, c48, c49, c50, c51, c52, c62, c63, c64, c65, c66, c67, c68, c69, c79, c80, c81, c82, c83, c84, c85, c86, c96, c97, c98, c99, c100, c101, c102, c103, c113, c114, c115, c116, c117, c118, c119, c120, c130, c131, c132, c133, c134, c135, c136, c137, c147, c148, c149, c150, c151, c152, c153, c154, c156, c157, c158, c159, c160, c161, c162, c163 |
| 360 | mint | `Grid/Grid_10/Grid_10_fromMINT.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=104, E=202, components=1, cycle_rank=99; cycle-closing connection(s): c12, c13, c14, c15, c16, c17, c18, c19, c20, c31, c32, c33, c34, c35, c36, c37, c38, c39, c50, c51, c52, c53, c54, c55, c56, c57, c58, c69, c70, c71, c72, c73, c74, c75, c76, c77, c88, c89, c90, c91, c92, c93, c94, c95, c96, c107, c108, c109, c110, c111, c112, c113, c114, c115, c126, c127, c128, c129, c130, c131, c132, c133, c134, c145, c146, c147, c148, c149, c150, c151, c152, c153, c164, c165, c166, c167, c168, c169, c170, c171, c172, c183, c184, c185, c186, c187, c188, c189, c190, c191, c193, c194, c195, c196, c197, c198, c199, c200, c201 |
| 361 | mint | `Grid/Grid_11/Grid_11_fromMINT.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=125, E=244, components=1, cycle_rank=120; cycle-closing connection(s): c13, c14, c15, c16, c17, c18, c19, c20, c21, c22, c34, c35, c36, c37, c38, c39, c40, c41, c42, c43, c55, c56, c57, c58, c59, c60, c61, c62, c63, c64, c76, c77, c78, c79, c80, c81, c82, c83, c84, c85, c97, c98, c99, c100, c101, c102, c103, c104, c105, c106, c118, c119, c120, c121, c122, c123, c124, c125, c126, c127, c139, c140, c141, c142, c143, c144, c145, c146, c147, c148, c160, c161, c162, c163, c164, c165, c166, c167, c168, c169, c181, c182, c183, c184, c185, c186, c187, c188, c189, c190, c202, c203, c204, c205, c206, c207, c208, c209, c210, c211, c223, c224, c225, c226, c227, c228, c229, c230, c231, c232, c234, c235, c236, c237, c238, c239, c240, c241, c242, c243 |
| 362 | mint | `Grid/Grid_12/Grid_12_fromMINT.json` | fail | 0.165 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=148, E=290, components=1, cycle_rank=143; cycle-closing connection(s): c14, c15, c16, c17, c18, c19, c20, c21, c22, c23, c24, c37, c38, c39, c40, c41, c42, c43, c44, c45, c46, c47, c60, c61, c62, c63, c64, c65, c66, c67, c68, c69, c70, c83, c84, c85, c86, c87, c88, c89, c90, c91, c92, c93, c106, c107, c108, c109, c110, c111, c112, c113, c114, c115, c116, c129, c130, c131, c132, c133, c134, c135, c136, c137, c138, c139, c152, c153, c154, c155, c156, c157, c158, c159, c160, c161, c162, c175, c176, c177, c178, c179, c180, c181, c182, c183, c184, c185, c198, c199, c200, c201, c202, c203, c204, c205, c206, c207, c208, c221, c222, c223, c224, c225, c226, c227, c228, c229, c230, c231, c244, c245, c246, c247, c248, c249, c250, c251, c252, c253, c254, c267, c268, c269, c270, c271, c272, c273, c274, c275, c276, c277, c279, c280, c281, c282, c283, c284, c285, c286, c287, c288, c289 |
| 363 | mint | `Grid/Grid_13/Grid_13_fromMINT.json` | fail | 0.168 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=173, E=340, components=1, cycle_rank=168; cycle-closing connection(s): c15, c16, c17, c18, c19, c20, c21, c22, c23, c24, c25, c26, c40, c41, c42, c43, c44, c45, c46, c47, c48, c49, c50, c51, c65, c66, c67, c68, c69, c70, c71, c72, c73, c74, c75, c76, c90, c91, c92, c93, c94, c95, c96, c97, c98, c99, c100, c101, c115, c116, c117, c118, c119, c120, c121, c122, c123, c124, c125, c126, c140, c141, c142, c143, c144, c145, c146, c147, c148, c149, c150, c151, c165, c166, c167, c168, c169, c170, c171, c172, c173, c174, c175, c176, c190, c191, c192, c193, c194, c195, c196, c197, c198, c199, c200, c201, c215, c216, c217, c218, c219, c220, c221, c222, c223, c224, c225, c226, c240, c241, c242, c243, c244, c245, c246, c247, c248, c249, c250, c251, c265, c266, c267, c268, c269, c270, c271, c272, c273, c274, c275, c276, c290, c291, c292, c293, c294, c295, c296, c297, c298, c299, c300, c301, c315, c316, c317, c318, c319, c320, c321, c322, c323, c324, c325, c326, c328, c329, c330, c331, c332, c333, c334, c335, c336, c337, c338, c339 |
| 364 | mint | `Grid/Grid_14/Grid_14_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=200, E=394, components=1, cycle_rank=195; cycle-closing connection(s): c16, c17, c18, c19, c20, c21, c22, c23, c24, c25, c26, c27, c28, c43, c44, c45, c46, c47, c48, c49, c50, c51, c52, c53, c54, c55, c70, c71, c72, c73, c74, c75, c76, c77, c78, c79, c80, c81, c82, c97, c98, c99, c100, c101, c102, c103, c104, c105, c106, c107, c108, c109, c124, c125, c126, c127, c128, c129, c130, c131, c132, c133, c134, c135, c136, c151, c152, c153, c154, c155, c156, c157, c158, c159, c160, c161, c162, c163, c178, c179, c180, c181, c182, c183, c184, c185, c186, c187, c188, c189, c190, c205, c206, c207, c208, c209, c210, c211, c212, c213, c214, c215, c216, c217, c232, c233, c234, c235, c236, c237, c238, c239, c240, c241, c242, c243, c244, c259, c260, c261, c262, c263, c264, c265, c266, c267, c268, c269, c270, c271, c286, c287, c288, c289, c290, c291, c292, c293, c294, c295, c296, c297, c298, c313, c314, c315, c316, c317, c318, c319, c320, c321, c322, c323, c324, c325, c340, c341, c342, c343, c344, c345, c346, c347, c348, c349, c350, c351, c352, c367, c368, c369, c370, c371, c372, c373, c374, c375, c376, c377, c378, c379, c381, c382, c383, c384, c385, c386, c387, c388, c389, c390, c391, c392, c393 |
| 365 | mint | `Grid/Grid_15/Grid_15_fromMINT.json` | fail | 0.174 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=229, E=452, components=1, cycle_rank=224; cycle-closing connection(s): c17, c18, c19, c20, c21, c22, c23, c24, c25, c26, c27, c28, c29, c30, c46, c47, c48, c49, c50, c51, c52, c53, c54, c55, c56, c57, c58, c59, c75, c76, c77, c78, c79, c80, c81, c82, c83, c84, c85, c86, c87, c88, c104, c105, c106, c107, c108, c109, c110, c111, c112, c113, c114, c115, c116, c117, c133, c134, c135, c136, c137, c138, c139, c140, c141, c142, c143, c144, c145, c146, c162, c163, c164, c165, c166, c167, c168, c169, c170, c171, c172, c173, c174, c175, c191, c192, c193, c194, c195, c196, c197, c198, c199, c200, c201, c202, c203, c204, c220, c221, c222, c223, c224, c225, c226, c227, c228, c229, c230, c231, c232, c233, c249, c250, c251, c252, c253, c254, c255, c256, c257, c258, c259, c260, c261, c262, c278, c279, c280, c281, c282, c283, c284, c285, c286, c287, c288, c289, c290, c291, c307, c308, c309, c310, c311, c312, c313, c314, c315, c316, c317, c318, c319, c320, c336, c337, c338, c339, c340, c341, c342, c343, c344, c345, c346, c347, c348, c349, c365, c366, c367, c368, c369, c370, c371, c372, c373, c374, c375, c376, c377, c378, c394, c395, c396, c397, c398, c399, c400, c401, c402, c403, c404, c405, c406, c407, c423, c424, c425, c426, c427, c428, c429, c430, c431, c432, c433, c434, c435, c436, c438, c439, c440, c441, c442, c443, c444, c445, c446, c447, c448, c449, c450, c451 |
| 366 | mint | `Grid/Grid_16/Grid_16_fromMINT.json` | fail | 0.174 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=260, E=514, components=1, cycle_rank=255; cycle-closing connection(s): c18, c19, c20, c21, c22, c23, c24, c25, c26, c27, c28, c29, c30, c31, c32, c49, c50, c51, c52, c53, c54, c55, c56, c57, c58, c59, c60, c61, c62, c63, c80, c81, c82, c83, c84, c85, c86, c87, c88, c89, c90, c91, c92, c93, c94, c111, c112, c113, c114, c115, c116, c117, c118, c119, c120, c121, c122, c123, c124, c125, c142, c143, c144, c145, c146, c147, c148, c149, c150, c151, c152, c153, c154, c155, c156, c173, c174, c175, c176, c177, c178, c179, c180, c181, c182, c183, c184, c185, c186, c187, c204, c205, c206, c207, c208, c209, c210, c211, c212, c213, c214, c215, c216, c217, c218, c235, c236, c237, c238, c239, c240, c241, c242, c243, c244, c245, c246, c247, c248, c249, c266, c267, c268, c269, c270, c271, c272, c273, c274, c275, c276, c277, c278, c279, c280, c297, c298, c299, c300, c301, c302, c303, c304, c305, c306, c307, c308, c309, c310, c311, c328, c329, c330, c331, c332, c333, c334, c335, c336, c337, c338, c339, c340, c341, c342, c359, c360, c361, c362, c363, c364, c365, c366, c367, c368, c369, c370, c371, c372, c373, c390, c391, c392, c393, c394, c395, c396, c397, c398, c399, c400, c401, c402, c403, c404, c421, c422, c423, c424, c425, c426, c427, c428, c429, c430, c431, c432, c433, c434, c435, c452, c453, c454, c455, c456, c457, c458, c459, c460, c461, c462, c463, c464, c465, c466, c483, c484, c485, c486, c487, c488, c489, c490, c491, c492, c493, c494, c495, c496, c497, c499, c500, c501, c502, c503, c504, c505, c506, c507, c508, c509, c510, c511, c512, c513 |
| 367 | mint | `Literature_Benchmarks/Device_1_Sc_Rna_Seq/Device_1_Sc_Rna_Seq_fromMINT.json` | fail | 0.180 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=9, E=9, components=1, cycle_rank=1; cycle-closing connection(s): channel_8 |
| 368 | mint | `Literature_Benchmarks/Device_2_Artificial_Cells/Device_2_Artificial_Cells_fromMINT.json` | success | 1.175 |  |
| 369 | mint | `Literature_Benchmarks/Device_4_Molecular_Diagnostics/Device_4_Molecular_Diagnostics_fromMINT.json` | success | 1.080 |  |
| 370 | mint | `Literature_Benchmarks/Device_5_Bacteria_Diagnostics/Device_5_Bacteria_Diagnostics_fromMINT.json` | success | 1.383 |  |
| 371 | mint | `Literature_Benchmarks/Device_6_Organic_Chemical_Synthesis/Device_6_Organic_Chemical_Synthesis_fromMINT.json` | success | 2.333 |  |
| 372 | mint | `Literature_Benchmarks/Device_7_Enzyme_Screening/Device_7_Enzyme_Screening_fromMINT.json` | success | 28.139 |  |
| 373 | mint | `Mars/Antibiotic_Resistance/Antibiotic_Resistance_fromMINT.json` | success | 1.172 |  |
| 374 | mint | `Mars/Cell_Lysis/Cell_Lysis_fromMINT.json` | success | 1.075 |  |
| 375 | mint | `Mars/Dna_Digest/Dna_Digest_fromMINT.json` | success | 1.448 |  |
| 376 | mint | `Mars/Fluorescence/Fluorescence_fromMINT.json` | success | 1.181 |  |
| 377 | mint | `Mars/Ligation/Ligation_fromMINT.json` | success | 2.329 |  |
| 378 | mint | `Mars/Pcr/Pcr_fromMINT.json` | success | 1.121 |  |
| 379 | mint | `Mars/Pre_Processor_Dump/Pre_Processor_Dump_fromMINT.json` | success | 0.918 |  |
| 380 | mint | `Mars/Sorting/Sorting_fromMINT.json` | success | 0.975 |  |
| 381 | mint | `Mars/Transformation/Transformation_fromMINT.json` | success | 1.123 |  |
| 382 | mint | `Primitive/Capacitance_Sensor/Capacitance_Sensor_fromMINT.json` | success | 0.869 |  |
| 383 | mint | `Primitive/Curved_Mixer/Curved_Mixer_fromMINT.json` | success | 0.880 |  |
| 384 | mint | `Primitive/Diamond_Chamber/Diamond_Chamber_fromMINT.json` | success | 0.869 |  |
| 385 | mint | `Primitive/Droplet_Generator_T/Droplet_Generator_T_fromMINT.json` | success | 0.873 |  |
| 386 | mint | `Primitive/Droplet_Merger/Droplet_Merger_fromMINT.json` | success | 0.883 |  |
| 387 | mint | `Primitive/Droplet_Sorter/Droplet_Sorter_fromMINT.json` | success | 0.931 |  |
| 388 | mint | `Primitive/Filter/Filter_fromMINT.json` | success | 0.889 |  |
| 389 | mint | `Primitive/Flow_Focus_Droplet_Generator/Flow_Focus_Droplet_Generator_fromMINT.json` | success | 0.892 |  |
| 390 | mint | `Primitive/Gradient_Generator/Gradient_Generator_fromMINT.json` | success | 0.931 |  |
| 391 | mint | `Primitive/Long_Cell_Trap/Long_Cell_Trap_fromMINT.json` | success | 0.874 |  |
| 392 | mint | `Primitive/Mixer/Mixer_fromMINT.json` | success | 0.876 |  |
| 393 | mint | `Primitive/Mixer_To_Mixer/Mixer_To_Mixer_fromMINT.json` | fail | 0.130 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=2, E=2, components=1, cycle_rank=1; cycle-closing connection(s): c2 |
| 394 | mint | `Primitive/MUX/MUX_fromMINT.json` | success | 1.178 |  |
| 395 | mint | `Primitive/MUX_3d/MUX_3d_fromMINT.json` | success | 0.968 |  |
| 396 | mint | `Primitive/Node/Node_fromMINT.json` | success | 0.870 |  |
| 397 | mint | `Primitive/Nozzle_Droplet_Generator/Nozzle_Droplet_Generator_fromMINT.json` | success | 0.918 |  |
| 398 | mint | `Primitive/Picoinjector/Picoinjector_fromMINT.json` | success | 0.920 |  |
| 399 | mint | `Primitive/Pump/Pump_fromMINT.json` | success | 7.701 |  |
| 400 | mint | `Primitive/Pump_3d/Pump_3d_fromMINT.json` | success | 0.874 |  |
| 401 | mint | `Primitive/Rotary_Mixer/Rotary_Mixer_fromMINT.json` | success | 0.870 |  |
| 402 | mint | `Primitive/Splitter/Splitter_fromMINT.json` | success | 0.924 |  |
| 403 | mint | `Primitive/Square_Cell_Trap/Square_Cell_Trap_fromMINT.json` | success | 0.920 |  |
| 404 | mint | `Primitive/Transposer/Transposer_fromMINT.json` | success | 0.926 |  |
| 405 | mint | `Primitive/Tree/Tree_fromMINT.json` | success | 0.919 |  |
| 406 | mint | `Primitive/Valve/Valve_fromMINT.json` | success | 0.870 |  |
| 407 | mint | `Primitive/Y_Tree/Y_Tree_fromMINT.json` | success | 0.922 |  |
| 408 | mint | `Protocols/Cell_Sorting/Cell_Sorting_fromMINT.json` | success | 0.881 |  |
| 409 | mint | `Protocols/Directed_Evolution/Directed_Evolution_fromMINT.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=27, E=42, components=1, cycle_rank=16; cycle-closing connection(s): channel_23, channel_26, channel_27, channel_28, channel_29, channel_30, channel_32, channel_33, channel_34, channel_35, channel_36, channel_38, channel_39, channel_40, channel_41, channel_42 |
| 410 | mint | `Technology_Mapping/Cycle/Cycle_fromMINT.json` | success | 0.931 |  |
| 411 | mint | `Technology_Mapping/Instance_Mapping/Instance_Mapping_fromMINT.json` | success | 0.869 |  |
| 412 | mint | `Technology_Mapping/N_Greater_M_Map/N_Greater_M_Map_fromMINT.json` | success | 1.076 |  |
| 413 | mint | `Technology_Mapping/N_Less_M_Map/N_Less_M_Map_fromMINT.json` | success | 1.029 |  |
| 414 | mint | `Technology_Mapping/One_To_One_Mapping/One_To_One_Mapping_fromMINT.json` | success | 0.888 |  |
| 415 | mint | `Technology_Mapping/Tree_Bus/Tree_Bus_fromMINT.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=11, E=18, components=1, cycle_rank=8; cycle-closing connection(s): channel_11, channel_12, channel_13, channel_14, channel_15, channel_16, channel_17, channel_18 |
| 416 | mint | `Technology_Mapping/Tree_Fanin_Mapping/Tree_Fanin_Mapping_fromMINT.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=10, E=17, components=1, cycle_rank=8; cycle-closing connection(s): channel_10, channel_11, channel_12, channel_13, channel_14, channel_15, channel_16, channel_17 |
| 417 | mint | `Technology_Mapping/Tree_Fanout_Mapping_1/Tree_Fanout_Mapping_1_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=10, E=17, components=1, cycle_rank=8; cycle-closing connection(s): channel_10, channel_11, channel_12, channel_13, channel_14, channel_15, channel_16, channel_17 |
| 418 | mint | `Technology_Mapping/Tree_Fanout_Mapping_2/Tree_Fanout_Mapping_2_fromMINT.json` | success | 1.075 |  |
| 419 | mint | `Technology_Mapping/Tree_Fanout_Mapping_3/Tree_Fanout_Mapping_3_fromMINT.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=10, E=17, components=1, cycle_rank=8; cycle-closing connection(s): channel_10, channel_11, channel_12, channel_13, channel_14, channel_15, channel_16, channel_17 |
| 420 | mint | `Technology_Mapping/Tree_Storage_Bus_Mapping/Tree_Storage_Bus_Mapping_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=12, E=37, components=1, cycle_rank=26; cycle-closing connection(s): channel_11, channel_12, channel_13, channel_14, channel_15, channel_16, channel_17, channel_18, channel_19, channel_21, channel_22, channel_23, channel_24, channel_25, channel_26, channel_27, channel_28, channel_29, channel_30, channel_31, channel_32, channel_33, channel_34, channel_35, channel_36, channel_37 |
| 421 | mint | `Transport_Networks/Distribute_Network_Examples/Distribute_Network_Examples_fromMINT.json` | timeout | 1800.021 | exceeded 1800s |
| 422 | mint | `Transport_Networks/One_To_8/One_To_8_fromMINT.json` | timeout | 1800.011 | exceeded 1800s |
| 423 | mint | `Transport_Networks/One_To_One/One_To_One_fromMINT.json` | success | 0.868 |  |
| 424 | quick | `constrain_mixer/constrain_mixer_fromLFR.json` | success | 0.881 |  |
| 425 | quick | `constrain_pump/constrain_pump_fromLFR.json` | success | 7.538 |  |
| 426 | quick | `diy_with_mixer_demo/diy_with_mixer_demo_fromLFR.json` | success | 0.921 |  |
| 427 | quick | `DIYcomponent/DIYcomponent_fromLFR.json` | success | 0.924 |  |
| 428 | quick | `droplet_generator/droplet_generator_fromLFR.json` | success | 0.919 |  |
| 429 | quick | `flow_and_control_demo/flow_and_control_demo_fromLFR.json` | success | 1.127 |  |
| 430 | quick | `flow_and_control_demo/flow_and_control_demo_fromMINT.json` | success | 1.119 |  |
| 431 | quick | `flow_only_demo/flow_only_demo_fromLFR.json` | success | 0.883 |  |
| 432 | quick | `flow_only_demo/flow_only_demo_fromMINT.json` | success | 0.877 |  |
| 433 | quick | `import_droplet_reaction/import_droplet_reaction_fromLFR.json` | success | 2.043 |  |
| 434 | quick | `import_mixer_and_incubator/import_mixer_and_incubator_fromLFR.json` | success | 0.933 |  |
| 435 | quick | `import_parallel_premix/import_parallel_premix_fromLFR.json` | success | 1.096 |  |
| 436 | quick | `incubator/incubator_fromLFR.json` | success | 0.871 |  |
| 437 | quick | `long_mixer/long_mixer_fromLFR.json` | success | 0.877 |  |
| 438 | quick | `long_mixer/long_mixer_fromMINT.json` | success | 0.928 |  |
| 439 | quick | `map_droplet/map_droplet_fromLFR.json` | success | 0.933 |  |
| 440 | quick | `map_mixer/map_mixer_fromLFR.json` | success | 0.891 |  |
| 441 | quick | `map_mux/map_mux_fromLFR.json` | success | 1.187 |  |
| 442 | quick | `map_via/map_via_fromLFR.json` | success | 0.890 |  |
| 443 | quick | `map_ytree/map_ytree_fromLFR.json` | success | 0.924 |  |
| 444 | quick | `multi_mixer/multi_mixer_fromLFR.json` | success | 0.973 |  |
| 445 | quick | `multi_mixer/multi_mixer_fromMINT.json` | success | 0.983 |  |
| 446 | quick | `Super_MUX_8/Super_MUX_8_fromMINT.json` | success | 1.626 |  |
| 447 | quick | `test_device_v1_MUX_1to4/test_device_v1_MUX_1to4_fromLFR.json` | success | 6.949 |  |
| 448 | quick | `test_device_v1_MUX_4to1/test_device_v1_MUX_4to1_fromLFR.json` | success | 10.368 |  |
| 449 | quick | `test_device_v2_2MUX/test_device_v2_2MUX_fromLFR.json` | success | 1.583 |  |
| 450 | quick | `test_device_v3_2MUX_fork/test_device_v3_2MUX_fork_fromLFR.json` | success | 1.570 |  |
| 451 | quick | `test_DIY_crossing/test_DIY_crossing_fromLFR.json` | success | 0.931 |  |
| 452 | quick | `test_DIY_fork/test_DIY_fork_fromLFR.json` | success | 0.879 |  |
| 453 | quick | `three_in_mixer/three_in_mixer_fromLFR.json` | success | 0.919 |  |
| 454 | quick | `two_in_mixer/two_in_mixer_fromLFR.json` | success | 0.869 |  |
