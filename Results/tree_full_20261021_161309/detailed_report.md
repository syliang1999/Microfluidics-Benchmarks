# TREE full benchmark report

- Per-case hard timeout: **1800 seconds**
- Workers: **12**
- Discovered: **454**
- Completed: **171**
- Success: **117**
- Fail: **54**
- Timeout: **0**

| # | Suite | Case | Status | Wall time (s) | Reason |
|---:|---|---|---|---:|---|
| 1 | lfr | `CIDAR_Lab_Past_Devices/Chemostat_Chip/Chemostat_Chip_fromLFR.json` | fail | 0.230 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=36, E=50, components=1, cycle_rank=15; cycle-closing connection(s): channel_22, channel_29, channel_30, channel_31, channel_32, channel_33, channel_34, channel_43, channel_44, channel_45, channel_46, channel_47, channel_48, channel_49, channel_50 |
| 2 | lfr | `CIDAR_Lab_Past_Devices/Dna_Synthesizer/Dna_Synthesizer_fromLFR.json` | fail | 0.222 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=65, E=74, components=1, cycle_rank=10; cycle-closing connection(s): channel_60, channel_64, channel_67, channel_68, channel_69, channel_70, channel_71, channel_72, channel_73, channel_74 |
| 3 | lfr | `CIDAR_Lab_Past_Devices/Dual_Lane_Droplet/Dual_Lane_Droplet_fromLFR.json` | success | 1.831 |  |
| 4 | lfr | `CIDAR_Lab_Past_Devices/Genetic_Clock_Testing_Tool/Genetic_Clock_Testing_Tool_fromLFR.json` | fail | 0.227 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=9, E=10, components=1, cycle_rank=2; cycle-closing connection(s): channel_9, channel_10 |
| 5 | lfr | `CIDAR_Lab_Past_Devices/Glycoform/Glycoform_fromLFR.json` | success | 1.380 |  |
| 6 | lfr | `CIDAR_Lab_Past_Devices/Grad_Cells/Grad_Cells_fromLFR.json` | fail | 0.232 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=9, E=12, components=1, cycle_rank=4; cycle-closing connection(s): channel_4, channel_6, channel_8, channel_12 |
| 7 | lfr | `CIDAR_Lab_Past_Devices/Gradient/Gradient_fromLFR.json` | fail | 0.223 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=48, E=57, components=1, cycle_rank=10; cycle-closing connection(s): channel_40, channel_42, channel_44, channel_46, channel_50, channel_52, channel_53, channel_54, channel_55, channel_56 |
| 8 | lfr | `CIDAR_Lab_Past_Devices/Hasty_Cell_Traps/Hasty_Cell_Traps_fromLFR.json` | fail | 0.228 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=6, E=8, components=1, cycle_rank=3; cycle-closing connection(s): channel_4, channel_6, channel_8 |
| 9 | lfr | `CIDAR_Lab_Past_Devices/Hmlp_Dual_Bank/Hmlp_Dual_Bank_fromLFR.json` | fail | 0.225 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=43, E=63, components=1, cycle_rank=21; cycle-closing connection(s): channel_36, channel_38, channel_40, channel_41, channel_42, channel_45, channel_46, channel_47, channel_48, channel_50, channel_51, channel_53, channel_54, channel_55, channel_56, channel_57, channel_58, channel_59, channel_60, channel_62, channel_63 |
| 10 | lfr | `CIDAR_Lab_Past_Devices/Incubator/Incubator_fromLFR.json` | fail | 0.220 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=22, E=26, components=1, cycle_rank=5; cycle-closing connection(s): channel_20, channel_21, channel_24, channel_25, channel_26 |
| 11 | lfr | `CIDAR_Lab_Past_Devices/Inlet_16/Inlet_16_fromLFR.json` | fail | 0.219 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=57, E=73, components=1, cycle_rank=17; cycle-closing connection(s): channel_49, channel_50, channel_51, channel_54, channel_57, channel_61, channel_62, channel_64, channel_65, channel_66, channel_67, channel_68, channel_69, channel_70, channel_71, channel_72, channel_73 |
| 12 | lfr | `CIDAR_Lab_Past_Devices/Kinetics/Kinetics_fromLFR.json` | success | 1.222 |  |
| 13 | lfr | `CIDAR_Lab_Past_Devices/Logic_04/Logic_04_fromLFR.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=31, E=45, components=1, cycle_rank=15; cycle-closing connection(s): channel_21, channel_22, channel_23, channel_26, channel_29, channel_30, channel_31, channel_32, channel_33, channel_34, channel_38, channel_39, channel_40, channel_41, channel_44 |
| 14 | lfr | `CIDAR_Lab_Past_Devices/Mfd_005_Chip/Mfd_005_Chip_fromLFR.json` | success | 1.323 |  |
| 15 | lfr | `CIDAR_Lab_Past_Devices/Microalgal_Bioassay/Microalgal_Bioassay_fromLFR.json` | fail | 0.267 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=11, E=14, components=1, cycle_rank=4; cycle-closing connection(s): channel_9, channel_10, channel_11, channel_12 |
| 16 | lfr | `CIDAR_Lab_Past_Devices/Microdroplet/Microdroplet_fromLFR.json` | fail | 0.269 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=22, E=27, components=1, cycle_rank=6; cycle-closing connection(s): channel_19, channel_21, channel_22, channel_25, channel_26, channel_27 |
| 17 | lfr | `CIDAR_Lab_Past_Devices/Microreactor/Microreactor_fromLFR.json` | fail | 0.218 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=8, E=10, components=1, cycle_rank=3; cycle-closing connection(s): channel_7, channel_8, channel_10 |
| 18 | lfr | `CIDAR_Lab_Past_Devices/Mix_Incubate_Express/Mix_Incubate_Express_fromLFR.json` | success | 1.121 |  |
| 19 | lfr | `CIDAR_Lab_Past_Devices/Multi_Input/Multi_Input_fromLFR.json` | fail | 0.218 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=17, E=22, components=1, cycle_rank=6; cycle-closing connection(s): channel_14, channel_15, channel_19, channel_20, channel_21, channel_22 |
| 20 | lfr | `CIDAR_Lab_Past_Devices/MUX_96_Chambers/MUX_96_Chambers_fromLFR.json` | fail | 0.217 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=146, E=240, components=1, cycle_rank=95; cycle-closing connection(s): channel_52, channel_54, channel_56, channel_58, channel_60, channel_62, channel_64, channel_66, channel_68, channel_70, channel_72, channel_74, channel_76, channel_78, channel_80, channel_82, channel_84, channel_86, channel_88, channel_90, channel_92, channel_94, channel_96, channel_98, channel_100, channel_102, channel_104, channel_106, channel_108, channel_110, channel_112, channel_114, channel_116, channel_118, channel_120, channel_122, channel_124, channel_126, channel_128, channel_130, channel_132, channel_134, channel_136, channel_138, channel_140, channel_142, channel_144, channel_146, channel_148, channel_150, channel_152, channel_154, channel_156, channel_158, channel_160, channel_162, channel_164, channel_166, channel_168, channel_170, channel_172, channel_174, channel_176, channel_178, channel_210, channel_211, channel_212, channel_213, channel_214, channel_215, channel_216, channel_217, channel_218, channel_219, channel_220, channel_221, channel_222, channel_223, channel_224, channel_225, channel_226, channel_227, channel_228, channel_229, channel_230, channel_231, channel_232, channel_233, channel_234, channel_235, channel_236, channel_237, channel_238, channel_239, channel_240 |
| 21 | lfr | `CIDAR_Lab_Past_Devices/Net_MUX/Net_MUX_fromLFR.json` | fail | 0.217 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=32, E=50, components=1, cycle_rank=19; cycle-closing connection(s): channel_15, channel_18, channel_20, channel_21, channel_25, channel_26, channel_27, channel_28, channel_30, channel_31, channel_34, channel_37, channel_40, channel_41, channel_42, channel_43, channel_45, channel_47, channel_49 |
| 22 | lfr | `CIDAR_Lab_Past_Devices/Nine_To_One_MUX/Nine_To_One_MUX_fromLFR.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=28, E=35, components=1, cycle_rank=8; cycle-closing connection(s): channel_25, channel_27, channel_29, channel_31, channel_32, channel_33, channel_34, channel_35 |
| 23 | lfr | `CIDAR_Lab_Past_Devices/Number_Declarations/Number_Declarations_fromLFR.json` | success | 0.971 |  |
| 24 | lfr | `CIDAR_Lab_Past_Devices/Olfactory/Olfactory_fromLFR.json` | fail | 0.219 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=13, E=16, components=1, cycle_rank=4; cycle-closing connection(s): channel_12, channel_14, channel_15, channel_16 |
| 25 | lfr | `CIDAR_Lab_Past_Devices/Pump_Passthrough/Pump_Passthrough_fromLFR.json` | success | 0.719 |  |
| 26 | lfr | `CIDAR_Lab_Past_Devices/Ring/Ring_fromLFR.json` | success | 1.121 |  |
| 27 | lfr | `CIDAR_Lab_Past_Devices/Root_Chip/Root_Chip_fromLFR.json` | fail | 0.168 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=22, E=23, components=1, cycle_rank=2; cycle-closing connection(s): channel_22, channel_23 |
| 28 | lfr | `CIDAR_Lab_Past_Devices/Rotary_16/Rotary_16_fromLFR.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=63, E=93, components=1, cycle_rank=31; cycle-closing connection(s): channel_34, channel_35, channel_36, channel_37, channel_38, channel_39, channel_52, channel_53, channel_55, channel_56, channel_57, channel_58, channel_59, channel_60, channel_70, channel_73, channel_74, channel_75, channel_77, channel_78, channel_81, channel_82, channel_84, channel_85, channel_86, channel_87, channel_88, channel_89, channel_90, channel_91, channel_93 |
| 29 | lfr | `CIDAR_Lab_Past_Devices/Rotary_Cells/Rotary_Cells_fromLFR.json` | fail | 0.216 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=15, E=20, components=1, cycle_rank=6; cycle-closing connection(s): channel_4, channel_6, channel_8, channel_18, channel_19, channel_20 |
| 30 | lfr | `CIDAR_Lab_Past_Devices/Seeding/Seeding_fromLFR.json` | fail | 0.168 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=23, E=38, components=1, cycle_rank=16; cycle-closing connection(s): channel_4, channel_6, channel_8, channel_10, channel_14, channel_16, channel_18, channel_20, channel_22, channel_29, channel_30, channel_31, channel_32, channel_33, channel_37, channel_38 |
| 31 | lfr | `CIDAR_Lab_Past_Devices/Three_Reagent_Mix/Three_Reagent_Mix_fromLFR.json` | fail | 0.216 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=9, E=10, components=1, cycle_rank=2; cycle-closing connection(s): channel_9, channel_10 |
| 32 | lfr | `COVID/Aj_Rtpcr_8_Primer/Aj_Rtpcr_8_Primer_fromLFR.json` | fail | 0.216 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=38, E=48, components=1, cycle_rank=11; cycle-closing connection(s): channel_21, channel_28, channel_31, channel_35, channel_36, channel_38, channel_43, channel_44, channel_45, channel_47, channel_48 |
| 33 | lfr | `COVID/Arize/Arize_fromLFR.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=39, E=44, components=1, cycle_rank=6; cycle-closing connection(s): channel_22, channel_23, channel_32, channel_36, channel_37, channel_38 |
| 34 | lfr | `COVID/Covid_Crispr/Covid_Crispr_fromLFR.json` | success | 1.017 |  |
| 35 | lfr | `COVID/Crispr/Crispr_fromLFR.json` | success | 1.170 |  |
| 36 | lfr | `COVID/Detectr/Detectr_fromLFR.json` | success | 1.421 |  |
| 37 | lfr | `COVID/Elisa/Elisa_fromLFR.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=8, E=8, components=1, cycle_rank=1; cycle-closing connection(s): channel_8 |
| 38 | lfr | `COVID/Gel_Electrophoresis/Gel_Electrophoresis_fromLFR.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=12, E=14, components=1, cycle_rank=3; cycle-closing connection(s): channel_9, channel_12, channel_13 |
| 39 | lfr | `COVID/Hybri_Detect/Hybri_Detect_fromLFR.json` | success | 1.120 |  |
| 40 | lfr | `COVID/Part_1_Rna_Prep/Part_1_Rna_Prep_fromLFR.json` | success | 1.170 |  |
| 41 | lfr | `COVID/Part_2_Rt_Step/Part_2_Rt_Step_fromLFR.json` | success | 1.069 |  |
| 42 | lfr | `COVID/Part_3_Gel/Part_3_Gel_fromLFR.json` | success | 1.221 |  |
| 43 | lfr | `COVID/Rt_Pcr/Rt_Pcr_fromLFR.json` | success | 0.969 |  |
| 44 | lfr | `Distribute_Expressions/And_Annotation_Test/And_Annotation_Test_fromLFR.json` | success | 3.475 |  |
| 45 | lfr | `Distribute_Expressions/Dist_Expression_1/Dist_Expression_1_fromLFR.json` | success | 0.922 |  |
| 46 | lfr | `Distribute_Expressions/Dist_Expression_2/Dist_Expression_2_fromLFR.json` | success | 1.019 |  |
| 47 | lfr | `Distribute_Expressions/Dist_Expression_3/Dist_Expression_3_fromLFR.json` | success | 0.968 |  |
| 48 | lfr | `Distribute_Library/Cell_Traps_4/Cell_Traps_4_fromLFR.json` | success | 0.869 |  |
| 49 | lfr | `Distribute_Library/Hv_Storage_Grid_04/Hv_Storage_Grid_04_fromLFR.json` | success | 0.921 |  |
| 50 | lfr | `Distribute_Library/Hv_Storage_Grid_08/Hv_Storage_Grid_08_fromLFR.json` | success | 0.971 |  |
| 51 | lfr | `Distribute_Library/Hv_Storage_Grid_16/Hv_Storage_Grid_16_fromLFR.json` | success | 0.921 |  |
| 52 | lfr | `Distribute_Library/Hv_Storage_Grid_32/Hv_Storage_Grid_32_fromLFR.json` | success | 0.920 |  |
| 53 | lfr | `Distribute_Library/Hv_Storage_Grid_64/Hv_Storage_Grid_64_fromLFR.json` | success | 0.924 |  |
| 54 | lfr | `Distribute_Library/MUX_02_In/MUX_02_In_fromLFR.json` | success | 1.372 |  |
| 55 | lfr | `Distribute_Library/MUX_02_Out/MUX_02_Out_fromLFR.json` | success | 1.371 |  |
| 56 | lfr | `Distribute_Library/MUX_04_In/MUX_04_In_fromLFR.json` | success | 10.455 |  |
| 57 | lfr | `Distribute_Library/MUX_04_Out/MUX_04_Out_fromLFR.json` | success | 7.139 |  |
| 66 | lfr | `Distribute_Library/Single_Storage_Grid_01/Single_Storage_Grid_01_fromLFR.json` | success | 0.919 |  |
| 67 | lfr | `Distribute_Library/Single_Storage_Grid_02/Single_Storage_Grid_02_fromLFR.json` | success | 0.870 |  |
| 68 | lfr | `Distribute_Library/Single_Storage_Grid_04/Single_Storage_Grid_04_fromLFR.json` | success | 0.868 |  |
| 69 | lfr | `Distribute_Library/Single_Storage_Grid_08/Single_Storage_Grid_08_fromLFR.json` | success | 0.869 |  |
| 70 | lfr | `Distribute_Library/Single_Storage_Grid_16/Single_Storage_Grid_16_fromLFR.json` | success | 0.868 |  |
| 71 | lfr | `Distribute_Library/Single_Storage_Grid_32/Single_Storage_Grid_32_fromLFR.json` | success | 0.869 |  |
| 72 | lfr | `Distribute_Library/Single_Storage_Grid_64/Single_Storage_Grid_64_fromLFR.json` | success | 0.866 |  |
| 73 | lfr | `Distribute_Library/Transposer_02/Transposer_02_fromLFR.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=4, E=4, components=1, cycle_rank=1; cycle-closing connection(s): channel_4 |
| 74 | lfr | `Distribute_Library/Transposer_03/Transposer_03_fromLFR.json` | fail | 0.169 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=6, E=8, components=1, cycle_rank=3; cycle-closing connection(s): channel_5, channel_6, channel_8 |
| 75 | lfr | `Distribute_Library/Transposer_04/Transposer_04_fromLFR.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=23, E=35, components=1, cycle_rank=13; cycle-closing connection(s): channel_15, channel_16, channel_20, channel_21, channel_22, channel_26, channel_28, channel_29, channel_30, channel_31, channel_32, channel_33, channel_34 |
| 76 | lfr | `Distribute_Library/Transposer_08/Transposer_08_fromLFR.json` | success | 0.820 |  |
| 77 | lfr | `Distribute_Library/Transposer_16/Transposer_16_fromLFR.json` | success | 0.868 |  |
| 78 | lfr | `Distribute_Library/Transposer_32/Transposer_32_fromLFR.json` | success | 0.869 |  |
| 79 | lfr | `Distribute_Library/Transposer_64/Transposer_64_fromLFR.json` | success | 0.918 |  |
| 80 | lfr | `Drop_Ref/Droplet_Generator_1/Droplet_Generator_1_fromLFR.json` | success | 0.920 |  |
| 81 | lfr | `Drop_Ref/Droplet_Generator_2/Droplet_Generator_2_fromLFR.json` | success | 1.219 |  |
| 82 | lfr | `Drop_Ref/Droplet_Generator_3/Droplet_Generator_3_fromLFR.json` | fail | 0.165 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=20, E=24, components=1, cycle_rank=5; cycle-closing connection(s): channel_17, channel_19, channel_22, channel_23, channel_24 |
| 83 | lfr | `Drop_Ref/Droplet_Generator_4/Droplet_Generator_4_fromLFR.json` | fail | 0.169 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=12, E=12, components=1, cycle_rank=1; cycle-closing connection(s): channel_12 |
| 84 | lfr | `Drop_Ref/Dropx_Test_1/Dropx_Test_1_fromLFR.json` | success | 0.869 |  |
| 85 | lfr | `Drop_Ref/Dropx_Test_2/Dropx_Test_2_fromLFR.json` | success | 1.018 |  |
| 86 | lfr | `Drop_Ref/Dropx_Test_3/Dropx_Test_3_fromLFR.json` | success | 1.069 |  |
| 87 | lfr | `Drop_Ref/Dropx_Test_4/Dropx_Test_4_fromLFR.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=8, E=8, components=1, cycle_rank=1; cycle-closing connection(s): channel_8 |
| 88 | lfr | `Drop_Ref/Dx_1/Dx_1_fromLFR.json` | success | 1.017 |  |
| 89 | lfr | `Drop_Ref/Dx_10/Dx_10_fromLFR.json` | success | 1.018 |  |
| 90 | lfr | `Drop_Ref/Dx_11/Dx_11_fromLFR.json` | success | 1.169 |  |
| 91 | lfr | `Drop_Ref/Dx_12/Dx_12_fromLFR.json` | success | 1.120 |  |
| 92 | lfr | `Drop_Ref/Dx_13/Dx_13_fromLFR.json` | success | 1.270 |  |
| 93 | lfr | `Drop_Ref/Dx_14/Dx_14_fromLFR.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=9, E=10, components=1, cycle_rank=2; cycle-closing connection(s): channel_8, channel_9 |
| 94 | lfr | `Drop_Ref/Dx_15/Dx_15_fromLFR.json` | success | 1.020 |  |
| 95 | lfr | `Drop_Ref/Dx_2/Dx_2_fromLFR.json` | success | 1.070 |  |
| 96 | lfr | `Drop_Ref/Dx_3/Dx_3_fromLFR.json` | success | 1.069 |  |
| 97 | lfr | `Drop_Ref/Dx_4/Dx_4_fromLFR.json` | fail | 0.168 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=18, E=18, components=1, cycle_rank=1; cycle-closing connection(s): channel_18 |
| 98 | lfr | `Drop_Ref/Dx_5/Dx_5_fromLFR.json` | success | 1.169 |  |
| 99 | lfr | `Drop_Ref/Dx_6/Dx_6_fromLFR.json` | success | 1.070 |  |
| 100 | lfr | `Drop_Ref/Dx_7/Dx_7_fromLFR.json` | success | 1.169 |  |
| 101 | lfr | `Drop_Ref/Dx_8/Dx_8_fromLFR.json` | success | 1.374 |  |
| 102 | lfr | `Drop_Ref/Dx_9/Dx_9_fromLFR.json` | success | 1.122 |  |
| 103 | lfr | `Expressions/Expression_1/Expression_1_fromLFR.json` | success | 0.968 |  |
| 104 | lfr | `Expressions/Expression_10/Expression_10_fromLFR.json` | success | 0.970 |  |
| 105 | lfr | `Expressions/Expression_11/Expression_11_fromLFR.json` | success | 0.921 |  |
| 106 | lfr | `Expressions/Expression_12/Expression_12_fromLFR.json` | success | 1.572 |  |
| 107 | lfr | `Expressions/Expression_13/Expression_13_fromLFR.json` | success | 0.869 |  |
| 108 | lfr | `Expressions/Expression_14/Expression_14_fromLFR.json` | fail | 0.168 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=58, E=60, components=1, cycle_rank=3; cycle-closing connection(s): channel_13, channel_15, channel_55 |
| 109 | lfr | `Expressions/Expression_15/Expression_15_fromLFR.json` | success | 1.321 |  |
| 110 | lfr | `Expressions/Expression_2/Expression_2_fromLFR.json` | success | 0.968 |  |
| 111 | lfr | `Expressions/Expression_3/Expression_3_fromLFR.json` | success | 1.018 |  |
| 112 | lfr | `Expressions/Expression_4/Expression_4_fromLFR.json` | success | 1.070 |  |
| 113 | lfr | `Expressions/Expression_5/Expression_5_fromLFR.json` | success | 1.071 |  |
| 114 | lfr | `Expressions/Expression_6/Expression_6_fromLFR.json` | success | 1.171 |  |
| 115 | lfr | `Expressions/Expression_7/Expression_7_fromLFR.json` | success | 1.119 |  |
| 116 | lfr | `Expressions/Expression_8/Expression_8_fromLFR.json` | fail | 0.117 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=10, E=10, components=1, cycle_rank=1; cycle-closing connection(s): channel_6 |
| 117 | lfr | `Expressions/Expression_9/Expression_9_fromLFR.json` | success | 0.971 |  |
| 118 | lfr | `Ghissues/Issue_10/Issue_10_fromLFR.json` | fail | 0.116 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=24, E=36, components=1, cycle_rank=13; cycle-closing connection(s): channel_20, channel_21, channel_23, channel_25, channel_26, channel_27, channel_29, channel_30, channel_31, channel_33, channel_34, channel_35, channel_36 |
| 119 | lfr | `Ghissues/Issue_15/Issue_15_fromLFR.json` | success | 1.070 |  |
| 120 | lfr | `Ghissues/Issue_2/Issue_2_fromLFR.json` | success | 0.926 |  |
| 121 | lfr | `Ghissues/Issue_3/Issue_3_fromLFR.json` | fail | 0.168 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=20, E=28, components=1, cycle_rank=9; cycle-closing connection(s): channel_13, channel_15, channel_20, channel_21, channel_22, channel_23, channel_24, channel_26, channel_28 |
| 122 | lfr | `Ghissues/Issue_6/Issue_6_fromLFR.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=35, E=51, components=1, cycle_rank=17; cycle-closing connection(s): channel_20, channel_31, channel_32, channel_33, channel_34, channel_37, channel_38, channel_41, channel_42, channel_44, channel_45, channel_46, channel_47, channel_48, channel_49, channel_50, channel_51 |
| 123 | lfr | `Ghissues/Issue_7/Issue_7_fromLFR.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=44, E=52, components=1, cycle_rank=9; cycle-closing connection(s): channel_26, channel_30, channel_40, channel_45, channel_46, channel_47, channel_48, channel_49, channel_50 |
| 124 | lfr | `Ghissues/Issue_8/Issue_8_fromLFR.json` | fail | 0.169 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=48, E=57, components=1, cycle_rank=10; cycle-closing connection(s): channel_26, channel_36, channel_42, channel_48, channel_50, channel_51, channel_52, channel_54, channel_55, channel_56 |
| 125 | lfr | `Ghissues/Issue_9/Issue_9_fromLFR.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=47, E=62, components=1, cycle_rank=16; cycle-closing connection(s): channel_34, channel_36, channel_37, channel_44, channel_48, channel_50, channel_52, channel_53, channel_54, channel_55, channel_56, channel_57, channel_59, channel_60, channel_61, channel_62 |
| 126 | lfr | `Graph_Coverage/Tree_Fanin/Tree_Fanin_fromLFR.json` | success | 1.121 |  |
| 127 | lfr | `Graph_Coverage/Tree_Fanout/Tree_Fanout_fromLFR.json` | success | 1.122 |  |
| 128 | lfr | `Literature_Benchmarks/Device_1_Sc_Rna_Seq/Device_1_Sc_Rna_Seq_fromLFR.json` | fail | 0.166 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=9, E=9, components=1, cycle_rank=1; cycle-closing connection(s): channel_9 |
| 129 | lfr | `Literature_Benchmarks/Device_2_Artificial_Cells/Device_2_Artificial_Cells_fromLFR.json` | success | 1.222 |  |
| 130 | lfr | `Literature_Benchmarks/Device_4_Molecular_Diagnostics/Device_4_Molecular_Diagnostics_fromLFR.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=9, E=9, components=1, cycle_rank=1; cycle-closing connection(s): channel_5 |
| 131 | lfr | `Literature_Benchmarks/Device_5_Bacteria_Diagnostics/Device_5_Bacteria_Diagnostics_fromLFR.json` | success | 1.274 |  |
| 132 | lfr | `Literature_Benchmarks/Device_6_Organic_Chemical_Synthesis/Device_6_Organic_Chemical_Synthesis_fromLFR.json` | success | 2.527 |  |
| 133 | lfr | `Literature_Benchmarks/Device_7_Enzyme_Screening/Device_7_Enzyme_Screening_fromLFR.json` | success | 10.707 |  |
| 134 | lfr | `Literature_Benchmarks/library/mip_biosensor/mip_biosensor_fromLFR.json` | success | 0.971 |  |
| 135 | lfr | `Mars/Antibiotic_Resistance/Antibiotic_Resistance_fromLFR.json` | success | 1.222 |  |
| 136 | lfr | `Mars/Cell_Lysis/Cell_Lysis_fromLFR.json` | success | 1.071 |  |
| 137 | lfr | `Mars/Dna_Digest/Dna_Digest_fromLFR.json` | success | 1.272 |  |
| 138 | lfr | `Mars/Fluorescence/Fluorescence_fromLFR.json` | success | 1.171 |  |
| 139 | lfr | `Mars/Ligation/Ligation_fromLFR.json` | success | 1.973 |  |
| 140 | lfr | `Mars/Pcr/Pcr_fromLFR.json` | success | 1.121 |  |
| 141 | lfr | `Mars/Sorting/Sorting_fromLFR.json` | success | 0.969 |  |
| 142 | lfr | `Mars/Transformation/Transformation_fromLFR.json` | success | 1.071 |  |
| 143 | lfr | `Protocols/Cell_Sorting/Cell_Sorting_fromLFR.json` | success | 0.928 |  |
| 144 | lfr | `Protocols/Directed_Evolution/Directed_Evolution_fromLFR.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=27, E=42, components=1, cycle_rank=16; cycle-closing connection(s): channel_13, channel_24, channel_26, channel_28, channel_29, channel_30, channel_31, channel_33, channel_34, channel_35, channel_36, channel_37, channel_38, channel_39, channel_40, channel_41 |
| 145 | lfr | `Technology_Mapping/Cycle/Cycle_fromLFR.json` | success | 1.020 |  |
| 146 | lfr | `Technology_Mapping/Instance_Mapping/Instance_Mapping_fromLFR.json` | success | 0.920 |  |
| 147 | lfr | `Technology_Mapping/N_Greater_M_Map/N_Greater_M_Map_fromLFR.json` | success | 1.071 |  |
| 148 | lfr | `Technology_Mapping/N_Less_M_Map/N_Less_M_Map_fromLFR.json` | success | 1.121 |  |
| 149 | lfr | `Technology_Mapping/One_To_One_Mapping/One_To_One_Mapping_fromLFR.json` | success | 0.919 |  |
| 150 | lfr | `Technology_Mapping/Tree_Bus/Tree_Bus_fromLFR.json` | fail | 0.168 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=11, E=18, components=1, cycle_rank=8; cycle-closing connection(s): channel_4, channel_6, channel_8, channel_10, channel_12, channel_14, channel_16, channel_18 |
| 151 | lfr | `Technology_Mapping/Tree_Fanin_Mapping/Tree_Fanin_Mapping_fromLFR.json` | success | 1.170 |  |
| 152 | lfr | `Technology_Mapping/Tree_Fanout_Mapping_1/Tree_Fanout_Mapping_1_fromLFR.json` | success | 1.122 |  |
| 153 | lfr | `Technology_Mapping/Tree_Fanout_Mapping_2/Tree_Fanout_Mapping_2_fromLFR.json` | success | 1.120 |  |
| 154 | lfr | `Technology_Mapping/Tree_Fanout_Mapping_3/Tree_Fanout_Mapping_3_fromLFR.json` | success | 1.170 |  |
| 155 | lfr | `Technology_Mapping/Tree_Storage_Bus_Mapping/Tree_Storage_Bus_Mapping_fromLFR.json` | fail | 0.168 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=20, E=43, components=1, cycle_rank=24; cycle-closing connection(s): channel_19, channel_20, channel_21, channel_22, channel_23, channel_24, channel_25, channel_26, channel_28, channel_29, channel_30, channel_31, channel_32, channel_33, channel_34, channel_35, channel_36, channel_37, channel_38, channel_39, channel_40, channel_41, channel_42, channel_43 |
| 158 | lfr | `Transport_Networks/One_To_One/One_To_One_fromLFR.json` | success | 0.920 |  |
| 159 | mint | `Base/Crossing_H/Crossing_H_fromMINT.json` | success | 1.823 |  |
| 160 | mint | `Base/Crossing_V/Crossing_V_fromMINT.json` | success | 1.923 |  |
| 161 | mint | `Base/Grad_Gen_H/Grad_Gen_H_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=11, E=12, components=1, cycle_rank=2; cycle-closing connection(s): c10, c11 |
| 162 | mint | `Base/Grad_Gen_V/Grad_Gen_V_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=11, E=12, components=1, cycle_rank=2; cycle-closing connection(s): c10, c11 |
| 163 | mint | `Base/Grid_4_Mixer/Grid_4_Mixer_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=24, E=38, components=1, cycle_rank=15; cycle-closing connection(s): c6, c7, c8, c13, c14, c15, c20, c21, c22, c27, c28, c29, c31, c32, c33 |
| 164 | mint | `Base/Horizontal_MUX_01/Horizontal_MUX_01_fromMINT.json` | success | 1.576 |  |
| 165 | mint | `Base/Logic_Test_01/Logic_Test_01_fromMINT.json` | success | 1.020 |  |
| 166 | mint | `Base/Logic_Test_02/Logic_Test_02_fromMINT.json` | success | 1.171 |  |
| 167 | mint | `Base/Logic_Test_03/Logic_Test_03_fromMINT.json` | success | 1.372 |  |
| 168 | mint | `Base/Long_Cell_Trap_Two_Port/Long_Cell_Trap_Two_Port_fromMINT.json` | success | 0.920 |  |
| 169 | mint | `Base/MUX_8/MUX_8_fromMINT.json` | success | 1.572 |  |
| 170 | mint | `Base/Net_Multi_Test/Net_Multi_Test_fromMINT.json` | success | 13.961 |  |
| 171 | mint | `Base/Net_Test/Net_Test_fromMINT.json` | success | 1.371 |  |
| 173 | mint | `Base/Node_Long_Cell_Trap_01/Node_Long_Cell_Trap_01_fromMINT.json` | success | 1.020 |  |
| 174 | mint | `Base/Node_Long_Cell_Trap_02/Node_Long_Cell_Trap_02_fromMINT.json` | success | 1.021 |  |
| 175 | mint | `Base/Node_Long_Cell_Trap_03/Node_Long_Cell_Trap_03_fromMINT.json` | success | 1.020 |  |
| 176 | mint | `Base/Node_Long_Cell_Trap_04/Node_Long_Cell_Trap_04_fromMINT.json` | success | 1.070 |  |
| 177 | mint | `Base/Node_Test_01/Node_Test_01_fromMINT.json` | success | 4.983 |  |
| 178 | mint | `Base/Nonplanar/Nonplanar_fromMINT.json` | fail | 0.168 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=4, E=6, components=1, cycle_rank=3; cycle-closing connection(s): c4, c5, c6 |
| 179 | mint | `Base/Port_Bank_01/Port_Bank_01_fromMINT.json` | success | 0.669 |  |
| 180 | mint | `Base/Port_Multi_Connection/Port_Multi_Connection_fromMINT.json` | fail | 0.167 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=4, E=4, components=1, cycle_rank=1; cycle-closing connection(s): c4 |
| 181 | mint | `Base/Square_Cell_Trap_Chambers/Square_Cell_Trap_Chambers_fromMINT.json` | fail | 0.168 | UnsupportedFlowTopologyError: layer-0 component graph is not a forest: V=17, E=20, components=1, cycle_rank=4; cycle-closing connection(s): c15, c17, c19, c20 |
| 182 | mint | `Base/Square_Cell_Trap_Ports/Square_Cell_Trap_Ports_fromMINT.json` | success | 6.082 |  |
