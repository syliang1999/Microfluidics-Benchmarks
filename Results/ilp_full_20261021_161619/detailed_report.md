# ILP full benchmark report

- Per-case hard timeout: **1800 seconds**
- Workers: **12**
- Discovered: **454**
- Completed: **454**
- Success: **276**
- Fail: **101**
- Timeout: **77**

| # | Suite | Case | Status | Wall time (s) | Reason |
|---:|---|---|---|---:|---|
| 1 | lfr | `CIDAR_Lab_Past_Devices/Chemostat_Chip/Chemostat_Chip_fromLFR.json` | timeout | 1800.039 | exceeded 1800s |
| 2 | lfr | `CIDAR_Lab_Past_Devices/Dna_Synthesizer/Dna_Synthesizer_fromLFR.json` | timeout | 1800.068 | exceeded 1800s |
| 3 | lfr | `CIDAR_Lab_Past_Devices/Dual_Lane_Droplet/Dual_Lane_Droplet_fromLFR.json` | success | 6.196 |  |
| 4 | lfr | `CIDAR_Lab_Past_Devices/Genetic_Clock_Testing_Tool/Genetic_Clock_Testing_Tool_fromLFR.json` | success | 64.785 |  |
| 5 | lfr | `CIDAR_Lab_Past_Devices/Glycoform/Glycoform_fromLFR.json` | success | 162.008 |  |
| 6 | lfr | `CIDAR_Lab_Past_Devices/Grad_Cells/Grad_Cells_fromLFR.json` | fail | 12.161 | RuntimeError: DRC violations: channel_spacing: channels of connections 'channel_5' and 'channel_12' violate the 1000 edge-to-edge clearance |
| 7 | lfr | `CIDAR_Lab_Past_Devices/Gradient/Gradient_fromLFR.json` | fail | 1799.080 | TimeoutError: case-level placement/routing budget exhausted; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/lfr__CIDAR_Lab_Past_Devices__Gradient__Gradient_fromLFR/placement_attempts.json; last error: Placement MILP failed: status=1 message=Time limit reached. (HiGHS Status 13: model_status is Time limit reached; primal_status is At lower/fixed bound) |
| 8 | lfr | `CIDAR_Lab_Past_Devices/Hasty_Cell_Traps/Hasty_Cell_Traps_fromLFR.json` | success | 3.735 |  |
| 9 | lfr | `CIDAR_Lab_Past_Devices/Hmlp_Dual_Bank/Hmlp_Dual_Bank_fromLFR.json` | fail | 1799.915 | TimeoutError: case-level placement/routing budget exhausted; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/lfr__CIDAR_Lab_Past_Devices__Hmlp_Dual_Bank__Hmlp_Dual_Bank_fromLFR/placement_attempts.json; last error: Placement MILP failed: status=1 message=Time limit reached. (HiGHS Status 13: model_status is Time limit reached; primal_status is At lower/fixed bound) |
| 10 | lfr | `CIDAR_Lab_Past_Devices/Incubator/Incubator_fromLFR.json` | timeout | 1800.066 | exceeded 1800s |
| 11 | lfr | `CIDAR_Lab_Past_Devices/Inlet_16/Inlet_16_fromLFR.json` | fail | 1799.432 | TimeoutError: case-level placement/routing budget exhausted; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/lfr__CIDAR_Lab_Past_Devices__Inlet_16__Inlet_16_fromLFR/placement_attempts.json; last error: Placement MILP failed: status=1 message=Time limit reached. (HiGHS Status 13: model_status is Time limit reached; primal_status is At lower/fixed bound) |
| 12 | lfr | `CIDAR_Lab_Past_Devices/Kinetics/Kinetics_fromLFR.json` | success | 2.372 |  |
| 13 | lfr | `CIDAR_Lab_Past_Devices/Logic_04/Logic_04_fromLFR.json` | timeout | 1800.017 | exceeded 1800s |
| 14 | lfr | `CIDAR_Lab_Past_Devices/Mfd_005_Chip/Mfd_005_Chip_fromLFR.json` | success | 63.187 |  |
| 15 | lfr | `CIDAR_Lab_Past_Devices/Microalgal_Bioassay/Microalgal_Bioassay_fromLFR.json` | success | 86.974 |  |
| 16 | lfr | `CIDAR_Lab_Past_Devices/Microdroplet/Microdroplet_fromLFR.json` | timeout | 1800.034 | exceeded 1800s |
| 17 | lfr | `CIDAR_Lab_Past_Devices/Microreactor/Microreactor_fromLFR.json` | success | 104.563 |  |
| 18 | lfr | `CIDAR_Lab_Past_Devices/Mix_Incubate_Express/Mix_Incubate_Express_fromLFR.json` | success | 1.420 |  |
| 19 | lfr | `CIDAR_Lab_Past_Devices/Multi_Input/Multi_Input_fromLFR.json` | timeout | 1800.034 | exceeded 1800s |
| 20 | lfr | `CIDAR_Lab_Past_Devices/MUX_96_Chambers/MUX_96_Chambers_fromLFR.json` | timeout | 1800.116 | exceeded 1800s |
| 21 | lfr | `CIDAR_Lab_Past_Devices/Net_MUX/Net_MUX_fromLFR.json` | timeout | 1800.034 | exceeded 1800s |
| 22 | lfr | `CIDAR_Lab_Past_Devices/Nine_To_One_MUX/Nine_To_One_MUX_fromLFR.json` | timeout | 1800.033 | exceeded 1800s |
| 23 | lfr | `CIDAR_Lab_Past_Devices/Number_Declarations/Number_Declarations_fromLFR.json` | success | 0.968 |  |
| 24 | lfr | `CIDAR_Lab_Past_Devices/Olfactory/Olfactory_fromLFR.json` | fail | 128.980 | RuntimeError: DRC violations: channel_spacing: channels of connections 'channel_8' and 'channel_12' violate the 1000 edge-to-edge clearance; channel_spacing: channels of connections 'channel_10' and 'channel_13' violate the 1000 edge-to-edge clearance |
| 25 | lfr | `CIDAR_Lab_Past_Devices/Pump_Passthrough/Pump_Passthrough_fromLFR.json` | success | 1.070 |  |
| 26 | lfr | `CIDAR_Lab_Past_Devices/Ring/Ring_fromLFR.json` | success | 1.973 |  |
| 27 | lfr | `CIDAR_Lab_Past_Devices/Root_Chip/Root_Chip_fromLFR.json` | timeout | 1800.067 | exceeded 1800s |
| 28 | lfr | `CIDAR_Lab_Past_Devices/Rotary_16/Rotary_16_fromLFR.json` | timeout | 1800.067 | exceeded 1800s |
| 29 | lfr | `CIDAR_Lab_Past_Devices/Rotary_Cells/Rotary_Cells_fromLFR.json` | timeout | 1800.035 | exceeded 1800s |
| 30 | lfr | `CIDAR_Lab_Past_Devices/Seeding/Seeding_fromLFR.json` | timeout | 1800.035 | exceeded 1800s |
| 31 | lfr | `CIDAR_Lab_Past_Devices/Three_Reagent_Mix/Three_Reagent_Mix_fromLFR.json` | success | 48.415 |  |
| 32 | lfr | `COVID/Aj_Rtpcr_8_Primer/Aj_Rtpcr_8_Primer_fromLFR.json` | timeout | 1800.033 | exceeded 1800s |
| 33 | lfr | `COVID/Arize/Arize_fromLFR.json` | timeout | 1800.035 | exceeded 1800s |
| 34 | lfr | `COVID/Covid_Crispr/Covid_Crispr_fromLFR.json` | success | 1.169 |  |
| 35 | lfr | `COVID/Crispr/Crispr_fromLFR.json` | success | 13.107 |  |
| 36 | lfr | `COVID/Detectr/Detectr_fromLFR.json` | success | 605.168 |  |
| 37 | lfr | `COVID/Elisa/Elisa_fromLFR.json` | success | 47.611 |  |
| 38 | lfr | `COVID/Gel_Electrophoresis/Gel_Electrophoresis_fromLFR.json` | success | 299.639 |  |
| 39 | lfr | `COVID/Hybri_Detect/Hybri_Detect_fromLFR.json` | success | 7.388 |  |
| 40 | lfr | `COVID/Part_1_Rna_Prep/Part_1_Rna_Prep_fromLFR.json` | success | 4.279 |  |
| 41 | lfr | `COVID/Part_2_Rt_Step/Part_2_Rt_Step_fromLFR.json` | fail | 3.126 | RuntimeError: DRC violations: channel_spacing: channels of connections 'channel_5' and 'channel_7' violate the 1000 edge-to-edge clearance |
| 42 | lfr | `COVID/Part_3_Gel/Part_3_Gel_fromLFR.json` | success | 83.798 |  |
| 43 | lfr | `COVID/Rt_Pcr/Rt_Pcr_fromLFR.json` | success | 1.069 |  |
| 44 | lfr | `Distribute_Expressions/And_Annotation_Test/And_Annotation_Test_fromLFR.json` | fail | 1798.532 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/lfr__Distribute_Expressions__And_Annotation_Test__And_Annotation_Test_fromLFR/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 45 | lfr | `Distribute_Expressions/Dist_Expression_1/Dist_Expression_1_fromLFR.json` | success | 1.068 |  |
| 46 | lfr | `Distribute_Expressions/Dist_Expression_2/Dist_Expression_2_fromLFR.json` | success | 1.570 |  |
| 47 | lfr | `Distribute_Expressions/Dist_Expression_3/Dist_Expression_3_fromLFR.json` | fail | 1798.546 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/lfr__Distribute_Expressions__Dist_Expression_3__Dist_Expression_3_fromLFR/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 48 | lfr | `Distribute_Library/Cell_Traps_4/Cell_Traps_4_fromLFR.json` | success | 0.968 |  |
| 49 | lfr | `Distribute_Library/Hv_Storage_Grid_04/Hv_Storage_Grid_04_fromLFR.json` | success | 0.970 |  |
| 50 | lfr | `Distribute_Library/Hv_Storage_Grid_08/Hv_Storage_Grid_08_fromLFR.json` | success | 0.968 |  |
| 51 | lfr | `Distribute_Library/Hv_Storage_Grid_16/Hv_Storage_Grid_16_fromLFR.json` | success | 1.018 |  |
| 52 | lfr | `Distribute_Library/Hv_Storage_Grid_32/Hv_Storage_Grid_32_fromLFR.json` | success | 1.019 |  |
| 53 | lfr | `Distribute_Library/Hv_Storage_Grid_64/Hv_Storage_Grid_64_fromLFR.json` | success | 1.021 |  |
| 54 | lfr | `Distribute_Library/MUX_02_In/MUX_02_In_fromLFR.json` | success | 2.022 |  |
| 55 | lfr | `Distribute_Library/MUX_02_Out/MUX_02_Out_fromLFR.json` | success | 1.522 |  |
| 56 | lfr | `Distribute_Library/MUX_04_In/MUX_04_In_fromLFR.json` | fail | 1798.551 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/lfr__Distribute_Library__MUX_04_In__MUX_04_In_fromLFR/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 57 | lfr | `Distribute_Library/MUX_04_Out/MUX_04_Out_fromLFR.json` | fail | 1798.617 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/lfr__Distribute_Library__MUX_04_Out__MUX_04_Out_fromLFR/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 58 | lfr | `Distribute_Library/MUX_08_In/MUX_08_In_fromLFR.json` | fail | 1798.554 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/lfr__Distribute_Library__MUX_08_In__MUX_08_In_fromLFR/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 59 | lfr | `Distribute_Library/MUX_08_Out/MUX_08_Out_fromLFR.json` | fail | 1798.495 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/lfr__Distribute_Library__MUX_08_Out__MUX_08_Out_fromLFR/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 60 | lfr | `Distribute_Library/MUX_16_In/MUX_16_In_fromLFR.json` | fail | 1798.581 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/lfr__Distribute_Library__MUX_16_In__MUX_16_In_fromLFR/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 61 | lfr | `Distribute_Library/MUX_16_Out/MUX_16_Out_fromLFR.json` | fail | 1798.638 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/lfr__Distribute_Library__MUX_16_Out__MUX_16_Out_fromLFR/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 62 | lfr | `Distribute_Library/MUX_32_In/MUX_32_In_fromLFR.json` | fail | 1798.635 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/lfr__Distribute_Library__MUX_32_In__MUX_32_In_fromLFR/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 63 | lfr | `Distribute_Library/MUX_32_Out/MUX_32_Out_fromLFR.json` | fail | 1798.676 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/lfr__Distribute_Library__MUX_32_Out__MUX_32_Out_fromLFR/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 64 | lfr | `Distribute_Library/MUX_64_In/MUX_64_In_fromLFR.json` | fail | 1798.561 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/lfr__Distribute_Library__MUX_64_In__MUX_64_In_fromLFR/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 65 | lfr | `Distribute_Library/MUX_64_Out/MUX_64_Out_fromLFR.json` | fail | 1798.519 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/lfr__Distribute_Library__MUX_64_Out__MUX_64_Out_fromLFR/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 66 | lfr | `Distribute_Library/Single_Storage_Grid_01/Single_Storage_Grid_01_fromLFR.json` | success | 0.969 |  |
| 67 | lfr | `Distribute_Library/Single_Storage_Grid_02/Single_Storage_Grid_02_fromLFR.json` | success | 0.970 |  |
| 68 | lfr | `Distribute_Library/Single_Storage_Grid_04/Single_Storage_Grid_04_fromLFR.json` | success | 0.968 |  |
| 69 | lfr | `Distribute_Library/Single_Storage_Grid_08/Single_Storage_Grid_08_fromLFR.json` | success | 0.969 |  |
| 70 | lfr | `Distribute_Library/Single_Storage_Grid_16/Single_Storage_Grid_16_fromLFR.json` | success | 0.971 |  |
| 71 | lfr | `Distribute_Library/Single_Storage_Grid_32/Single_Storage_Grid_32_fromLFR.json` | success | 0.968 |  |
| 72 | lfr | `Distribute_Library/Single_Storage_Grid_64/Single_Storage_Grid_64_fromLFR.json` | success | 0.967 |  |
| 73 | lfr | `Distribute_Library/Transposer_02/Transposer_02_fromLFR.json` | success | 57.952 |  |
| 74 | lfr | `Distribute_Library/Transposer_03/Transposer_03_fromLFR.json` | fail | 1798.478 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/lfr__Distribute_Library__Transposer_03__Transposer_03_fromLFR/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 75 | lfr | `Distribute_Library/Transposer_04/Transposer_04_fromLFR.json` | timeout | 1800.034 | exceeded 1800s |
| 76 | lfr | `Distribute_Library/Transposer_08/Transposer_08_fromLFR.json` | success | 0.969 |  |
| 77 | lfr | `Distribute_Library/Transposer_16/Transposer_16_fromLFR.json` | success | 1.068 |  |
| 78 | lfr | `Distribute_Library/Transposer_32/Transposer_32_fromLFR.json` | success | 0.967 |  |
| 79 | lfr | `Distribute_Library/Transposer_64/Transposer_64_fromLFR.json` | success | 1.018 |  |
| 80 | lfr | `Drop_Ref/Droplet_Generator_1/Droplet_Generator_1_fromLFR.json` | success | 1.019 |  |
| 81 | lfr | `Drop_Ref/Droplet_Generator_2/Droplet_Generator_2_fromLFR.json` | success | 24.979 |  |
| 82 | lfr | `Drop_Ref/Droplet_Generator_3/Droplet_Generator_3_fromLFR.json` | timeout | 1800.033 | exceeded 1800s |
| 83 | lfr | `Drop_Ref/Droplet_Generator_4/Droplet_Generator_4_fromLFR.json` | success | 68.131 |  |
| 84 | lfr | `Drop_Ref/Dropx_Test_1/Dropx_Test_1_fromLFR.json` | success | 1.018 |  |
| 85 | lfr | `Drop_Ref/Dropx_Test_2/Dropx_Test_2_fromLFR.json` | success | 4.279 |  |
| 86 | lfr | `Drop_Ref/Dropx_Test_3/Dropx_Test_3_fromLFR.json` | success | 11.299 |  |
| 87 | lfr | `Drop_Ref/Dropx_Test_4/Dropx_Test_4_fromLFR.json` | success | 18.263 |  |
| 88 | lfr | `Drop_Ref/Dx_1/Dx_1_fromLFR.json` | success | 3.974 |  |
| 89 | lfr | `Drop_Ref/Dx_10/Dx_10_fromLFR.json` | success | 7.686 |  |
| 90 | lfr | `Drop_Ref/Dx_11/Dx_11_fromLFR.json` | fail | 124.488 | RuntimeError: DRC violations: channel_spacing: channels of connections 'channel_4' and 'channel_5' violate the 1000 edge-to-edge clearance; channel_spacing: channels of connections 'channel_11' and 'channel_12' violate the 1000 edge-to-edge clearance |
| 91 | lfr | `Drop_Ref/Dx_12/Dx_12_fromLFR.json` | success | 5.634 |  |
| 92 | lfr | `Drop_Ref/Dx_13/Dx_13_fromLFR.json` | fail | 38.734 | RuntimeError: DRC violations: channel_spacing: channels of connections 'channel_5' and 'channel_11' violate the 1000 edge-to-edge clearance; channel_spacing: channels of connections 'channel_14' and 'channel_15' violate the 1000 edge-to-edge clearance |
| 93 | lfr | `Drop_Ref/Dx_14/Dx_14_fromLFR.json` | success | 61.762 |  |
| 94 | lfr | `Drop_Ref/Dx_15/Dx_15_fromLFR.json` | success | 1.671 |  |
| 95 | lfr | `Drop_Ref/Dx_2/Dx_2_fromLFR.json` | success | 3.729 |  |
| 96 | lfr | `Drop_Ref/Dx_3/Dx_3_fromLFR.json` | success | 44.907 |  |
| 97 | lfr | `Drop_Ref/Dx_4/Dx_4_fromLFR.json` | success | 739.185 |  |
| 98 | lfr | `Drop_Ref/Dx_5/Dx_5_fromLFR.json` | success | 25.684 |  |
| 99 | lfr | `Drop_Ref/Dx_6/Dx_6_fromLFR.json` | success | 1.721 |  |
| 100 | lfr | `Drop_Ref/Dx_7/Dx_7_fromLFR.json` | success | 101.117 |  |
| 101 | lfr | `Drop_Ref/Dx_8/Dx_8_fromLFR.json` | fail | 518.724 | RuntimeError: DRC violations: channel_spacing: channels of connections 'channel_3' and 'channel_15' violate the 1000 edge-to-edge clearance |
| 102 | lfr | `Drop_Ref/Dx_9/Dx_9_fromLFR.json` | success | 62.654 |  |
| 103 | lfr | `Expressions/Expression_1/Expression_1_fromLFR.json` | success | 4.178 |  |
| 104 | lfr | `Expressions/Expression_10/Expression_10_fromLFR.json` | success | 2.675 |  |
| 105 | lfr | `Expressions/Expression_11/Expression_11_fromLFR.json` | success | 1.070 |  |
| 106 | lfr | `Expressions/Expression_12/Expression_12_fromLFR.json` | success | 1059.166 |  |
| 107 | lfr | `Expressions/Expression_13/Expression_13_fromLFR.json` | success | 1.120 |  |
| 108 | lfr | `Expressions/Expression_14/Expression_14_fromLFR.json` | timeout | 1800.036 | exceeded 1800s |
| 109 | lfr | `Expressions/Expression_15/Expression_15_fromLFR.json` | success | 1236.384 |  |
| 110 | lfr | `Expressions/Expression_2/Expression_2_fromLFR.json` | success | 1.322 |  |
| 111 | lfr | `Expressions/Expression_3/Expression_3_fromLFR.json` | success | 7.339 |  |
| 112 | lfr | `Expressions/Expression_4/Expression_4_fromLFR.json` | success | 20.089 |  |
| 113 | lfr | `Expressions/Expression_5/Expression_5_fromLFR.json` | success | 31.266 |  |
| 114 | lfr | `Expressions/Expression_6/Expression_6_fromLFR.json` | fail | 6.888 | RuntimeError: DRC violations: channel_spacing: channels of connections 'channel_3' and 'channel_8' violate the 1000 edge-to-edge clearance; channel_spacing: channels of connections 'channel_3' and 'channel_9' violate the 1000 edge-to-edge clearance |
| 115 | lfr | `Expressions/Expression_7/Expression_7_fromLFR.json` | success | 14.866 |  |
| 116 | lfr | `Expressions/Expression_8/Expression_8_fromLFR.json` | success | 95.601 |  |
| 117 | lfr | `Expressions/Expression_9/Expression_9_fromLFR.json` | success | 2.675 |  |
| 118 | lfr | `Ghissues/Issue_10/Issue_10_fromLFR.json` | timeout | 1800.033 | exceeded 1800s |
| 119 | lfr | `Ghissues/Issue_15/Issue_15_fromLFR.json` | success | 1.671 |  |
| 120 | lfr | `Ghissues/Issue_2/Issue_2_fromLFR.json` | success | 0.969 |  |
| 121 | lfr | `Ghissues/Issue_3/Issue_3_fromLFR.json` | timeout | 1800.034 | exceeded 1800s |
| 122 | lfr | `Ghissues/Issue_6/Issue_6_fromLFR.json` | fail | 1799.243 | TimeoutError: case-level placement/routing budget exhausted; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/lfr__Ghissues__Issue_6__Issue_6_fromLFR/placement_attempts.json; last error: Placement MILP failed: status=1 message=Time limit reached. (HiGHS Status 13: model_status is Time limit reached; primal_status is At lower/fixed bound) |
| 123 | lfr | `Ghissues/Issue_7/Issue_7_fromLFR.json` | timeout | 1800.034 | exceeded 1800s |
| 124 | lfr | `Ghissues/Issue_8/Issue_8_fromLFR.json` | fail | 1798.529 | TimeoutError: case-level placement/routing budget exhausted; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/lfr__Ghissues__Issue_8__Issue_8_fromLFR/placement_attempts.json; last error: Placement MILP failed: status=1 message=Time limit reached. (HiGHS Status 13: model_status is Time limit reached; primal_status is At lower/fixed bound) |
| 125 | lfr | `Ghissues/Issue_9/Issue_9_fromLFR.json` | timeout | 1800.070 | exceeded 1800s |
| 126 | lfr | `Graph_Coverage/Tree_Fanin/Tree_Fanin_fromLFR.json` | success | 2.226 |  |
| 127 | lfr | `Graph_Coverage/Tree_Fanout/Tree_Fanout_fromLFR.json` | success | 2.123 |  |
| 128 | lfr | `Literature_Benchmarks/Device_1_Sc_Rna_Seq/Device_1_Sc_Rna_Seq_fromLFR.json` | success | 15.166 |  |
| 129 | lfr | `Literature_Benchmarks/Device_2_Artificial_Cells/Device_2_Artificial_Cells_fromLFR.json` | fail | 16.715 | RuntimeError: DRC violations: channel_spacing: channels of connections 'channel_8' and 'channel_9' violate the 1000 edge-to-edge clearance |
| 130 | lfr | `Literature_Benchmarks/Device_4_Molecular_Diagnostics/Device_4_Molecular_Diagnostics_fromLFR.json` | success | 4.281 |  |
| 131 | lfr | `Literature_Benchmarks/Device_5_Bacteria_Diagnostics/Device_5_Bacteria_Diagnostics_fromLFR.json` | success | 2.172 |  |
| 132 | lfr | `Literature_Benchmarks/Device_6_Organic_Chemical_Synthesis/Device_6_Organic_Chemical_Synthesis_fromLFR.json` | timeout | 1800.033 | exceeded 1800s |
| 133 | lfr | `Literature_Benchmarks/Device_7_Enzyme_Screening/Device_7_Enzyme_Screening_fromLFR.json` | timeout | 1800.065 | exceeded 1800s |
| 134 | lfr | `Literature_Benchmarks/library/mip_biosensor/mip_biosensor_fromLFR.json` | success | 1.122 |  |
| 135 | lfr | `Mars/Antibiotic_Resistance/Antibiotic_Resistance_fromLFR.json` | success | 20.731 |  |
| 136 | lfr | `Mars/Cell_Lysis/Cell_Lysis_fromLFR.json` | success | 5.947 |  |
| 137 | lfr | `Mars/Dna_Digest/Dna_Digest_fromLFR.json` | success | 124.728 |  |
| 138 | lfr | `Mars/Fluorescence/Fluorescence_fromLFR.json` | success | 8.544 |  |
| 139 | lfr | `Mars/Ligation/Ligation_fromLFR.json` | success | 1465.887 |  |
| 140 | lfr | `Mars/Pcr/Pcr_fromLFR.json` | success | 1.777 |  |
| 141 | lfr | `Mars/Sorting/Sorting_fromLFR.json` | success | 1.124 |  |
| 142 | lfr | `Mars/Transformation/Transformation_fromLFR.json` | success | 3.478 |  |
| 143 | lfr | `Protocols/Cell_Sorting/Cell_Sorting_fromLFR.json` | success | 1.078 |  |
| 144 | lfr | `Protocols/Directed_Evolution/Directed_Evolution_fromLFR.json` | timeout | 1800.034 | exceeded 1800s |
| 145 | lfr | `Technology_Mapping/Cycle/Cycle_fromLFR.json` | fail | 1.526 | RuntimeError: DRC violations: channel_spacing: channels of connections 'channel_4' and 'channel_5' violate the 1000 edge-to-edge clearance |
| 146 | lfr | `Technology_Mapping/Instance_Mapping/Instance_Mapping_fromLFR.json` | success | 1.369 |  |
| 147 | lfr | `Technology_Mapping/N_Greater_M_Map/N_Greater_M_Map_fromLFR.json` | success | 2.474 |  |
| 148 | lfr | `Technology_Mapping/N_Less_M_Map/N_Less_M_Map_fromLFR.json` | success | 3.729 |  |
| 149 | lfr | `Technology_Mapping/One_To_One_Mapping/One_To_One_Mapping_fromLFR.json` | success | 1.322 |  |
| 150 | lfr | `Technology_Mapping/Tree_Bus/Tree_Bus_fromLFR.json` | success | 87.024 |  |
| 151 | lfr | `Technology_Mapping/Tree_Fanin_Mapping/Tree_Fanin_Mapping_fromLFR.json` | fail | 13.009 | RuntimeError: DRC violations: channel_spacing: channels of connections 'channel_1' and 'channel_4' violate the 1000 edge-to-edge clearance; channel_spacing: channels of connections 'channel_1' and 'channel_6' violate the 1000 edge-to-edge clearance; channel_spacing: channels of connections 'channel_4' and 'channel_6' violate the 1000 edge-to-edge clearance; channel_spacing: channels of connections 'channel_6' and 'channel_8' violate the 1000 edge-to-edge clearance; channel_spacing: channels of connections 'channel_6' and 'channel_9' violate the 1000 edge-to-edge clearance |
| 152 | lfr | `Technology_Mapping/Tree_Fanout_Mapping_1/Tree_Fanout_Mapping_1_fromLFR.json` | fail | 3.125 | RuntimeError: DRC violations: channel_spacing: channels of connections 'channel_2' and 'channel_8' violate the 1000 edge-to-edge clearance; channel_spacing: channels of connections 'channel_7' and 'channel_8' violate the 1000 edge-to-edge clearance |
| 153 | lfr | `Technology_Mapping/Tree_Fanout_Mapping_2/Tree_Fanout_Mapping_2_fromLFR.json` | success | 1.922 |  |
| 154 | lfr | `Technology_Mapping/Tree_Fanout_Mapping_3/Tree_Fanout_Mapping_3_fromLFR.json` | fail | 9.596 | RuntimeError: DRC violations: channel_spacing: channels of connections 'channel_1' and 'channel_3' violate the 1000 edge-to-edge clearance; channel_spacing: channels of connections 'channel_3' and 'channel_8' violate the 1000 edge-to-edge clearance; channel_spacing: channels of connections 'channel_4' and 'channel_6' violate the 1000 edge-to-edge clearance; channel_spacing: channels of connections 'channel_4' and 'channel_9' violate the 1000 edge-to-edge clearance |
| 155 | lfr | `Technology_Mapping/Tree_Storage_Bus_Mapping/Tree_Storage_Bus_Mapping_fromLFR.json` | timeout | 1800.034 | exceeded 1800s |
| 156 | lfr | `Transport_Networks/Distribute_Network_Examples/Distribute_Network_Examples_fromLFR.json` | fail | 1798.495 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/lfr__Transport_Networks__Distribute_Network_Examples__Distribute_Network_Examples_fromLFR/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 157 | lfr | `Transport_Networks/One_To_8/One_To_8_fromLFR.json` | fail | 1798.583 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/lfr__Transport_Networks__One_To_8__One_To_8_fromLFR/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 158 | lfr | `Transport_Networks/One_To_One/One_To_One_fromLFR.json` | success | 1.321 |  |
| 159 | mint | `Base/Crossing_H/Crossing_H_fromMINT.json` | fail | 42.755 | RuntimeError: DRC violations: control_route: layer-1 connection 'cc3' has a sentinel or missing route; control_route: layer-1 connection 'cc4' has a sentinel or missing route |
| 160 | mint | `Base/Crossing_V/Crossing_V_fromMINT.json` | fail | 37.822 | RuntimeError: DRC violations: control_route: layer-1 connection 'cc3' has a sentinel or missing route; control_route: layer-1 connection 'cc4' has a sentinel or missing route |
| 161 | mint | `Base/Grad_Gen_H/Grad_Gen_H_fromMINT.json` | success | 117.331 |  |
| 162 | mint | `Base/Grad_Gen_V/Grad_Gen_V_fromMINT.json` | fail | 82.553 | RuntimeError: DRC violations: channel_spacing: channels of connections 'c1' and 'c2' violate the 1000 edge-to-edge clearance; channel_spacing: channels of connections 'c6' and 'c12' violate the 1000 edge-to-edge clearance; channel_spacing: channels of connections 'c10' and 'c11' violate the 1000 edge-to-edge clearance |
| 163 | mint | `Base/Grid_4_Mixer/Grid_4_Mixer_fromMINT.json` | fail | 1799.036 | TimeoutError: case-level placement/routing budget exhausted; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Base__Grid_4_Mixer__Grid_4_Mixer_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=1 message=Time limit reached. (HiGHS Status 13: model_status is Time limit reached; primal_status is At lower/fixed bound) |
| 164 | mint | `Base/Horizontal_MUX_01/Horizontal_MUX_01_fromMINT.json` | fail | 1.471 | RuntimeError: DRC violations: channel_component_clearance: channel of connection 'c1' crosses the effective envelope of unrelated component 'pb_1'; channel_component_clearance: channel of connection 'c1' crosses the effective envelope of unrelated component 'pb_2'; channel_component_clearance: channel of connection 'c1' crosses the effective envelope of unrelated component 'pb_3'; channel_component_clearance: channel of connection 'c1' crosses the effective envelope of unrelated component 'pb_4'; channel_component_clearance: channel of connection 'c1' crosses the effective envelope of unrelated component 'pb_5' |
| 165 | mint | `Base/Logic_Test_01/Logic_Test_01_fromMINT.json` | success | 1.070 |  |
| 166 | mint | `Base/Logic_Test_02/Logic_Test_02_fromMINT.json` | success | 3.730 |  |
| 167 | mint | `Base/Logic_Test_03/Logic_Test_03_fromMINT.json` | success | 18.128 |  |
| 168 | mint | `Base/Long_Cell_Trap_Two_Port/Long_Cell_Trap_Two_Port_fromMINT.json` | success | 1.069 |  |
| 169 | mint | `Base/MUX_8/MUX_8_fromMINT.json` | success | 87.638 |  |
| 170 | mint | `Base/Net_Multi_Test/Net_Multi_Test_fromMINT.json` | fail | 250.655 | RuntimeError: DRC violations: control_route: layer-1 connection 'cntrlnet1' has a sentinel or missing route |
| 171 | mint | `Base/Net_Test/Net_Test_fromMINT.json` | success | 1.822 |  |
| 172 | mint | `Base/Net_Valve_Test/Net_Valve_Test_fromMINT.json` | fail | 1353.837 | RuntimeError: DRC violations: control_route: layer-1 connection 'nt1' has a sentinel or missing route |
| 173 | mint | `Base/Node_Long_Cell_Trap_01/Node_Long_Cell_Trap_01_fromMINT.json` | fail | 1798.577 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Base__Node_Long_Cell_Trap_01__Node_Long_Cell_Trap_01_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 174 | mint | `Base/Node_Long_Cell_Trap_02/Node_Long_Cell_Trap_02_fromMINT.json` | fail | 1798.525 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Base__Node_Long_Cell_Trap_02__Node_Long_Cell_Trap_02_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 175 | mint | `Base/Node_Long_Cell_Trap_03/Node_Long_Cell_Trap_03_fromMINT.json` | fail | 1798.586 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Base__Node_Long_Cell_Trap_03__Node_Long_Cell_Trap_03_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 176 | mint | `Base/Node_Long_Cell_Trap_04/Node_Long_Cell_Trap_04_fromMINT.json` | fail | 1798.638 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Base__Node_Long_Cell_Trap_04__Node_Long_Cell_Trap_04_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 177 | mint | `Base/Node_Test_01/Node_Test_01_fromMINT.json` | success | 7.498 |  |
| 178 | mint | `Base/Nonplanar/Nonplanar_fromMINT.json` | success | 1.119 |  |
| 179 | mint | `Base/Port_Bank_01/Port_Bank_01_fromMINT.json` | success | 1.118 |  |
| 180 | mint | `Base/Port_Multi_Connection/Port_Multi_Connection_fromMINT.json` | success | 1.169 |  |
| 181 | mint | `Base/Square_Cell_Trap_Chambers/Square_Cell_Trap_Chambers_fromMINT.json` | timeout | 1800.034 | exceeded 1800s |
| 182 | mint | `Base/Square_Cell_Trap_Ports/Square_Cell_Trap_Ports_fromMINT.json` | success | 26.977 |  |
| 183 | mint | `Base/Super_MUX_1024/Super_MUX_1024_fromMINT.json` | timeout | 1800.223 | exceeded 1800s |
| 184 | mint | `Base/Super_MUX_128/Super_MUX_128_fromMINT.json` | fail | 1799.243 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Base__Super_MUX_128__Super_MUX_128_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 185 | mint | `Base/Super_MUX_16/Super_MUX_16_fromMINT.json` | fail | 581.118 | RuntimeError: DRC violations: channel_spacing: channels of connections 'cin3' and 'cin4' violate the 1000 edge-to-edge clearance; channel_spacing: channels of connections 'cin4' and 'cin5' violate the 1000 edge-to-edge clearance; channel_spacing: channels of connections 'cin5' and 'cin6' violate the 1000 edge-to-edge clearance |
| 186 | mint | `Base/Super_MUX_2/Super_MUX_2_fromMINT.json` | success | 1.070 |  |
| 187 | mint | `Base/Super_MUX_256/Super_MUX_256_fromMINT.json` | timeout | 1800.067 | exceeded 1800s |
| 188 | mint | `Base/Super_MUX_32/Super_MUX_32_fromMINT.json` | timeout | 1800.035 | exceeded 1800s |
| 189 | mint | `Base/Super_MUX_4/Super_MUX_4_fromMINT.json` | success | 2.123 |  |
| 190 | mint | `Base/Super_MUX_512/Super_MUX_512_fromMINT.json` | timeout | 1800.117 | exceeded 1800s |
| 191 | mint | `Base/Super_MUX_64/Super_MUX_64_fromMINT.json` | fail | 1798.568 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Base__Super_MUX_64__Super_MUX_64_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 192 | mint | `Base/Super_MUX_8/Super_MUX_8_fromMINT.json` | fail | 3.479 | RuntimeError: DRC violations: channel_spacing: channels of connections 'cin5' and 'cin6' violate the 1000 edge-to-edge clearance; channel_spacing: channels of connections 'cin6' and 'cin7' violate the 1000 edge-to-edge clearance; channel_spacing: channels of connections 'cin7' and 'cin8' violate the 1000 edge-to-edge clearance |
| 193 | mint | `Base/Test_MUX_01/Test_MUX_01_fromMINT.json` | success | 261.295 |  |
| 194 | mint | `Base/Test_MUX_02/Test_MUX_02_fromMINT.json` | success | 208.706 |  |
| 195 | mint | `Base/Three_Port_Channel/Three_Port_Channel_fromMINT.json` | success | 1.025 |  |
| 196 | mint | `Base/Transposer_Test/Transposer_Test_fromMINT.json` | fail | 353.829 | RuntimeError: DRC violations: control_route: layer-1 connection 'cc3' has a sentinel or missing route |
| 197 | mint | `Base/Tree_Test_01/Tree_Test_01_fromMINT.json` | success | 448.016 |  |
| 198 | mint | `Base/Tree_Test_02/Tree_Test_02_fromMINT.json` | success | 1.471 |  |
| 199 | mint | `Base/Tree_Valve_Test/Tree_Valve_Test_fromMINT.json` | success | 39.846 |  |
| 200 | mint | `CIDAR_Lab_Past_Devices/Chemostat_Chip/Chemostat_Chip_fromMINT.json` | timeout | 1800.066 | exceeded 1800s |
| 201 | mint | `CIDAR_Lab_Past_Devices/Dna_Synthesizer/Dna_Synthesizer_fromMINT.json` | timeout | 1800.066 | exceeded 1800s |
| 202 | mint | `CIDAR_Lab_Past_Devices/Droplet_Merger_Simple/Droplet_Merger_Simple_fromMINT.json` | timeout | 1800.019 | exceeded 1800s |
| 203 | mint | `CIDAR_Lab_Past_Devices/Dual_Lane_Droplet/Dual_Lane_Droplet_fromMINT.json` | success | 105.825 |  |
| 204 | mint | `CIDAR_Lab_Past_Devices/Flow_Focus/Flow_Focus_fromMINT.json` | success | 1.224 |  |
| 205 | mint | `CIDAR_Lab_Past_Devices/Genetic_Clock_Testing_Tool/Genetic_Clock_Testing_Tool_fromMINT.json` | success | 69.447 |  |
| 206 | mint | `CIDAR_Lab_Past_Devices/Glycoform/Glycoform_fromMINT.json` | success | 65.799 |  |
| 207 | mint | `CIDAR_Lab_Past_Devices/Grad_Cells/Grad_Cells_fromMINT.json` | success | 12.800 |  |
| 208 | mint | `CIDAR_Lab_Past_Devices/Gradient/Gradient_fromMINT.json` | fail | 1798.585 | TimeoutError: case-level placement/routing budget exhausted; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__CIDAR_Lab_Past_Devices__Gradient__Gradient_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=1 message=Time limit reached. (HiGHS Status 13: model_status is Time limit reached; primal_status is At lower/fixed bound) |
| 209 | mint | `CIDAR_Lab_Past_Devices/Grid_02/Grid_02_fromMINT.json` | success | 124.554 |  |
| 210 | mint | `CIDAR_Lab_Past_Devices/Hasty_Cell_Traps/Hasty_Cell_Traps_fromMINT.json` | success | 17.114 |  |
| 211 | mint | `CIDAR_Lab_Past_Devices/Hmlp_Dual_Bank/Hmlp_Dual_Bank_fromMINT.json` | fail | 1799.533 | TimeoutError: case-level placement/routing budget exhausted; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__CIDAR_Lab_Past_Devices__Hmlp_Dual_Bank__Hmlp_Dual_Bank_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=1 message=Time limit reached. (HiGHS Status 13: model_status is Time limit reached; primal_status is At lower/fixed bound) |
| 212 | mint | `CIDAR_Lab_Past_Devices/Incubator/Incubator_fromMINT.json` | timeout | 1800.068 | exceeded 1800s |
| 213 | mint | `CIDAR_Lab_Past_Devices/Inlet_16/Inlet_16_fromMINT.json` | timeout | 1800.066 | exceeded 1800s |
| 214 | mint | `CIDAR_Lab_Past_Devices/Kinetics/Kinetics_fromMINT.json` | success | 1.973 |  |
| 215 | mint | `CIDAR_Lab_Past_Devices/Logic_04/Logic_04_fromMINT.json` | timeout | 1800.034 | exceeded 1800s |
| 216 | mint | `CIDAR_Lab_Past_Devices/Mfd_005_Chip/Mfd_005_Chip_fromMINT.json` | success | 43.556 |  |
| 217 | mint | `CIDAR_Lab_Past_Devices/Microalgal_Bioassay/Microalgal_Bioassay_fromMINT.json` | success | 62.258 |  |
| 218 | mint | `CIDAR_Lab_Past_Devices/Microdroplet/Microdroplet_fromMINT.json` | timeout | 1800.033 | exceeded 1800s |
| 219 | mint | `CIDAR_Lab_Past_Devices/Microreactor/Microreactor_fromMINT.json` | success | 372.222 |  |
| 220 | mint | `CIDAR_Lab_Past_Devices/Mix_Incubate_Express/Mix_Incubate_Express_fromMINT.json` | success | 1.472 |  |
| 221 | mint | `CIDAR_Lab_Past_Devices/Mixer_Trap_Simple/Mixer_Trap_Simple_fromMINT.json` | success | 1.133 |  |
| 222 | mint | `CIDAR_Lab_Past_Devices/Multi_Input/Multi_Input_fromMINT.json` | timeout | 1800.042 | exceeded 1800s |
| 223 | mint | `CIDAR_Lab_Past_Devices/MUX_96_Chambers/MUX_96_Chambers_fromMINT.json` | fail | 1799.916 | TimeoutError: case-level placement/routing budget exhausted; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__CIDAR_Lab_Past_Devices__MUX_96_Chambers__MUX_96_Chambers_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=1 message=Time limit reached. (HiGHS Status 13: model_status is Time limit reached; primal_status is At lower/fixed bound) |
| 224 | mint | `CIDAR_Lab_Past_Devices/Net_MUX/Net_MUX_fromMINT.json` | timeout | 1800.034 | exceeded 1800s |
| 225 | mint | `CIDAR_Lab_Past_Devices/Nine_To_One_MUX/Nine_To_One_MUX_fromMINT.json` | timeout | 1800.034 | exceeded 1800s |
| 226 | mint | `CIDAR_Lab_Past_Devices/Number_Declarations/Number_Declarations_fromMINT.json` | success | 1.019 |  |
| 227 | mint | `CIDAR_Lab_Past_Devices/Olfactory/Olfactory_fromMINT.json` | success | 95.386 |  |
| 228 | mint | `CIDAR_Lab_Past_Devices/Pump_Passthrough/Pump_Passthrough_fromMINT.json` | success | 1.019 |  |
| 229 | mint | `CIDAR_Lab_Past_Devices/Ring/Ring_fromMINT.json` | success | 1.720 |  |
| 230 | mint | `CIDAR_Lab_Past_Devices/Root_Chip/Root_Chip_fromMINT.json` | timeout | 1800.033 | exceeded 1800s |
| 231 | mint | `CIDAR_Lab_Past_Devices/Rotary_16/Rotary_16_fromMINT.json` | timeout | 1800.077 | exceeded 1800s |
| 232 | mint | `CIDAR_Lab_Past_Devices/Rotary_Cells/Rotary_Cells_fromMINT.json` | success | 1465.903 |  |
| 233 | mint | `CIDAR_Lab_Past_Devices/Seeding/Seeding_fromMINT.json` | timeout | 1800.046 | exceeded 1800s |
| 234 | mint | `CIDAR_Lab_Past_Devices/Single_Port/Single_Port_fromMINT.json` | success | 1.019 |  |
| 235 | mint | `CIDAR_Lab_Past_Devices/Three_Reagent_Mix/Three_Reagent_Mix_fromMINT.json` | success | 70.115 |  |
| 236 | mint | `Constraints/Array_Constraint/Array_Constraint_fromMINT.json` | fail | 1798.569 | TimeoutError: case-level placement/routing budget exhausted; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Constraints__Array_Constraint__Array_Constraint_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=1 message=Time limit reached. (HiGHS Status 13: model_status is Time limit reached; primal_status is At lower/fixed bound) |
| 237 | mint | `Constraints/Orthogonal_Constraint/Orthogonal_Constraint_fromMINT.json` | success | 1.171 |  |
| 238 | mint | `Constraints/Orthogonal_Constraint_Large/Orthogonal_Constraint_Large_fromMINT.json` | fail | 301.214 | RuntimeError: DRC violations: channel_spacing: channels of connections 'c_1' and 'c_12' violate the 1000 edge-to-edge clearance; channel_spacing: channels of connections 'c_2' and 'c_12' violate the 1000 edge-to-edge clearance; channel_spacing: channels of connections 'c_3' and 'c_12' violate the 1000 edge-to-edge clearance |
| 239 | mint | `Constraints/Position_Constraint/Position_Constraint_fromMINT.json` | success | 1.069 |  |
| 240 | mint | `Constraints/Relative_Orientation_Constraint/Relative_Orientation_Constraint_fromMINT.json` | success | 1.169 |  |
| 241 | mint | `Constraints/Tree_Constraint/Tree_Constraint_fromMINT.json` | success | 2.273 |  |
| 242 | mint | `COVID/Aj_Rtpcr_8_Primer/Aj_Rtpcr_8_Primer_fromMINT.json` | timeout | 1800.033 | exceeded 1800s |
| 243 | mint | `COVID/Arize/Arize_fromMINT.json` | timeout | 1800.080 | exceeded 1800s |
| 244 | mint | `COVID/Covid_Crispr/Covid_Crispr_fromMINT.json` | success | 1.169 |  |
| 245 | mint | `COVID/Crispr/Crispr_fromMINT.json` | fail | 59.918 | RuntimeError: DRC violations: channel_spacing: channels of connections 'channel_8' and 'channel_10' violate the 1000 edge-to-edge clearance |
| 246 | mint | `COVID/Detectr/Detectr_fromMINT.json` | success | 484.719 |  |
| 247 | mint | `COVID/Elisa/Elisa_fromMINT.json` | success | 23.388 |  |
| 248 | mint | `COVID/Gel_Electrophoresis/Gel_Electrophoresis_fromMINT.json` | success | 287.341 |  |
| 249 | mint | `COVID/Hybri_Detect/Hybri_Detect_fromMINT.json` | success | 10.149 |  |
| 250 | mint | `COVID/Part_1_Rna_Prep/Part_1_Rna_Prep_fromMINT.json` | success | 8.453 |  |
| 251 | mint | `COVID/Part_2_Rt_Step/Part_2_Rt_Step_fromMINT.json` | success | 2.725 |  |
| 252 | mint | `COVID/Part_3_Gel/Part_3_Gel_fromMINT.json` | success | 61.806 |  |
| 253 | mint | `COVID/Rt_Pcr/Rt_Pcr_fromMINT.json` | success | 1.074 |  |
| 254 | mint | `Distribute_Expressions/And_Annotation_Test/And_Annotation_Test_fromMINT.json` | fail | 1798.618 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Distribute_Expressions__And_Annotation_Test__And_Annotation_Test_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 255 | mint | `Distribute_Expressions/Dist_Expression_1/Dist_Expression_1_fromMINT.json` | success | 1.029 |  |
| 256 | mint | `Distribute_Expressions/Dist_Expression_2/Dist_Expression_2_fromMINT.json` | success | 1.320 |  |
| 257 | mint | `Distribute_Expressions/Dist_Expression_3/Dist_Expression_3_fromMINT.json` | success | 1.485 |  |
| 258 | mint | `Distribute_Library/Cell_Traps_4/Cell_Traps_4_fromMINT.json` | success | 0.918 |  |
| 259 | mint | `Distribute_Library/Hv_Storage_Grid_04/Hv_Storage_Grid_04_fromMINT.json` | success | 0.928 |  |
| 260 | mint | `Distribute_Library/Hv_Storage_Grid_08/Hv_Storage_Grid_08_fromMINT.json` | success | 0.970 |  |
| 261 | mint | `Distribute_Library/Hv_Storage_Grid_16/Hv_Storage_Grid_16_fromMINT.json` | success | 0.981 |  |
| 262 | mint | `Distribute_Library/Hv_Storage_Grid_32/Hv_Storage_Grid_32_fromMINT.json` | success | 0.968 |  |
| 263 | mint | `Distribute_Library/Hv_Storage_Grid_64/Hv_Storage_Grid_64_fromMINT.json` | success | 0.968 |  |
| 264 | mint | `Distribute_Library/MUX_02_In/MUX_02_In_fromMINT.json` | fail | 1798.494 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Distribute_Library__MUX_02_In__MUX_02_In_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 265 | mint | `Distribute_Library/MUX_02_Out/MUX_02_Out_fromMINT.json` | success | 1.520 |  |
| 266 | mint | `Distribute_Library/MUX_04_In/MUX_04_In_fromMINT.json` | fail | 1798.582 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Distribute_Library__MUX_04_In__MUX_04_In_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 267 | mint | `Distribute_Library/MUX_04_Out/MUX_04_Out_fromMINT.json` | fail | 1798.521 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Distribute_Library__MUX_04_Out__MUX_04_Out_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 268 | mint | `Distribute_Library/MUX_08_In/MUX_08_In_fromMINT.json` | fail | 1798.480 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Distribute_Library__MUX_08_In__MUX_08_In_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 269 | mint | `Distribute_Library/MUX_08_Out/MUX_08_Out_fromMINT.json` | fail | 1798.512 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Distribute_Library__MUX_08_Out__MUX_08_Out_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 270 | mint | `Distribute_Library/MUX_16_In/MUX_16_In_fromMINT.json` | fail | 1798.630 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Distribute_Library__MUX_16_In__MUX_16_In_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 271 | mint | `Distribute_Library/MUX_16_Out/MUX_16_Out_fromMINT.json` | fail | 1798.671 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Distribute_Library__MUX_16_Out__MUX_16_Out_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 272 | mint | `Distribute_Library/MUX_32_In/MUX_32_In_fromMINT.json` | fail | 1798.509 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Distribute_Library__MUX_32_In__MUX_32_In_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 273 | mint | `Distribute_Library/MUX_32_Out/MUX_32_Out_fromMINT.json` | fail | 1798.640 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Distribute_Library__MUX_32_Out__MUX_32_Out_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 274 | mint | `Distribute_Library/MUX_64_In/MUX_64_In_fromMINT.json` | fail | 1798.752 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Distribute_Library__MUX_64_In__MUX_64_In_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 275 | mint | `Distribute_Library/MUX_64_Out/MUX_64_Out_fromMINT.json` | fail | 1798.743 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Distribute_Library__MUX_64_Out__MUX_64_Out_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 276 | mint | `Distribute_Library/Single_Storage_Grid_01/Single_Storage_Grid_01_fromMINT.json` | success | 0.920 |  |
| 277 | mint | `Distribute_Library/Single_Storage_Grid_02/Single_Storage_Grid_02_fromMINT.json` | success | 0.977 |  |
| 278 | mint | `Distribute_Library/Single_Storage_Grid_04/Single_Storage_Grid_04_fromMINT.json` | success | 0.917 |  |
| 279 | mint | `Distribute_Library/Single_Storage_Grid_08/Single_Storage_Grid_08_fromMINT.json` | success | 0.973 |  |
| 280 | mint | `Distribute_Library/Single_Storage_Grid_16/Single_Storage_Grid_16_fromMINT.json` | success | 0.928 |  |
| 281 | mint | `Distribute_Library/Single_Storage_Grid_32/Single_Storage_Grid_32_fromMINT.json` | success | 0.939 |  |
| 282 | mint | `Distribute_Library/Single_Storage_Grid_64/Single_Storage_Grid_64_fromMINT.json` | success | 0.918 |  |
| 283 | mint | `Distribute_Library/Transposer_02/Transposer_02_fromMINT.json` | fail | 1798.577 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Distribute_Library__Transposer_02__Transposer_02_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 284 | mint | `Distribute_Library/Transposer_03/Transposer_03_fromMINT.json` | fail | 1798.472 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Distribute_Library__Transposer_03__Transposer_03_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 285 | mint | `Distribute_Library/Transposer_04/Transposer_04_fromMINT.json` | timeout | 1800.034 | exceeded 1800s |
| 286 | mint | `Distribute_Library/Transposer_08/Transposer_08_fromMINT.json` | success | 0.970 |  |
| 287 | mint | `Distribute_Library/Transposer_16/Transposer_16_fromMINT.json` | success | 0.926 |  |
| 288 | mint | `Distribute_Library/Transposer_32/Transposer_32_fromMINT.json` | success | 0.970 |  |
| 289 | mint | `Distribute_Library/Transposer_64/Transposer_64_fromMINT.json` | success | 0.984 |  |
| 290 | mint | `Drop_Ref/Droplet_Generator_1/Droplet_Generator_1_fromMINT.json` | success | 18.646 |  |
| 291 | mint | `Drop_Ref/Droplet_Generator_2/Droplet_Generator_2_fromMINT.json` | timeout | 1800.034 | exceeded 1800s |
| 292 | mint | `Drop_Ref/Droplet_Generator_3/Droplet_Generator_3_fromMINT.json` | timeout | 1800.050 | exceeded 1800s |
| 293 | mint | `Drop_Ref/Droplet_Generator_4/Droplet_Generator_4_fromMINT.json` | fail | 1799.169 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Drop_Ref__Droplet_Generator_4__Droplet_Generator_4_fromMINT/placement_attempts.json; last error: All 16 deterministic routing orders failed; conflict refinement: conflict refinement stalled with 9 relaxed inter-net conflict(s): channel_5[0] x channel_11[0], channel_5[0] x channel_16[0], channel_6[0] x channel_12[0], channel_6[0] x channel_15[0], channel_6[0] x channel_16[0], channel_7[0] x channel_14[0] \| order 1: No legal route for connection 'channel_6' sink 0 ({'component': 'nozzle_droplet_generator_2', 'port': '3'} -> {'component': 'mixer_3', 'port': '1'}) \| order 2: No legal route for connection 'channel_5' sink 0 ({'component': 'nozzle_droplet_generator_1', 'port': '3'} -> {'component': 'mixer_1', 'port': '1'}) \| order 3: No legal route for connection 'channel_10' sink 0 ({'component': 'mixer_4', 'port': '2'} -> {'component': 'port_6', 'port': '1'}) \| order 4: No legal route for connection 'channel_4' sink 0 ({'component': 'port_5', 'port': '1'} -> {'component': 'nozzle_droplet_generator_2', 'port': '4'}) \| order 5: No legal route for connection 'channel_12' sink 0 ({'component': 'port_8', 'port': '1'} -> {'component': 'nozzle_droplet_generator_2', 'port': '1'}) \| order 6: No legal route for connection 'channel_12' sink 0 ({'component': 'port_8', 'port': '1'} -> {'component': 'nozzle_droplet_generator_2', 'port': '1'}) \| order 7: No legal route for connection 'channel_9' sink 0 ({'component': 'mixer_2', 'port': '2'} -> {'component': 'port_3', 'port': '1'}) \| order 8: No legal route for connection 'channel_11' sink 0 ({'component': 'port_7', 'port': '1'} -> {'component': 'nozzle_droplet_generator_1', 'port': '1'}) \| order 9: No legal route for connection 'channel_9' sink 0 ({'component': 'mixer_2', 'port': '2'} -> {'component': 'port_3', 'port': '1'}) \| order 10: No legal route for connection 'channel_11' sink 0 ({'component': 'port_7', 'port': '1'} -> {'component': 'nozzle_droplet_generator_1', 'port': '1'}) \| order 11: No legal route for connection 'channel_11' sink 0 ({'component': 'port_7', 'port': '1'} -> {'component': 'nozzle_droplet_generator_1', 'port': '1'}) \| order 12: No legal route for connection 'channel_14' sink 0 ({'component': 'port_9', 'port': '1'} -> {'component': 'mixer_4', 'port': '1'}) \| order 13: No legal route for connection 'channel_5' sink 0 ({'component': 'nozzle_droplet_generator_1', 'port': '3'} -> {'component': 'mixer_1', 'port': '1'}) \| order 14: No legal route for connection 'channel_11' sink 0 ({'component': 'port_7', 'port': '1'} -> {'component': 'nozzle_droplet_generator_1', 'port': '1'}) \| order 15: No legal route for connection 'channel_6' sink 0 ({'component': 'nozzle_droplet_generator_2', 'port': '3'} -> {'component': 'mixer_3', 'port': '1'}) \| order 16: No legal route for connection 'channel_5' sink 0 ({'component': 'nozzle_droplet_generator_1', 'port': '3'} -> {'component': 'mixer_1', 'port': '1'}) |
| 294 | mint | `Drop_Ref/Dropx_Test_1/Dropx_Test_1_fromMINT.json` | success | 18.736 |  |
| 295 | mint | `Drop_Ref/Dropx_Test_2/Dropx_Test_2_fromMINT.json` | fail | 5.791 | RuntimeError: DRC violations: channel_spacing: channels of connections 'channel_4' and 'channel_8' violate the 1000 edge-to-edge clearance |
| 296 | mint | `Drop_Ref/Dropx_Test_3/Dropx_Test_3_fromMINT.json` | success | 1294.667 |  |
| 297 | mint | `Drop_Ref/Dropx_Test_4/Dropx_Test_4_fromMINT.json` | success | 16.279 |  |
| 298 | mint | `Drop_Ref/Dx_1/Dx_1_fromMINT.json` | success | 251.883 |  |
| 299 | mint | `Drop_Ref/Dx_10/Dx_10_fromMINT.json` | success | 8.438 |  |
| 300 | mint | `Drop_Ref/Dx_10_Ref/Dx_10_Ref_fromMINT.json` | success | 3.689 |  |
| 301 | mint | `Drop_Ref/Dx_11/Dx_11_fromMINT.json` | success | 207.704 |  |
| 302 | mint | `Drop_Ref/Dx_11_Ref/Dx_11_Ref_fromMINT.json` | success | 319.253 |  |
| 303 | mint | `Drop_Ref/Dx_12/Dx_12_fromMINT.json` | fail | 28.291 | RuntimeError: DRC violations: channel_spacing: channels of connections 'channel_8' and 'channel_10' violate the 1000 edge-to-edge clearance |
| 304 | mint | `Drop_Ref/Dx_12_Ref/Dx_12_Ref_fromMINT.json` | success | 70.046 |  |
| 305 | mint | `Drop_Ref/Dx_13/Dx_13_fromMINT.json` | fail | 487.804 | RuntimeError: DRC violations: channel_spacing: channels of connections 'channel_2' and 'channel_16' violate the 1000 edge-to-edge clearance |
| 306 | mint | `Drop_Ref/Dx_13_Ref/Dx_13_Ref_fromMINT.json` | timeout | 1800.033 | exceeded 1800s |
| 307 | mint | `Drop_Ref/Dx_14/Dx_14_fromMINT.json` | fail | 37.979 | RuntimeError: DRC violations: channel_spacing: channels of connections 'channel_4' and 'channel_5' violate the 1000 edge-to-edge clearance |
| 308 | mint | `Drop_Ref/Dx_14_Ref/Dx_14_Ref_fromMINT.json` | fail | 167.713 | RuntimeError: DRC violations: channel_spacing: channels of connections 'channel_mixed_2' and 'channel_incubate1' violate the 1000 edge-to-edge clearance |
| 309 | mint | `Drop_Ref/Dx_15/Dx_15_fromMINT.json` | success | 40.807 |  |
| 310 | mint | `Drop_Ref/Dx_15_Ref/Dx_15_Ref_fromMINT.json` | success | 1.483 |  |
| 311 | mint | `Drop_Ref/Dx_1_Ref/Dx_1_Ref_fromMINT.json` | success | 90.917 |  |
| 312 | mint | `Drop_Ref/Dx_2/Dx_2_fromMINT.json` | fail | 97.361 | RuntimeError: DRC violations: channel_spacing: channels of connections 'channel_3' and 'channel_8' violate the 1000 edge-to-edge clearance; channel_spacing: channels of connections 'channel_3' and 'channel_9' violate the 1000 edge-to-edge clearance |
| 313 | mint | `Drop_Ref/Dx_2_Ref/Dx_2_Ref_fromMINT.json` | timeout | 1800.017 | exceeded 1800s |
| 314 | mint | `Drop_Ref/Dx_3/Dx_3_fromMINT.json` | success | 81.529 |  |
| 315 | mint | `Drop_Ref/Dx_3_Ref/Dx_3_Ref_fromMINT.json` | success | 39.089 |  |
| 316 | mint | `Drop_Ref/Dx_4/Dx_4_fromMINT.json` | success | 694.047 |  |
| 317 | mint | `Drop_Ref/Dx_4_Ref/Dx_4_Ref_fromMINT.json` | success | 588.039 |  |
| 318 | mint | `Drop_Ref/Dx_5/Dx_5_fromMINT.json` | success | 179.531 |  |
| 319 | mint | `Drop_Ref/Dx_5_Ref/Dx_5_Ref_fromMINT.json` | success | 161.130 |  |
| 320 | mint | `Drop_Ref/Dx_6/Dx_6_fromMINT.json` | success | 30.582 |  |
| 321 | mint | `Drop_Ref/Dx_6_Ref/Dx_6_Ref_fromMINT.json` | success | 8.459 |  |
| 322 | mint | `Drop_Ref/Dx_7/Dx_7_fromMINT.json` | timeout | 1800.044 | exceeded 1800s |
| 323 | mint | `Drop_Ref/Dx_7_Ref/Dx_7_Ref_fromMINT.json` | timeout | 1800.034 | exceeded 1800s |
| 324 | mint | `Drop_Ref/Dx_8/Dx_8_fromMINT.json` | timeout | 1800.044 | exceeded 1800s |
| 325 | mint | `Drop_Ref/Dx_8_Ref/Dx_8_Ref_fromMINT.json` | timeout | 1800.052 | exceeded 1800s |
| 326 | mint | `Drop_Ref/Dx_9/Dx_9_fromMINT.json` | success | 1447.365 |  |
| 327 | mint | `Drop_Ref/Dx_9_Ref/Dx_9_Ref_fromMINT.json` | timeout | 1800.033 | exceeded 1800s |
| 328 | mint | `Expressions/Expression_1/Expression_1_fromMINT.json` | fail | 5.747 | RuntimeError: DRC violations: channel_spacing: channels of connections 'channel_4' and 'channel_8' violate the 1000 edge-to-edge clearance |
| 329 | mint | `Expressions/Expression_10/Expression_10_fromMINT.json` | success | 4.747 |  |
| 330 | mint | `Expressions/Expression_11/Expression_11_fromMINT.json` | success | 1.072 |  |
| 331 | mint | `Expressions/Expression_12/Expression_12_fromMINT.json` | timeout | 1800.033 | exceeded 1800s |
| 332 | mint | `Expressions/Expression_13/Expression_13_fromMINT.json` | success | 1.070 |  |
| 333 | mint | `Expressions/Expression_14/Expression_14_fromMINT.json` | timeout | 1800.066 | exceeded 1800s |
| 334 | mint | `Expressions/Expression_15/Expression_15_fromMINT.json` | success | 1147.589 |  |
| 335 | mint | `Expressions/Expression_2/Expression_2_fromMINT.json` | success | 9.565 |  |
| 336 | mint | `Expressions/Expression_3/Expression_3_fromMINT.json` | success | 3.526 |  |
| 337 | mint | `Expressions/Expression_4/Expression_4_fromMINT.json` | success | 5.635 |  |
| 338 | mint | `Expressions/Expression_5/Expression_5_fromMINT.json` | success | 25.533 |  |
| 339 | mint | `Expressions/Expression_6/Expression_6_fromMINT.json` | fail | 5.785 | RuntimeError: DRC violations: channel_spacing: channels of connections 'channel_3' and 'channel_4' violate the 1000 edge-to-edge clearance; channel_spacing: channels of connections 'channel_3' and 'channel_9' violate the 1000 edge-to-edge clearance |
| 340 | mint | `Expressions/Expression_7/Expression_7_fromMINT.json` | timeout | 1800.048 | exceeded 1800s |
| 341 | mint | `Expressions/Expression_8/Expression_8_fromMINT.json` | success | 8.744 |  |
| 342 | mint | `Expressions/Expression_9/Expression_9_fromMINT.json` | success | 4.781 |  |
| 343 | mint | `Ghissues/Issue_10/Issue_10_fromMINT.json` | timeout | 1800.034 | exceeded 1800s |
| 344 | mint | `Ghissues/Issue_15/Issue_15_fromMINT.json` | success | 40.837 |  |
| 345 | mint | `Ghissues/Issue_2/Issue_2_fromMINT.json` | success | 0.981 |  |
| 346 | mint | `Ghissues/Issue_3/Issue_3_fromMINT.json` | timeout | 1800.033 | exceeded 1800s |
| 347 | mint | `Ghissues/Issue_6/Issue_6_fromMINT.json` | fail | 1799.207 | TimeoutError: case-level placement/routing budget exhausted; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Ghissues__Issue_6__Issue_6_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=1 message=Time limit reached. (HiGHS Status 13: model_status is Time limit reached; primal_status is At lower/fixed bound) |
| 348 | mint | `Ghissues/Issue_7/Issue_7_fromMINT.json` | fail | 1798.451 | TimeoutError: case-level placement/routing budget exhausted; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Ghissues__Issue_7__Issue_7_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=1 message=Time limit reached. (HiGHS Status 13: model_status is Time limit reached; primal_status is At lower/fixed bound) |
| 349 | mint | `Ghissues/Issue_8/Issue_8_fromMINT.json` | fail | 1798.572 | TimeoutError: case-level placement/routing budget exhausted; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Ghissues__Issue_8__Issue_8_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=1 message=Time limit reached. (HiGHS Status 13: model_status is Time limit reached; primal_status is At lower/fixed bound) |
| 350 | mint | `Ghissues/Issue_9/Issue_9_fromMINT.json` | timeout | 1800.049 | exceeded 1800s |
| 351 | mint | `Graph_Coverage/Tree_Fanin/Tree_Fanin_fromMINT.json` | success | 2.286 |  |
| 352 | mint | `Graph_Coverage/Tree_Fanout/Tree_Fanout_fromMINT.json` | success | 1.979 |  |
| 353 | mint | `Grid/Grid_03/Grid_03_fromMINT.json` | timeout | 1800.066 | exceeded 1800s |
| 354 | mint | `Grid/Grid_04/Grid_04_fromMINT.json` | timeout | 1800.034 | exceeded 1800s |
| 355 | mint | `Grid/Grid_05/Grid_05_fromMINT.json` | fail | 1799.256 | TimeoutError: case-level placement/routing budget exhausted; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Grid__Grid_05__Grid_05_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=1 message=Time limit reached. (HiGHS Status 13: model_status is Time limit reached; primal_status is At lower/fixed bound) |
| 356 | mint | `Grid/Grid_06/Grid_06_fromMINT.json` | fail | 1799.351 | TimeoutError: case-level placement/routing budget exhausted; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Grid__Grid_06__Grid_06_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=1 message=Time limit reached. (HiGHS Status 13: model_status is Time limit reached; primal_status is At lower/fixed bound) |
| 357 | mint | `Grid/Grid_07/Grid_07_fromMINT.json` | fail | 1798.545 | TimeoutError: case-level placement/routing budget exhausted; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Grid__Grid_07__Grid_07_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=1 message=Time limit reached. (HiGHS Status 13: model_status is Time limit reached; primal_status is At lower/fixed bound) |
| 358 | mint | `Grid/Grid_08/Grid_08_fromMINT.json` | fail | 1798.999 | TimeoutError: case-level placement/routing budget exhausted; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Grid__Grid_08__Grid_08_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=1 message=Time limit reached. (HiGHS Status 13: model_status is Time limit reached; primal_status is At lower/fixed bound) |
| 359 | mint | `Grid/Grid_09/Grid_09_fromMINT.json` | fail | 1799.268 | TimeoutError: case-level placement/routing budget exhausted; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Grid__Grid_09__Grid_09_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=1 message=Time limit reached. (HiGHS Status 13: model_status is Time limit reached; primal_status is At lower/fixed bound) |
| 360 | mint | `Grid/Grid_10/Grid_10_fromMINT.json` | fail | 1798.545 | TimeoutError: case-level placement/routing budget exhausted; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Grid__Grid_10__Grid_10_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=1 message=Time limit reached. (HiGHS Status 13: model_status is Time limit reached; primal_status is At lower/fixed bound) |
| 361 | mint | `Grid/Grid_11/Grid_11_fromMINT.json` | fail | 1799.020 | TimeoutError: case-level placement/routing budget exhausted; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Grid__Grid_11__Grid_11_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=1 message=Time limit reached. (HiGHS Status 13: model_status is Time limit reached; primal_status is At lower/fixed bound) |
| 362 | mint | `Grid/Grid_12/Grid_12_fromMINT.json` | fail | 1799.015 | TimeoutError: case-level placement/routing budget exhausted; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Grid__Grid_12__Grid_12_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=1 message=Time limit reached. (HiGHS Status 13: model_status is Time limit reached; primal_status is At lower/fixed bound) |
| 363 | mint | `Grid/Grid_13/Grid_13_fromMINT.json` | fail | 1799.444 | TimeoutError: case-level placement/routing budget exhausted; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Grid__Grid_13__Grid_13_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=1 message=Time limit reached. (HiGHS Status 13: model_status is Time limit reached; primal_status is At lower/fixed bound) |
| 364 | mint | `Grid/Grid_14/Grid_14_fromMINT.json` | timeout | 1800.117 | exceeded 1800s |
| 365 | mint | `Grid/Grid_15/Grid_15_fromMINT.json` | timeout | 1800.120 | exceeded 1800s |
| 366 | mint | `Grid/Grid_16/Grid_16_fromMINT.json` | timeout | 1800.167 | exceeded 1800s |
| 367 | mint | `Literature_Benchmarks/Device_1_Sc_Rna_Seq/Device_1_Sc_Rna_Seq_fromMINT.json` | success | 2.978 |  |
| 368 | mint | `Literature_Benchmarks/Device_2_Artificial_Cells/Device_2_Artificial_Cells_fromMINT.json` | success | 33.322 |  |
| 369 | mint | `Literature_Benchmarks/Device_4_Molecular_Diagnostics/Device_4_Molecular_Diagnostics_fromMINT.json` | success | 5.937 |  |
| 370 | mint | `Literature_Benchmarks/Device_5_Bacteria_Diagnostics/Device_5_Bacteria_Diagnostics_fromMINT.json` | success | 2.974 |  |
| 371 | mint | `Literature_Benchmarks/Device_6_Organic_Chemical_Synthesis/Device_6_Organic_Chemical_Synthesis_fromMINT.json` | timeout | 1800.066 | exceeded 1800s |
| 372 | mint | `Literature_Benchmarks/Device_7_Enzyme_Screening/Device_7_Enzyme_Screening_fromMINT.json` | timeout | 1800.034 | exceeded 1800s |
| 373 | mint | `Mars/Antibiotic_Resistance/Antibiotic_Resistance_fromMINT.json` | success | 8.320 |  |
| 374 | mint | `Mars/Cell_Lysis/Cell_Lysis_fromMINT.json` | success | 2.777 |  |
| 375 | mint | `Mars/Dna_Digest/Dna_Digest_fromMINT.json` | timeout | 1800.035 | exceeded 1800s |
| 376 | mint | `Mars/Fluorescence/Fluorescence_fromMINT.json` | fail | 39.422 | RuntimeError: DRC violations: channel_spacing: channels of connections 'channel_2' and 'channel_8' violate the 1000 edge-to-edge clearance; channel_spacing: channels of connections 'channel_4' and 'channel_10' violate the 1000 edge-to-edge clearance |
| 377 | mint | `Mars/Ligation/Ligation_fromMINT.json` | timeout | 1800.034 | exceeded 1800s |
| 378 | mint | `Mars/Pcr/Pcr_fromMINT.json` | success | 2.096 |  |
| 379 | mint | `Mars/Pre_Processor_Dump/Pre_Processor_Dump_fromMINT.json` | success | 1.271 |  |
| 380 | mint | `Mars/Sorting/Sorting_fromMINT.json` | success | 1.220 |  |
| 381 | mint | `Mars/Transformation/Transformation_fromMINT.json` | timeout | 1800.017 | exceeded 1800s |
| 382 | mint | `Primitive/Capacitance_Sensor/Capacitance_Sensor_fromMINT.json` | success | 1.173 |  |
| 383 | mint | `Primitive/Curved_Mixer/Curved_Mixer_fromMINT.json` | success | 1.180 |  |
| 384 | mint | `Primitive/Diamond_Chamber/Diamond_Chamber_fromMINT.json` | success | 1.173 |  |
| 385 | mint | `Primitive/Droplet_Generator_T/Droplet_Generator_T_fromMINT.json` | success | 1.123 |  |
| 386 | mint | `Primitive/Droplet_Merger/Droplet_Merger_fromMINT.json` | success | 1.188 |  |
| 387 | mint | `Primitive/Droplet_Sorter/Droplet_Sorter_fromMINT.json` | success | 1.275 |  |
| 388 | mint | `Primitive/Filter/Filter_fromMINT.json` | success | 1.173 |  |
| 389 | mint | `Primitive/Flow_Focus_Droplet_Generator/Flow_Focus_Droplet_Generator_fromMINT.json` | success | 1.125 |  |
| 390 | mint | `Primitive/Gradient_Generator/Gradient_Generator_fromMINT.json` | success | 2.077 |  |
| 391 | mint | `Primitive/Long_Cell_Trap/Long_Cell_Trap_fromMINT.json` | success | 1.186 |  |
| 392 | mint | `Primitive/Mixer/Mixer_fromMINT.json` | success | 1.174 |  |
| 393 | mint | `Primitive/Mixer_To_Mixer/Mixer_To_Mixer_fromMINT.json` | success | 1.128 |  |
| 394 | mint | `Primitive/MUX/MUX_fromMINT.json` | fail | 1.473 | RuntimeError: DRC violations: channel_spacing: channels of connections 'ci1' and 'co1' violate the 1000 edge-to-edge clearance |
| 395 | mint | `Primitive/MUX_3d/MUX_3d_fromMINT.json` | success | 1.873 |  |
| 396 | mint | `Primitive/Node/Node_fromMINT.json` | success | 1.171 |  |
| 397 | mint | `Primitive/Nozzle_Droplet_Generator/Nozzle_Droplet_Generator_fromMINT.json` | success | 1.639 |  |
| 398 | mint | `Primitive/Picoinjector/Picoinjector_fromMINT.json` | success | 1.234 |  |
| 399 | mint | `Primitive/Pump/Pump_fromMINT.json` | success | 1.175 |  |
| 400 | mint | `Primitive/Pump_3d/Pump_3d_fromMINT.json` | success | 1.424 |  |
| 401 | mint | `Primitive/Rotary_Mixer/Rotary_Mixer_fromMINT.json` | success | 1.189 |  |
| 402 | mint | `Primitive/Splitter/Splitter_fromMINT.json` | success | 1.172 |  |
| 403 | mint | `Primitive/Square_Cell_Trap/Square_Cell_Trap_fromMINT.json` | success | 1.572 |  |
| 404 | mint | `Primitive/Transposer/Transposer_fromMINT.json` | success | 1.444 |  |
| 405 | mint | `Primitive/Tree/Tree_fromMINT.json` | fail | 2.224 | RuntimeError: DRC violations: channel_spacing: channels of connections 'co2' and 'co3' violate the 1000 edge-to-edge clearance |
| 406 | mint | `Primitive/Valve/Valve_fromMINT.json` | success | 1.471 |  |
| 407 | mint | `Primitive/Y_Tree/Y_Tree_fromMINT.json` | fail | 2.226 | RuntimeError: DRC violations: channel_spacing: channels of connections 'co2' and 'co3' violate the 1000 edge-to-edge clearance |
| 408 | mint | `Protocols/Cell_Sorting/Cell_Sorting_fromMINT.json` | success | 1.171 |  |
| 409 | mint | `Protocols/Directed_Evolution/Directed_Evolution_fromMINT.json` | timeout | 1800.034 | exceeded 1800s |
| 410 | mint | `Technology_Mapping/Cycle/Cycle_fromMINT.json` | success | 2.070 |  |
| 411 | mint | `Technology_Mapping/Instance_Mapping/Instance_Mapping_fromMINT.json` | success | 1.478 |  |
| 412 | mint | `Technology_Mapping/N_Greater_M_Map/N_Greater_M_Map_fromMINT.json` | success | 12.760 |  |
| 413 | mint | `Technology_Mapping/N_Less_M_Map/N_Less_M_Map_fromMINT.json` | success | 2.676 |  |
| 414 | mint | `Technology_Mapping/One_To_One_Mapping/One_To_One_Mapping_fromMINT.json` | success | 1.471 |  |
| 415 | mint | `Technology_Mapping/Tree_Bus/Tree_Bus_fromMINT.json` | success | 464.084 |  |
| 416 | mint | `Technology_Mapping/Tree_Fanin_Mapping/Tree_Fanin_Mapping_fromMINT.json` | success | 44.538 |  |
| 417 | mint | `Technology_Mapping/Tree_Fanout_Mapping_1/Tree_Fanout_Mapping_1_fromMINT.json` | timeout | 1800.038 | exceeded 1800s |
| 418 | mint | `Technology_Mapping/Tree_Fanout_Mapping_2/Tree_Fanout_Mapping_2_fromMINT.json` | timeout | 1800.018 | exceeded 1800s |
| 419 | mint | `Technology_Mapping/Tree_Fanout_Mapping_3/Tree_Fanout_Mapping_3_fromMINT.json` | timeout | 1800.018 | exceeded 1800s |
| 420 | mint | `Technology_Mapping/Tree_Storage_Bus_Mapping/Tree_Storage_Bus_Mapping_fromMINT.json` | timeout | 1800.017 | exceeded 1800s |
| 421 | mint | `Transport_Networks/Distribute_Network_Examples/Distribute_Network_Examples_fromMINT.json` | fail | 1798.634 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Transport_Networks__Distribute_Network_Examples__Distribute_Network_Examples_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 422 | mint | `Transport_Networks/One_To_8/One_To_8_fromMINT.json` | fail | 1798.613 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/mint__Transport_Networks__One_To_8__One_To_8_fromMINT/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 423 | mint | `Transport_Networks/One_To_One/One_To_One_fromMINT.json` | success | 1.230 |  |
| 424 | quick | `constrain_mixer/constrain_mixer_fromLFR.json` | success | 1.122 |  |
| 425 | quick | `constrain_pump/constrain_pump_fromLFR.json` | success | 0.994 |  |
| 426 | quick | `diy_with_mixer_demo/diy_with_mixer_demo_fromLFR.json` | success | 1.342 |  |
| 427 | quick | `DIYcomponent/DIYcomponent_fromLFR.json` | success | 1.037 |  |
| 428 | quick | `droplet_generator/droplet_generator_fromLFR.json` | success | 3.748 |  |
| 429 | quick | `flow_and_control_demo/flow_and_control_demo_fromLFR.json` | success | 2.228 |  |
| 430 | quick | `flow_and_control_demo/flow_and_control_demo_fromMINT.json` | success | 2.236 |  |
| 431 | quick | `flow_only_demo/flow_only_demo_fromLFR.json` | success | 1.120 |  |
| 432 | quick | `flow_only_demo/flow_only_demo_fromMINT.json` | success | 1.070 |  |
| 433 | quick | `import_droplet_reaction/import_droplet_reaction_fromLFR.json` | fail | 1799.908 | TimeoutError: case-level placement/routing budget exhausted; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/quick__import_droplet_reaction__import_droplet_reaction_fromLFR/placement_attempts.json; last error: All 17 deterministic routing orders failed; conflict refinement: conflict refinement stalled with 3 relaxed inter-net conflict(s): channel_1[0] x channel_3[0], channel_6[0] x channel_7[0], channel_8[0] x channel_9[0] \| order 1: No legal route for connection 'channel_3' sink 0 ({'component': 'port_5', 'port': '1'} -> {'component': 'nozzle_droplet_generator_1', 'port': '3'}) \| order 2: No legal route for connection 'channel_3' sink 0 ({'component': 'port_5', 'port': '1'} -> {'component': 'nozzle_droplet_generator_1', 'port': '3'}) \| order 3: No legal route for connection 'channel_7' sink 0 ({'component': 'port_4', 'port': '1'} -> {'component': 'mixer_1', 'port': '1'}) \| order 4: No legal route for connection 'channel_3' sink 0 ({'component': 'port_5', 'port': '1'} -> {'component': 'nozzle_droplet_generator_1', 'port': '3'}) \| order 5: No legal route for connection 'channel_3' sink 0 ({'component': 'port_5', 'port': '1'} -> {'component': 'nozzle_droplet_generator_1', 'port': '3'}) \| order 6: No legal route for connection 'channel_4' sink 0 ({'component': 'port_6', 'port': '1'} -> {'component': 'nozzle_droplet_generator_1', 'port': '1'}) \| order 7: No legal route for connection 'channel_2' sink 0 ({'component': 'mixer_1', 'port': '2'} -> {'component': 'nozzle_droplet_generator_1', 'port': '4'}) \| order 8: No legal route for connection 'channel_2' sink 0 ({'component': 'mixer_1', 'port': '2'} -> {'component': 'nozzle_droplet_generator_1', 'port': '4'}) \| order 9: No legal route for connection 'channel_3' sink 0 ({'component': 'port_5', 'port': '1'} -> {'component': 'nozzle_droplet_generator_1', 'port': '3'}) \| order 10: No legal route for connection 'channel_3' sink 0 ({'component': 'port_5', 'port': '1'} -> {'component': 'nozzle_droplet_generator_1', 'port': '3'}) \| order 11: No legal route for connection 'channel_2' sink 0 ({'component': 'mixer_1', 'port': '2'} -> {'component': 'nozzle_droplet_generator_1', 'port': '4'}) \| order 12: No legal route for connection 'channel_3' sink 0 ({'component': 'port_5', 'port': '1'} -> {'component': 'nozzle_droplet_generator_1', 'port': '3'}) \| order 13: No legal route for connection 'channel_4' sink 0 ({'component': 'port_6', 'port': '1'} -> {'component': 'nozzle_droplet_generator_1', 'port': '1'}) \| order 14: No legal route for connection 'channel_1' sink 0 ({'component': 'nozzle_droplet_generator_1', 'port': '2'} -> {'component': 'reaction_chamber_1', 'port': '1'}) \| order 15: No legal route for connection 'channel_2' sink 0 ({'component': 'mixer_1', 'port': '2'} -> {'component': 'nozzle_droplet_generator_1', 'port': '4'}) \| order 16: No legal route for connection 'channel_2' sink 0 ({'component': 'mixer_1', 'port': '2'} -> {'component': 'nozzle_droplet_generator_1', 'port': '4'}) \| order 17: No legal route for connection 'channel_1' sink 0 ({'component': 'nozzle_droplet_generator_1', 'port': '2'} -> {'component': 'reaction_chamber_1', 'port': '1'}) |
| 434 | quick | `import_mixer_and_incubator/import_mixer_and_incubator_fromLFR.json` | success | 1.290 |  |
| 435 | quick | `import_parallel_premix/import_parallel_premix_fromLFR.json` | success | 6.228 |  |
| 436 | quick | `incubator/incubator_fromLFR.json` | success | 0.969 |  |
| 437 | quick | `long_mixer/long_mixer_fromLFR.json` | success | 1.170 |  |
| 438 | quick | `long_mixer/long_mixer_fromMINT.json` | success | 1.170 |  |
| 439 | quick | `map_droplet/map_droplet_fromLFR.json` | success | 2.174 |  |
| 440 | quick | `map_mixer/map_mixer_fromLFR.json` | success | 1.320 |  |
| 441 | quick | `map_mux/map_mux_fromLFR.json` | success | 4.783 |  |
| 442 | quick | `map_via/map_via_fromLFR.json` | success | 1.032 |  |
| 443 | quick | `map_ytree/map_ytree_fromLFR.json` | fail | 1.629 | RuntimeError: DRC violations: channel_spacing: channels of connections 'channel_1' and 'channel_2' violate the 1000 edge-to-edge clearance; channel_spacing: channels of connections 'channel_1' and 'channel_3' violate the 1000 edge-to-edge clearance |
| 444 | quick | `multi_mixer/multi_mixer_fromLFR.json` | success | 2.422 |  |
| 445 | quick | `multi_mixer/multi_mixer_fromMINT.json` | success | 1.372 |  |
| 446 | quick | `Super_MUX_8/Super_MUX_8_fromMINT.json` | success | 12.269 |  |
| 447 | quick | `test_device_v1_MUX_1to4/test_device_v1_MUX_1to4_fromLFR.json` | success | 52.178 |  |
| 448 | quick | `test_device_v1_MUX_4to1/test_device_v1_MUX_4to1_fromLFR.json` | fail | 1798.622 | TimeoutError: case-level placement/routing search ended without a legal design; attempts saved to /home/student/Desktop/Neptune_2026/Microfluidics-Benchmarks/Results/ilp_full_20261021_161619/artifacts/quick__test_device_v1_MUX_4to1__test_device_v1_MUX_4to1_fromLFR/placement_attempts.json; last error: Placement MILP failed: status=2 message=The problem is infeasible. (HiGHS Status 8: model_status is Infeasible; primal_status is At lower/fixed bound) |
| 449 | quick | `test_device_v2_2MUX/test_device_v2_2MUX_fromLFR.json` | fail | 19.323 | RuntimeError: DRC violations: channel_spacing: channels of connections 'channel_6' and 'channel_9' violate the 1000 edge-to-edge clearance |
| 450 | quick | `test_device_v3_2MUX_fork/test_device_v3_2MUX_fork_fromLFR.json` | fail | 70.902 | RuntimeError: DRC violations: channel_component_clearance: channel of connection 'channel_10' crosses the effective envelope of unrelated component 'port_1' |
| 451 | quick | `test_DIY_crossing/test_DIY_crossing_fromLFR.json` | success | 1.069 |  |
| 452 | quick | `test_DIY_fork/test_DIY_fork_fromLFR.json` | success | 1.069 |  |
| 453 | quick | `three_in_mixer/three_in_mixer_fromLFR.json` | fail | 1.471 | RuntimeError: DRC violations: channel_spacing: channels of connections 'channel_4' and 'channel_5' violate the 1000 edge-to-edge clearance |
| 454 | quick | `two_in_mixer/two_in_mixer_fromLFR.json` | success | 1.068 |  |
