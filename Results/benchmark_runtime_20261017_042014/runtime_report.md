# Benchmark runtime report

Generated: `2026-10-17T11:52:37.362381+00:00`

## TREE-PLACE (PRalgorithm)

- Cases discovered: **454**
- Cases completed: **454**
- Success **311** · Fail **123** · Timeout **20**
- Workers **12** · per-case hard timeout **1800.0s**

## ILP baseline

- Cases discovered: **454**
- Cases completed: **454**
- Success **277** · Fail **105** · Timeout **72**
- Workers **12** · per-case hard timeout **1800.0s**

## Aggregate runtime

| Algorithm | Cases with timing | Total | Mean | Median | p90 | Max |
|---|---:|---:|---:|---:|---:|---:|
| TREE-PLACE | 454 | 10.36 h | 82.17 s | 0.92 s | 3.38 s | 1800.03 s |
| ILP baseline | 454 | 76.61 h | 607.50 s | 24.13 s | 1800.04 s | 1800.27 s |

> Totals are the sum of per-case wall times — i.e. the CPU-time-equivalent if the batch had run serially. Divide by the worker count for the observed wall clock.

## Runtime by suite

| Suite | Algorithm | Cases | Total | Mean | Median | Max | success/fail/timeout |
|---|---|---:|---:|---:|---:|---:|---|
| lfr | TREE-PLACE | 158 | 18144.5 s | 114.84 s | 0.92 s | 1800.02 s | 100/48/10 |
| lfr | ILP baseline | 158 | 91214.5 s | 577.31 s | 19.28 s | 1800.07 s | 101/32/25 |
| mint | TREE-PLACE | 265 | 19104.5 s | 72.09 s | 0.92 s | 1800.03 s | 180/75/10 |
| mint | ILP baseline | 265 | 180575.0 s | 681.41 s | 60.47 s | 1800.27 s | 149/70/46 |
| quick | TREE-PLACE | 31 | 54.4 s | 1.75 s | 0.93 s | 10.37 s | 31/0/0 |
| quick | ILP baseline | 31 | 4016.0 s | 129.55 s | 1.35 s | 1800.02 s | 27/3/1 |

## Slowest cases — TREE-PLACE

| # | Case | Suite | Status | Wall time (s) |
|---:|---|---|---|---:|
| 1 | `mint__Distribute_Library__MUX_32_Out__MUX_32_Out_fromMINT` | mint | timeout | 1800.03 |
| 2 | `mint__Distribute_Library__MUX_64_Out__MUX_64_Out_fromMINT` | mint | timeout | 1800.02 |
| 3 | `mint__Distribute_Library__MUX_64_In__MUX_64_In_fromMINT` | mint | timeout | 1800.02 |
| 4 | `lfr__Distribute_Library__MUX_32_In__MUX_32_In_fromLFR` | lfr | timeout | 1800.02 |
| 5 | `mint__Distribute_Library__MUX_16_Out__MUX_16_Out_fromMINT` | mint | timeout | 1800.02 |
| 6 | `mint__Transport_Networks__Distribute_Network_Examples__Distribute_Network_Examples_fromMINT` | mint | timeout | 1800.02 |
| 7 | `lfr__Distribute_Library__MUX_08_Out__MUX_08_Out_fromLFR` | lfr | timeout | 1800.02 |
| 8 | `lfr__Distribute_Library__MUX_16_Out__MUX_16_Out_fromLFR` | lfr | timeout | 1800.02 |
| 9 | `lfr__Distribute_Library__MUX_64_Out__MUX_64_Out_fromLFR` | lfr | timeout | 1800.02 |
| 10 | `mint__Distribute_Library__MUX_32_In__MUX_32_In_fromMINT` | mint | timeout | 1800.02 |
| 11 | `lfr__Distribute_Library__MUX_08_In__MUX_08_In_fromLFR` | lfr | timeout | 1800.02 |
| 12 | `mint__Distribute_Library__MUX_16_In__MUX_16_In_fromMINT` | mint | timeout | 1800.02 |
| 13 | `lfr__Distribute_Library__MUX_16_In__MUX_16_In_fromLFR` | lfr | timeout | 1800.02 |
| 14 | `lfr__Distribute_Library__MUX_32_Out__MUX_32_Out_fromLFR` | lfr | timeout | 1800.02 |
| 15 | `lfr__Distribute_Library__MUX_64_In__MUX_64_In_fromLFR` | lfr | timeout | 1800.02 |
| 16 | `lfr__Transport_Networks__One_To_8__One_To_8_fromLFR` | lfr | timeout | 1800.02 |
| 17 | `mint__Distribute_Library__MUX_08_Out__MUX_08_Out_fromMINT` | mint | timeout | 1800.02 |
| 18 | `mint__Distribute_Library__MUX_08_In__MUX_08_In_fromMINT` | mint | timeout | 1800.01 |
| 19 | `mint__Transport_Networks__One_To_8__One_To_8_fromMINT` | mint | timeout | 1800.01 |
| 20 | `lfr__Transport_Networks__Distribute_Network_Examples__Distribute_Network_Examples_fromLFR` | lfr | timeout | 1800.01 |
| 21 | `mint__Base__Super_MUX_1024__Super_MUX_1024_fromMINT` | mint | success | 306.90 |
| 22 | `mint__Base__Test_MUX_01__Test_MUX_01_fromMINT` | mint | success | 260.27 |
| 23 | `mint__Base__Super_MUX_512__Super_MUX_512_fromMINT` | mint | success | 119.50 |
| 24 | `mint__Base__Super_MUX_256__Super_MUX_256_fromMINT` | mint | success | 48.86 |
| 25 | `mint__Base__Net_Valve_Test__Net_Valve_Test_fromMINT` | mint | success | 37.17 |

## Slowest cases — ILP baseline

| # | Case | Suite | Status | Wall time (s) |
|---:|---|---|---|---:|
| 1 | `mint__Base__Super_MUX_1024__Super_MUX_1024_fromMINT` | mint | timeout | 1800.27 |
| 2 | `mint__Grid__Grid_15__Grid_15_fromMINT` | mint | timeout | 1800.13 |
| 3 | `mint__Base__Super_MUX_512__Super_MUX_512_fromMINT` | mint | timeout | 1800.13 |
| 4 | `mint__Grid__Grid_14__Grid_14_fromMINT` | mint | timeout | 1800.12 |
| 5 | `mint__Grid__Grid_12__Grid_12_fromMINT` | mint | timeout | 1800.12 |
| 6 | `mint__COVID__Arize__Arize_fromMINT` | mint | timeout | 1800.08 |
| 7 | `mint__CIDAR_Lab_Past_Devices__Dna_Synthesizer__Dna_Synthesizer_fromMINT` | mint | timeout | 1800.07 |
| 8 | `lfr__Literature_Benchmarks__Device_7_Enzyme_Screening__Device_7_Enzyme_Screening_fromLFR` | lfr | timeout | 1800.07 |
| 9 | `lfr__CIDAR_Lab_Past_Devices__Root_Chip__Root_Chip_fromLFR` | lfr | timeout | 1800.07 |
| 10 | `lfr__CIDAR_Lab_Past_Devices__Rotary_Cells__Rotary_Cells_fromLFR` | lfr | timeout | 1800.07 |
| 11 | `lfr__CIDAR_Lab_Past_Devices__Logic_04__Logic_04_fromLFR` | lfr | timeout | 1800.07 |
| 12 | `mint__Expressions__Expression_14__Expression_14_fromMINT` | mint | timeout | 1800.07 |
| 13 | `mint__Grid__Grid_03__Grid_03_fromMINT` | mint | timeout | 1800.07 |
| 14 | `mint__Grid__Grid_04__Grid_04_fromMINT` | mint | timeout | 1800.07 |
| 15 | `mint__Drop_Ref__Dx_8__Dx_8_fromMINT` | mint | timeout | 1800.05 |
| 16 | `mint__Drop_Ref__Droplet_Generator_3__Droplet_Generator_3_fromMINT` | mint | timeout | 1800.05 |
| 17 | `mint__Drop_Ref__Dx_7_Ref__Dx_7_Ref_fromMINT` | mint | timeout | 1800.05 |
| 18 | `mint__Literature_Benchmarks__Device_6_Organic_Chemical_Synthesis__Device_6_Organic_Chemical_Synthesis_fromMINT` | mint | timeout | 1800.05 |
| 19 | `mint__CIDAR_Lab_Past_Devices__Nine_To_One_MUX__Nine_To_One_MUX_fromMINT` | mint | timeout | 1800.05 |
| 20 | `mint__COVID__Aj_Rtpcr_8_Primer__Aj_Rtpcr_8_Primer_fromMINT` | mint | timeout | 1800.05 |
| 21 | `mint__CIDAR_Lab_Past_Devices__Multi_Input__Multi_Input_fromMINT` | mint | timeout | 1800.05 |
| 22 | `mint__Ghissues__Issue_9__Issue_9_fromMINT` | mint | timeout | 1800.05 |
| 23 | `mint__CIDAR_Lab_Past_Devices__Chemostat_Chip__Chemostat_Chip_fromMINT` | mint | timeout | 1800.05 |
| 24 | `mint__CIDAR_Lab_Past_Devices__Incubator__Incubator_fromMINT` | mint | timeout | 1800.05 |
| 25 | `mint__CIDAR_Lab_Past_Devices__Droplet_Merger_Simple__Droplet_Merger_Simple_fromMINT` | mint | timeout | 1800.04 |

## Per-case runtime

| # | Case | Suite | TREE status | TREE wall (s) | ILP status | ILP wall (s) | Ratio TREE/ILP |
|---:|---|---|---|---:|---|---:|---:|
| 1 | `lfr__CIDAR_Lab_Past_Devices__Chemostat_Chip__Chemostat_Chip_fromLFR` | lfr | fail | 0.28 | timeout | 1800.04 | 0.000 |
| 2 | `lfr__CIDAR_Lab_Past_Devices__Dna_Synthesizer__Dna_Synthesizer_fromLFR` | lfr | fail | 0.27 | timeout | 1800.04 | 0.000 |
| 3 | `lfr__CIDAR_Lab_Past_Devices__Dual_Lane_Droplet__Dual_Lane_Droplet_fromLFR` | lfr | success | 1.74 | success | 6.09 | 0.285 |
| 4 | `lfr__CIDAR_Lab_Past_Devices__Genetic_Clock_Testing_Tool__Genetic_Clock_Testing_Tool_fromLFR` | lfr | fail | 0.23 | success | 6.25 | 0.037 |
| 5 | `lfr__CIDAR_Lab_Past_Devices__Glycoform__Glycoform_fromLFR` | lfr | success | 1.38 | success | 161.42 | 0.009 |
| 6 | `lfr__CIDAR_Lab_Past_Devices__Grad_Cells__Grad_Cells_fromLFR` | lfr | fail | 0.23 | success | 197.34 | 0.001 |
| 7 | `lfr__CIDAR_Lab_Past_Devices__Gradient__Gradient_fromLFR` | lfr | fail | 0.27 | fail | 1798.87 | 0.000 |
| 8 | `lfr__CIDAR_Lab_Past_Devices__Hasty_Cell_Traps__Hasty_Cell_Traps_fromLFR` | lfr | fail | 0.27 | success | 3.48 | 0.079 |
| 9 | `lfr__CIDAR_Lab_Past_Devices__Hmlp_Dual_Bank__Hmlp_Dual_Bank_fromLFR` | lfr | fail | 0.27 | fail | 1799.76 | 0.000 |
| 10 | `lfr__CIDAR_Lab_Past_Devices__Incubator__Incubator_fromLFR` | lfr | fail | 0.27 | timeout | 1800.04 | 0.000 |
| 11 | `lfr__CIDAR_Lab_Past_Devices__Inlet_16__Inlet_16_fromLFR` | lfr | fail | 0.27 | fail | 1799.20 | 0.000 |
| 12 | `lfr__CIDAR_Lab_Past_Devices__Kinetics__Kinetics_fromLFR` | lfr | success | 1.17 | success | 2.22 | 0.528 |
| 13 | `lfr__CIDAR_Lab_Past_Devices__Logic_04__Logic_04_fromLFR` | lfr | fail | 0.17 | timeout | 1800.07 | 0.000 |
| 14 | `lfr__CIDAR_Lab_Past_Devices__MUX_96_Chambers__MUX_96_Chambers_fromLFR` | lfr | fail | 0.22 | fail | 1799.07 | 0.000 |
| 15 | `lfr__CIDAR_Lab_Past_Devices__Mfd_005_Chip__Mfd_005_Chip_fromLFR` | lfr | success | 1.22 | success | 62.82 | 0.019 |
| 16 | `lfr__CIDAR_Lab_Past_Devices__Microalgal_Bioassay__Microalgal_Bioassay_fromLFR` | lfr | fail | 0.12 | success | 308.84 | 0.000 |
| 17 | `lfr__CIDAR_Lab_Past_Devices__Microdroplet__Microdroplet_fromLFR` | lfr | fail | 0.17 | timeout | 1800.03 | 0.000 |
| 18 | `lfr__CIDAR_Lab_Past_Devices__Microreactor__Microreactor_fromLFR` | lfr | fail | 0.17 | success | 115.55 | 0.001 |
| 19 | `lfr__CIDAR_Lab_Past_Devices__Mix_Incubate_Express__Mix_Incubate_Express_fromLFR` | lfr | success | 1.12 | success | 1.37 | 0.818 |
| 20 | `lfr__CIDAR_Lab_Past_Devices__Multi_Input__Multi_Input_fromLFR` | lfr | fail | 0.22 | timeout | 1800.03 | 0.000 |
| 21 | `lfr__CIDAR_Lab_Past_Devices__Net_MUX__Net_MUX_fromLFR` | lfr | fail | 0.17 | timeout | 1800.03 | 0.000 |
| 22 | `lfr__CIDAR_Lab_Past_Devices__Nine_To_One_MUX__Nine_To_One_MUX_fromLFR` | lfr | fail | 0.17 | timeout | 1800.03 | 0.000 |
| 23 | `lfr__CIDAR_Lab_Past_Devices__Number_Declarations__Number_Declarations_fromLFR` | lfr | success | 0.92 | success | 0.97 | 0.948 |
| 24 | `lfr__CIDAR_Lab_Past_Devices__Olfactory__Olfactory_fromLFR` | lfr | fail | 0.17 | fail | 130.27 | 0.001 |
| 25 | `lfr__CIDAR_Lab_Past_Devices__Pump_Passthrough__Pump_Passthrough_fromLFR` | lfr | success | 0.72 | success | 0.97 | 0.741 |
| 26 | `lfr__CIDAR_Lab_Past_Devices__Ring__Ring_fromLFR` | lfr | success | 0.97 | success | 1.77 | 0.547 |
| 27 | `lfr__CIDAR_Lab_Past_Devices__Root_Chip__Root_Chip_fromLFR` | lfr | fail | 0.17 | timeout | 1800.07 | 0.000 |
| 28 | `lfr__CIDAR_Lab_Past_Devices__Rotary_16__Rotary_16_fromLFR` | lfr | fail | 0.17 | timeout | 1800.03 | 0.000 |
| 29 | `lfr__CIDAR_Lab_Past_Devices__Rotary_Cells__Rotary_Cells_fromLFR` | lfr | fail | 0.12 | timeout | 1800.07 | 0.000 |
| 30 | `lfr__CIDAR_Lab_Past_Devices__Seeding__Seeding_fromLFR` | lfr | fail | 0.17 | timeout | 1800.03 | 0.000 |
| 31 | `lfr__CIDAR_Lab_Past_Devices__Three_Reagent_Mix__Three_Reagent_Mix_fromLFR` | lfr | fail | 0.17 | success | 47.98 | 0.003 |
| 32 | `lfr__COVID__Aj_Rtpcr_8_Primer__Aj_Rtpcr_8_Primer_fromLFR` | lfr | fail | 0.17 | timeout | 1800.03 | 0.000 |
| 33 | `lfr__COVID__Arize__Arize_fromLFR` | lfr | fail | 0.17 | timeout | 1800.04 | 0.000 |
| 34 | `lfr__COVID__Covid_Crispr__Covid_Crispr_fromLFR` | lfr | success | 0.92 | success | 1.12 | 0.822 |
| 35 | `lfr__COVID__Crispr__Crispr_fromLFR` | lfr | success | 1.22 | success | 12.86 | 0.095 |
| 36 | `lfr__COVID__Detectr__Detectr_fromLFR` | lfr | success | 1.47 | success | 604.33 | 0.002 |
| 37 | `lfr__COVID__Elisa__Elisa_fromLFR` | lfr | fail | 0.17 | success | 47.27 | 0.004 |
| 38 | `lfr__COVID__Gel_Electrophoresis__Gel_Electrophoresis_fromLFR` | lfr | fail | 0.17 | success | 299.81 | 0.001 |
| 39 | `lfr__COVID__Hybri_Detect__Hybri_Detect_fromLFR` | lfr | success | 1.12 | success | 7.39 | 0.151 |
| 40 | `lfr__COVID__Part_1_Rna_Prep__Part_1_Rna_Prep_fromLFR` | lfr | success | 1.17 | success | 4.43 | 0.264 |
| 41 | `lfr__COVID__Part_2_Rt_Step__Part_2_Rt_Step_fromLFR` | lfr | success | 1.17 | fail | 3.12 | 0.375 |
| 42 | `lfr__COVID__Part_3_Gel__Part_3_Gel_fromLFR` | lfr | success | 1.22 | success | 83.13 | 0.015 |
| 43 | `lfr__COVID__Rt_Pcr__Rt_Pcr_fromLFR` | lfr | success | 0.97 | success | 1.07 | 0.910 |
| 44 | `lfr__Distribute_Expressions__And_Annotation_Test__And_Annotation_Test_fromLFR` | lfr | success | 3.38 | fail | 1798.55 | 0.002 |
| 45 | `lfr__Distribute_Expressions__Dist_Expression_1__Dist_Expression_1_fromLFR` | lfr | success | 0.92 | success | 0.97 | 0.949 |
| 46 | `lfr__Distribute_Expressions__Dist_Expression_2__Dist_Expression_2_fromLFR` | lfr | success | 1.02 | success | 1.47 | 0.694 |
| 47 | `lfr__Distribute_Expressions__Dist_Expression_3__Dist_Expression_3_fromLFR` | lfr | success | 0.92 | fail | 1798.67 | 0.001 |
| 48 | `lfr__Distribute_Library__Cell_Traps_4__Cell_Traps_4_fromLFR` | lfr | success | 0.87 | success | 0.97 | 0.900 |
| 49 | `lfr__Distribute_Library__Hv_Storage_Grid_04__Hv_Storage_Grid_04_fromLFR` | lfr | success | 0.92 | success | 0.97 | 0.947 |
| 50 | `lfr__Distribute_Library__Hv_Storage_Grid_08__Hv_Storage_Grid_08_fromLFR` | lfr | success | 0.97 | success | 0.97 | 1.002 |
| 51 | `lfr__Distribute_Library__Hv_Storage_Grid_16__Hv_Storage_Grid_16_fromLFR` | lfr | success | 0.92 | success | 0.97 | 0.945 |
| 52 | `lfr__Distribute_Library__Hv_Storage_Grid_32__Hv_Storage_Grid_32_fromLFR` | lfr | success | 0.93 | success | 0.92 | 1.006 |
| 53 | `lfr__Distribute_Library__Hv_Storage_Grid_64__Hv_Storage_Grid_64_fromLFR` | lfr | success | 0.97 | success | 0.97 | 1.002 |
| 54 | `lfr__Distribute_Library__MUX_02_In__MUX_02_In_fromLFR` | lfr | success | 1.42 | success | 1.97 | 0.721 |
| 55 | `lfr__Distribute_Library__MUX_02_Out__MUX_02_Out_fromLFR` | lfr | success | 1.42 | success | 1.52 | 0.937 |
| 56 | `lfr__Distribute_Library__MUX_04_In__MUX_04_In_fromLFR` | lfr | success | 10.55 | fail | 1798.58 | 0.006 |
| 57 | `lfr__Distribute_Library__MUX_04_Out__MUX_04_Out_fromLFR` | lfr | success | 7.04 | fail | 1798.62 | 0.004 |
| 58 | `lfr__Distribute_Library__MUX_08_In__MUX_08_In_fromLFR` | lfr | timeout | 1800.02 | fail | 1798.58 | 1.001 |
| 59 | `lfr__Distribute_Library__MUX_08_Out__MUX_08_Out_fromLFR` | lfr | timeout | 1800.02 | fail | 1798.55 | 1.001 |
| 60 | `lfr__Distribute_Library__MUX_16_In__MUX_16_In_fromLFR` | lfr | timeout | 1800.02 | fail | 1798.46 | 1.001 |
| 61 | `lfr__Distribute_Library__MUX_16_Out__MUX_16_Out_fromLFR` | lfr | timeout | 1800.02 | fail | 1798.60 | 1.001 |
| 62 | `lfr__Distribute_Library__MUX_32_In__MUX_32_In_fromLFR` | lfr | timeout | 1800.02 | fail | 1798.51 | 1.001 |
| 63 | `lfr__Distribute_Library__MUX_32_Out__MUX_32_Out_fromLFR` | lfr | timeout | 1800.02 | fail | 1798.49 | 1.001 |
| 64 | `lfr__Distribute_Library__MUX_64_In__MUX_64_In_fromLFR` | lfr | timeout | 1800.02 | fail | 1798.49 | 1.001 |
| 65 | `lfr__Distribute_Library__MUX_64_Out__MUX_64_Out_fromLFR` | lfr | timeout | 1800.02 | fail | 1798.68 | 1.001 |
| 66 | `lfr__Distribute_Library__Single_Storage_Grid_01__Single_Storage_Grid_01_fromLFR` | lfr | success | 0.87 | success | 0.97 | 0.897 |
| 67 | `lfr__Distribute_Library__Single_Storage_Grid_02__Single_Storage_Grid_02_fromLFR` | lfr | success | 0.87 | success | 0.97 | 0.896 |
| 68 | `lfr__Distribute_Library__Single_Storage_Grid_04__Single_Storage_Grid_04_fromLFR` | lfr | success | 0.87 | success | 0.97 | 0.897 |
| 69 | `lfr__Distribute_Library__Single_Storage_Grid_08__Single_Storage_Grid_08_fromLFR` | lfr | success | 0.87 | success | 0.92 | 0.946 |
| 70 | `lfr__Distribute_Library__Single_Storage_Grid_16__Single_Storage_Grid_16_fromLFR` | lfr | success | 0.87 | success | 0.97 | 0.897 |
| 71 | `lfr__Distribute_Library__Single_Storage_Grid_32__Single_Storage_Grid_32_fromLFR` | lfr | success | 0.87 | success | 0.97 | 0.897 |
| 72 | `lfr__Distribute_Library__Single_Storage_Grid_64__Single_Storage_Grid_64_fromLFR` | lfr | success | 0.87 | success | 0.97 | 0.896 |
| 73 | `lfr__Distribute_Library__Transposer_02__Transposer_02_fromLFR` | lfr | fail | 0.17 | success | 57.46 | 0.003 |
| 74 | `lfr__Distribute_Library__Transposer_03__Transposer_03_fromLFR` | lfr | fail | 0.12 | fail | 1798.61 | 0.000 |
| 75 | `lfr__Distribute_Library__Transposer_04__Transposer_04_fromLFR` | lfr | fail | 0.17 | timeout | 1800.04 | 0.000 |
| 76 | `lfr__Distribute_Library__Transposer_08__Transposer_08_fromLFR` | lfr | success | 0.87 | success | 0.97 | 0.896 |
| 77 | `lfr__Distribute_Library__Transposer_16__Transposer_16_fromLFR` | lfr | success | 0.87 | success | 0.97 | 0.896 |
| 78 | `lfr__Distribute_Library__Transposer_32__Transposer_32_fromLFR` | lfr | success | 0.87 | success | 0.97 | 0.897 |
| 79 | `lfr__Distribute_Library__Transposer_64__Transposer_64_fromLFR` | lfr | success | 0.87 | success | 1.02 | 0.851 |
| 80 | `lfr__Drop_Ref__Droplet_Generator_1__Droplet_Generator_1_fromLFR` | lfr | success | 0.92 | success | 1.02 | 0.899 |
| 81 | `lfr__Drop_Ref__Droplet_Generator_2__Droplet_Generator_2_fromLFR` | lfr | success | 1.17 | success | 24.85 | 0.047 |
| 82 | `lfr__Drop_Ref__Droplet_Generator_3__Droplet_Generator_3_fromLFR` | lfr | fail | 0.17 | timeout | 1800.02 | 0.000 |
| 83 | `lfr__Drop_Ref__Droplet_Generator_4__Droplet_Generator_4_fromLFR` | lfr | fail | 0.17 | success | 67.24 | 0.003 |
| 84 | `lfr__Drop_Ref__Dropx_Test_1__Dropx_Test_1_fromLFR` | lfr | success | 0.87 | success | 1.02 | 0.851 |
| 85 | `lfr__Drop_Ref__Dropx_Test_2__Dropx_Test_2_fromLFR` | lfr | success | 1.02 | success | 7.24 | 0.141 |
| 86 | `lfr__Drop_Ref__Dropx_Test_3__Dropx_Test_3_fromLFR` | lfr | success | 1.07 | success | 11.20 | 0.096 |
| 87 | `lfr__Drop_Ref__Dropx_Test_4__Dropx_Test_4_fromLFR` | lfr | fail | 0.17 | success | 110.01 | 0.002 |
| 88 | `lfr__Drop_Ref__Dx_10__Dx_10_fromLFR` | lfr | success | 1.02 | success | 7.44 | 0.137 |
| 89 | `lfr__Drop_Ref__Dx_11__Dx_11_fromLFR` | lfr | success | 1.17 | fail | 124.27 | 0.009 |
| 90 | `lfr__Drop_Ref__Dx_12__Dx_12_fromLFR` | lfr | success | 1.12 | success | 5.58 | 0.201 |
| 91 | `lfr__Drop_Ref__Dx_13__Dx_13_fromLFR` | lfr | success | 1.27 | fail | 38.04 | 0.033 |
| 92 | `lfr__Drop_Ref__Dx_14__Dx_14_fromLFR` | lfr | fail | 0.17 | success | 61.59 | 0.003 |
| 93 | `lfr__Drop_Ref__Dx_15__Dx_15_fromLFR` | lfr | success | 0.97 | success | 1.62 | 0.599 |
| 94 | `lfr__Drop_Ref__Dx_1__Dx_1_fromLFR` | lfr | success | 1.07 | success | 3.98 | 0.268 |
| 95 | `lfr__Drop_Ref__Dx_2__Dx_2_fromLFR` | lfr | success | 1.12 | success | 3.67 | 0.305 |
| 96 | `lfr__Drop_Ref__Dx_3__Dx_3_fromLFR` | lfr | success | 1.12 | success | 45.00 | 0.025 |
| 97 | `lfr__Drop_Ref__Dx_4__Dx_4_fromLFR` | lfr | fail | 0.17 | success | 736.30 | 0.000 |
| 98 | `lfr__Drop_Ref__Dx_5__Dx_5_fromLFR` | lfr | success | 1.17 | success | 25.55 | 0.046 |
| 99 | `lfr__Drop_Ref__Dx_6__Dx_6_fromLFR` | lfr | success | 1.02 | success | 1.72 | 0.593 |
| 100 | `lfr__Drop_Ref__Dx_7__Dx_7_fromLFR` | lfr | success | 1.12 | success | 100.69 | 0.011 |
| 101 | `lfr__Drop_Ref__Dx_8__Dx_8_fromLFR` | lfr | success | 1.32 | fail | 517.17 | 0.003 |
| 102 | `lfr__Drop_Ref__Dx_9__Dx_9_fromLFR` | lfr | success | 1.12 | success | 62.44 | 0.018 |
| 103 | `lfr__Expressions__Expression_10__Expression_10_fromLFR` | lfr | success | 0.97 | success | 2.63 | 0.369 |
| 104 | `lfr__Expressions__Expression_11__Expression_11_fromLFR` | lfr | success | 0.92 | success | 1.12 | 0.820 |
| 105 | `lfr__Expressions__Expression_12__Expression_12_fromLFR` | lfr | success | 1.57 | success | 1054.87 | 0.002 |
| 106 | `lfr__Expressions__Expression_13__Expression_13_fromLFR` | lfr | success | 0.92 | success | 1.17 | 0.783 |
| 107 | `lfr__Expressions__Expression_14__Expression_14_fromLFR` | lfr | fail | 0.17 | timeout | 1800.04 | 0.000 |
| 108 | `lfr__Expressions__Expression_15__Expression_15_fromLFR` | lfr | success | 1.32 | success | 1235.91 | 0.001 |
| 109 | `lfr__Expressions__Expression_1__Expression_1_fromLFR` | lfr | success | 0.97 | success | 4.18 | 0.232 |
| 110 | `lfr__Expressions__Expression_2__Expression_2_fromLFR` | lfr | success | 0.92 | success | 2.03 | 0.453 |
| 111 | `lfr__Expressions__Expression_3__Expression_3_fromLFR` | lfr | success | 1.02 | success | 7.04 | 0.145 |
| 112 | `lfr__Expressions__Expression_4__Expression_4_fromLFR` | lfr | success | 1.02 | success | 19.98 | 0.051 |
| 113 | `lfr__Expressions__Expression_5__Expression_5_fromLFR` | lfr | success | 1.07 | success | 31.10 | 0.034 |
| 114 | `lfr__Expressions__Expression_6__Expression_6_fromLFR` | lfr | success | 1.12 | fail | 6.79 | 0.165 |
| 115 | `lfr__Expressions__Expression_7__Expression_7_fromLFR` | lfr | success | 1.12 | success | 14.37 | 0.078 |
| 116 | `lfr__Expressions__Expression_8__Expression_8_fromLFR` | lfr | fail | 0.17 | success | 97.14 | 0.002 |
| 117 | `lfr__Expressions__Expression_9__Expression_9_fromLFR` | lfr | success | 0.92 | success | 2.63 | 0.350 |
| 118 | `lfr__Ghissues__Issue_10__Issue_10_fromLFR` | lfr | fail | 0.17 | timeout | 1800.04 | 0.000 |
| 119 | `lfr__Ghissues__Issue_15__Issue_15_fromLFR` | lfr | success | 0.97 | success | 1.62 | 0.600 |
| 120 | `lfr__Ghissues__Issue_2__Issue_2_fromLFR` | lfr | success | 0.87 | success | 0.92 | 0.944 |
| 121 | `lfr__Ghissues__Issue_3__Issue_3_fromLFR` | lfr | fail | 0.17 | timeout | 1800.04 | 0.000 |
| 122 | `lfr__Ghissues__Issue_6__Issue_6_fromLFR` | lfr | fail | 0.17 | fail | 1799.22 | 0.000 |
| 123 | `lfr__Ghissues__Issue_7__Issue_7_fromLFR` | lfr | fail | 0.17 | timeout | 1800.04 | 0.000 |
| 124 | `lfr__Ghissues__Issue_8__Issue_8_fromLFR` | lfr | fail | 0.17 | fail | 1798.53 | 0.000 |
| 125 | `lfr__Ghissues__Issue_9__Issue_9_fromLFR` | lfr | fail | 0.17 | timeout | 1800.03 | 0.000 |
| 126 | `lfr__Graph_Coverage__Tree_Fanin__Tree_Fanin_fromLFR` | lfr | success | 1.07 | success | 2.07 | 0.517 |
| 127 | `lfr__Graph_Coverage__Tree_Fanout__Tree_Fanout_fromLFR` | lfr | success | 1.12 | success | 2.12 | 0.530 |
| 128 | `lfr__Literature_Benchmarks__Device_1_Sc_Rna_Seq__Device_1_Sc_Rna_Seq_fromLFR` | lfr | fail | 0.17 | success | 15.01 | 0.011 |
| 129 | `lfr__Literature_Benchmarks__Device_2_Artificial_Cells__Device_2_Artificial_Cells_fromLFR` | lfr | success | 1.23 | fail | 18.58 | 0.066 |
| 130 | `lfr__Literature_Benchmarks__Device_4_Molecular_Diagnostics__Device_4_Molecular_Diagnostics_fromLFR` | lfr | fail | 0.17 | success | 4.28 | 0.039 |
| 131 | `lfr__Literature_Benchmarks__Device_5_Bacteria_Diagnostics__Device_5_Bacteria_Diagnostics_fromLFR` | lfr | success | 1.23 | success | 2.22 | 0.552 |
| 132 | `lfr__Literature_Benchmarks__Device_6_Organic_Chemical_Synthesis__Device_6_Organic_Chemical_Synthesis_fromLFR` | lfr | success | 2.48 | timeout | 1800.03 | 0.001 |
| 133 | `lfr__Literature_Benchmarks__Device_7_Enzyme_Screening__Device_7_Enzyme_Screening_fromLFR` | lfr | success | 10.75 | timeout | 1800.07 | 0.006 |
| 134 | `lfr__Literature_Benchmarks__library__mip_biosensor__mip_biosensor_fromLFR` | lfr | success | 0.92 | success | 1.07 | 0.858 |
| 135 | `lfr__Mars__Antibiotic_Resistance__Antibiotic_Resistance_fromLFR` | lfr | success | 1.22 | success | 20.64 | 0.059 |
| 136 | `lfr__Mars__Cell_Lysis__Cell_Lysis_fromLFR` | lfr | success | 1.12 | success | 5.89 | 0.191 |
| 137 | `lfr__Mars__Dna_Digest__Dna_Digest_fromLFR` | lfr | success | 1.27 | success | 125.27 | 0.010 |
| 138 | `lfr__Mars__Fluorescence__Fluorescence_fromLFR` | lfr | success | 1.12 | success | 8.55 | 0.131 |
| 139 | `lfr__Mars__Ligation__Ligation_fromLFR` | lfr | success | 1.97 | success | 1464.01 | 0.001 |
| 140 | `lfr__Mars__Pcr__Pcr_fromLFR` | lfr | success | 1.12 | success | 1.77 | 0.632 |
| 141 | `lfr__Mars__Sorting__Sorting_fromLFR` | lfr | success | 0.97 | success | 1.12 | 0.866 |
| 142 | `lfr__Mars__Transformation__Transformation_fromLFR` | lfr | success | 1.07 | success | 3.48 | 0.308 |
| 143 | `lfr__Protocols__Cell_Sorting__Cell_Sorting_fromLFR` | lfr | success | 0.92 | success | 1.07 | 0.859 |
| 144 | `lfr__Protocols__Directed_Evolution__Directed_Evolution_fromLFR` | lfr | fail | 0.17 | timeout | 1800.04 | 0.000 |
| 145 | `lfr__Technology_Mapping__Cycle__Cycle_fromLFR` | lfr | success | 0.97 | fail | 1.53 | 0.635 |
| 146 | `lfr__Technology_Mapping__Instance_Mapping__Instance_Mapping_fromLFR` | lfr | success | 0.87 | success | 1.32 | 0.658 |
| 147 | `lfr__Technology_Mapping__N_Greater_M_Map__N_Greater_M_Map_fromLFR` | lfr | success | 1.07 | success | 2.42 | 0.441 |
| 148 | `lfr__Technology_Mapping__N_Less_M_Map__N_Less_M_Map_fromLFR` | lfr | success | 1.07 | success | 1.87 | 0.571 |
| 149 | `lfr__Technology_Mapping__One_To_One_Mapping__One_To_One_Mapping_fromLFR` | lfr | success | 0.92 | success | 1.37 | 0.671 |
| 150 | `lfr__Technology_Mapping__Tree_Bus__Tree_Bus_fromLFR` | lfr | fail | 0.17 | success | 87.48 | 0.002 |
| 151 | `lfr__Technology_Mapping__Tree_Fanin_Mapping__Tree_Fanin_Mapping_fromLFR` | lfr | success | 1.17 | fail | 2.93 | 0.399 |
| 152 | `lfr__Technology_Mapping__Tree_Fanout_Mapping_1__Tree_Fanout_Mapping_1_fromLFR` | lfr | success | 1.12 | fail | 10.66 | 0.105 |
| 153 | `lfr__Technology_Mapping__Tree_Fanout_Mapping_2__Tree_Fanout_Mapping_2_fromLFR` | lfr | success | 1.12 | success | 1.93 | 0.579 |
| 154 | `lfr__Technology_Mapping__Tree_Fanout_Mapping_3__Tree_Fanout_Mapping_3_fromLFR` | lfr | success | 1.12 | fail | 17.53 | 0.064 |
| 155 | `lfr__Technology_Mapping__Tree_Storage_Bus_Mapping__Tree_Storage_Bus_Mapping_fromLFR` | lfr | fail | 0.12 | timeout | 1800.04 | 0.000 |
| 156 | `lfr__Transport_Networks__Distribute_Network_Examples__Distribute_Network_Examples_fromLFR` | lfr | timeout | 1800.01 | fail | 1798.62 | 1.001 |
| 157 | `lfr__Transport_Networks__One_To_8__One_To_8_fromLFR` | lfr | timeout | 1800.02 | fail | 1798.54 | 1.001 |
| 158 | `lfr__Transport_Networks__One_To_One__One_To_One_fromLFR` | lfr | success | 0.92 | success | 1.27 | 0.723 |
| 159 | `mint__Base__Crossing_H__Crossing_H_fromMINT` | mint | success | 1.82 | fail | 42.09 | 0.043 |
| 160 | `mint__Base__Crossing_V__Crossing_V_fromMINT` | mint | success | 1.98 | fail | 37.78 | 0.052 |
| 161 | `mint__Base__Grad_Gen_H__Grad_Gen_H_fromMINT` | mint | fail | 0.17 | fail | 75.69 | 0.002 |
| 162 | `mint__Base__Grad_Gen_V__Grad_Gen_V_fromMINT` | mint | fail | 0.17 | fail | 70.41 | 0.002 |
| 163 | `mint__Base__Grid_4_Mixer__Grid_4_Mixer_fromMINT` | mint | fail | 0.17 | fail | 1799.05 | 0.000 |
| 164 | `mint__Base__Horizontal_MUX_01__Horizontal_MUX_01_fromMINT` | mint | success | 1.62 | fail | 1.47 | 1.103 |
| 165 | `mint__Base__Logic_Test_01__Logic_Test_01_fromMINT` | mint | success | 1.02 | success | 1.07 | 0.954 |
| 166 | `mint__Base__Logic_Test_02__Logic_Test_02_fromMINT` | mint | success | 1.17 | fail | 3.73 | 0.314 |
| 167 | `mint__Base__Logic_Test_03__Logic_Test_03_fromMINT` | mint | success | 1.37 | success | 18.28 | 0.075 |
| 168 | `mint__Base__Long_Cell_Trap_Two_Port__Long_Cell_Trap_Two_Port_fromMINT` | mint | success | 0.92 | success | 1.07 | 0.859 |
| 169 | `mint__Base__MUX_8__MUX_8_fromMINT` | mint | success | 1.57 | success | 2.42 | 0.649 |
| 170 | `mint__Base__Net_Multi_Test__Net_Multi_Test_fromMINT` | mint | success | 14.06 | fail | 246.21 | 0.057 |
| 171 | `mint__Base__Net_Test__Net_Test_fromMINT` | mint | success | 1.37 | success | 1.93 | 0.712 |
| 172 | `mint__Base__Net_Valve_Test__Net_Valve_Test_fromMINT` | mint | success | 37.17 | fail | 1344.97 | 0.028 |
| 173 | `mint__Base__Node_Long_Cell_Trap_01__Node_Long_Cell_Trap_01_fromMINT` | mint | success | 1.09 | fail | 1798.51 | 0.001 |
| 174 | `mint__Base__Node_Long_Cell_Trap_02__Node_Long_Cell_Trap_02_fromMINT` | mint | success | 1.07 | fail | 1798.61 | 0.001 |
| 175 | `mint__Base__Node_Long_Cell_Trap_03__Node_Long_Cell_Trap_03_fromMINT` | mint | success | 1.07 | fail | 1798.65 | 0.001 |
| 176 | `mint__Base__Node_Long_Cell_Trap_04__Node_Long_Cell_Trap_04_fromMINT` | mint | success | 1.07 | fail | 1798.62 | 0.001 |
| 177 | `mint__Base__Node_Test_01__Node_Test_01_fromMINT` | mint | success | 4.93 | success | 4.88 | 1.010 |
| 178 | `mint__Base__Nonplanar__Nonplanar_fromMINT` | mint | fail | 0.17 | success | 1.12 | 0.148 |
| 179 | `mint__Base__Port_Bank_01__Port_Bank_01_fromMINT` | mint | success | 0.67 | success | 1.07 | 0.624 |
| 180 | `mint__Base__Port_Multi_Connection__Port_Multi_Connection_fromMINT` | mint | fail | 0.17 | success | 1.17 | 0.143 |
| 181 | `mint__Base__Square_Cell_Trap_Chambers__Square_Cell_Trap_Chambers_fromMINT` | mint | fail | 0.17 | timeout | 1800.04 | 0.000 |
| 182 | `mint__Base__Square_Cell_Trap_Ports__Square_Cell_Trap_Ports_fromMINT` | mint | success | 5.98 | success | 26.81 | 0.223 |
| 183 | `mint__Base__Super_MUX_1024__Super_MUX_1024_fromMINT` | mint | success | 306.90 | timeout | 1800.27 | 0.171 |
| 184 | `mint__Base__Super_MUX_128__Super_MUX_128_fromMINT` | mint | success | 20.55 | fail | 1798.65 | 0.011 |
| 185 | `mint__Base__Super_MUX_16__Super_MUX_16_fromMINT` | mint | success | 2.48 | fail | 586.73 | 0.004 |
| 186 | `mint__Base__Super_MUX_256__Super_MUX_256_fromMINT` | mint | success | 48.86 | fail | 1799.28 | 0.027 |
| 187 | `mint__Base__Super_MUX_2__Super_MUX_2_fromMINT` | mint | success | 2.57 | success | 1.08 | 2.388 |
| 188 | `mint__Base__Super_MUX_32__Super_MUX_32_fromMINT` | mint | success | 4.47 | timeout | 1800.03 | 0.003 |
| 189 | `mint__Base__Super_MUX_4__Super_MUX_4_fromMINT` | mint | success | 1.22 | success | 1.42 | 0.859 |
| 190 | `mint__Base__Super_MUX_512__Super_MUX_512_fromMINT` | mint | success | 119.50 | timeout | 1800.13 | 0.066 |
| 191 | `mint__Base__Super_MUX_64__Super_MUX_64_fromMINT` | mint | success | 8.94 | fail | 1798.67 | 0.005 |
| 192 | `mint__Base__Super_MUX_8__Super_MUX_8_fromMINT` | mint | success | 1.67 | fail | 3.33 | 0.502 |
| 193 | `mint__Base__Test_MUX_01__Test_MUX_01_fromMINT` | mint | success | 260.27 | success | 262.01 | 0.993 |
| 194 | `mint__Base__Test_MUX_02__Test_MUX_02_fromMINT` | mint | success | 1.32 | success | 208.13 | 0.006 |
| 195 | `mint__Base__Three_Port_Channel__Three_Port_Channel_fromMINT` | mint | success | 0.87 | success | 1.02 | 0.854 |
| 196 | `mint__Base__Transposer_Test__Transposer_Test_fromMINT` | mint | success | 4.63 | fail | 352.76 | 0.013 |
| 197 | `mint__Base__Tree_Test_01__Tree_Test_01_fromMINT` | mint | success | 2.53 | success | 409.13 | 0.006 |
| 198 | `mint__Base__Tree_Test_02__Tree_Test_02_fromMINT` | mint | success | 0.92 | success | 1.48 | 0.622 |
| 199 | `mint__Base__Tree_Valve_Test__Tree_Valve_Test_fromMINT` | mint | success | 3.58 | success | 39.40 | 0.091 |
| 200 | `mint__CIDAR_Lab_Past_Devices__Chemostat_Chip__Chemostat_Chip_fromMINT` | mint | fail | 0.18 | timeout | 1800.05 | 0.000 |
| 201 | `mint__CIDAR_Lab_Past_Devices__Dna_Synthesizer__Dna_Synthesizer_fromMINT` | mint | fail | 0.17 | timeout | 1800.07 | 0.000 |
| 202 | `mint__CIDAR_Lab_Past_Devices__Droplet_Merger_Simple__Droplet_Merger_Simple_fromMINT` | mint | success | 1.12 | timeout | 1800.04 | 0.001 |
| 203 | `mint__CIDAR_Lab_Past_Devices__Dual_Lane_Droplet__Dual_Lane_Droplet_fromMINT` | mint | success | 1.62 | success | 104.53 | 0.015 |
| 204 | `mint__CIDAR_Lab_Past_Devices__Flow_Focus__Flow_Focus_fromMINT` | mint | success | 0.87 | success | 1.12 | 0.776 |
| 205 | `mint__CIDAR_Lab_Past_Devices__Genetic_Clock_Testing_Tool__Genetic_Clock_Testing_Tool_fromMINT` | mint | fail | 0.12 | success | 4.13 | 0.028 |
| 206 | `mint__CIDAR_Lab_Past_Devices__Glycoform__Glycoform_fromMINT` | mint | success | 1.07 | success | 66.34 | 0.016 |
| 207 | `mint__CIDAR_Lab_Past_Devices__Grad_Cells__Grad_Cells_fromMINT` | mint | fail | 0.17 | success | 38.69 | 0.004 |
| 208 | `mint__CIDAR_Lab_Past_Devices__Gradient__Gradient_fromMINT` | mint | fail | 0.17 | fail | 1798.55 | 0.000 |
| 209 | `mint__CIDAR_Lab_Past_Devices__Grid_02__Grid_02_fromMINT` | mint | fail | 0.17 | fail | 104.39 | 0.002 |
| 210 | `mint__CIDAR_Lab_Past_Devices__Hasty_Cell_Traps__Hasty_Cell_Traps_fromMINT` | mint | fail | 0.17 | success | 17.49 | 0.010 |
| 211 | `mint__CIDAR_Lab_Past_Devices__Hmlp_Dual_Bank__Hmlp_Dual_Bank_fromMINT` | mint | fail | 0.17 | fail | 1799.53 | 0.000 |
| 212 | `mint__CIDAR_Lab_Past_Devices__Incubator__Incubator_fromMINT` | mint | fail | 0.17 | timeout | 1800.05 | 0.000 |
| 213 | `mint__CIDAR_Lab_Past_Devices__Inlet_16__Inlet_16_fromMINT` | mint | fail | 0.17 | fail | 1798.61 | 0.000 |
| 214 | `mint__CIDAR_Lab_Past_Devices__Kinetics__Kinetics_fromMINT` | mint | success | 0.92 | success | 1.97 | 0.467 |
| 215 | `mint__CIDAR_Lab_Past_Devices__Logic_04__Logic_04_fromMINT` | mint | fail | 0.17 | timeout | 1800.04 | 0.000 |
| 216 | `mint__CIDAR_Lab_Past_Devices__MUX_96_Chambers__MUX_96_Chambers_fromMINT` | mint | fail | 0.17 | fail | 1799.33 | 0.000 |
| 217 | `mint__CIDAR_Lab_Past_Devices__Mfd_005_Chip__Mfd_005_Chip_fromMINT` | mint | success | 1.12 | success | 43.42 | 0.026 |
| 218 | `mint__CIDAR_Lab_Past_Devices__Microalgal_Bioassay__Microalgal_Bioassay_fromMINT` | mint | fail | 0.17 | success | 189.87 | 0.001 |
| 219 | `mint__CIDAR_Lab_Past_Devices__Microdroplet__Microdroplet_fromMINT` | mint | fail | 0.17 | timeout | 1800.03 | 0.000 |
| 220 | `mint__CIDAR_Lab_Past_Devices__Microreactor__Microreactor_fromMINT` | mint | fail | 0.17 | success | 300.04 | 0.001 |
| 221 | `mint__CIDAR_Lab_Past_Devices__Mix_Incubate_Express__Mix_Incubate_Express_fromMINT` | mint | success | 0.97 | success | 1.87 | 0.518 |
| 222 | `mint__CIDAR_Lab_Past_Devices__Mixer_Trap_Simple__Mixer_Trap_Simple_fromMINT` | mint | success | 0.87 | success | 1.07 | 0.814 |
| 223 | `mint__CIDAR_Lab_Past_Devices__Multi_Input__Multi_Input_fromMINT` | mint | fail | 0.17 | timeout | 1800.05 | 0.000 |
| 224 | `mint__CIDAR_Lab_Past_Devices__Net_MUX__Net_MUX_fromMINT` | mint | fail | 0.17 | timeout | 1800.03 | 0.000 |
| 225 | `mint__CIDAR_Lab_Past_Devices__Nine_To_One_MUX__Nine_To_One_MUX_fromMINT` | mint | fail | 0.17 | timeout | 1800.05 | 0.000 |
| 226 | `mint__CIDAR_Lab_Past_Devices__Number_Declarations__Number_Declarations_fromMINT` | mint | success | 0.87 | success | 0.99 | 0.879 |
| 227 | `mint__CIDAR_Lab_Past_Devices__Olfactory__Olfactory_fromMINT` | mint | fail | 0.17 | success | 95.50 | 0.002 |
| 228 | `mint__CIDAR_Lab_Past_Devices__Pump_Passthrough__Pump_Passthrough_fromMINT` | mint | success | 0.87 | success | 0.97 | 0.901 |
| 229 | `mint__CIDAR_Lab_Past_Devices__Ring__Ring_fromMINT` | mint | success | 0.92 | success | 1.69 | 0.545 |
| 230 | `mint__CIDAR_Lab_Past_Devices__Root_Chip__Root_Chip_fromMINT` | mint | fail | 0.17 | timeout | 1800.03 | 0.000 |
| 231 | `mint__CIDAR_Lab_Past_Devices__Rotary_16__Rotary_16_fromMINT` | mint | fail | 0.17 | fail | 1799.39 | 0.000 |
| 232 | `mint__CIDAR_Lab_Past_Devices__Rotary_Cells__Rotary_Cells_fromMINT` | mint | fail | 0.17 | success | 1458.79 | 0.000 |
| 233 | `mint__CIDAR_Lab_Past_Devices__Seeding__Seeding_fromMINT` | mint | fail | 0.17 | timeout | 1800.04 | 0.000 |
| 234 | `mint__CIDAR_Lab_Past_Devices__Single_Port__Single_Port_fromMINT` | mint | success | 0.82 | success | 0.97 | 0.845 |
| 235 | `mint__CIDAR_Lab_Past_Devices__Three_Reagent_Mix__Three_Reagent_Mix_fromMINT` | mint | fail | 0.17 | success | 86.17 | 0.002 |
| 236 | `mint__COVID__Aj_Rtpcr_8_Primer__Aj_Rtpcr_8_Primer_fromMINT` | mint | fail | 0.12 | timeout | 1800.05 | 0.000 |
| 237 | `mint__COVID__Arize__Arize_fromMINT` | mint | fail | 0.17 | timeout | 1800.08 | 0.000 |
| 238 | `mint__COVID__Covid_Crispr__Covid_Crispr_fromMINT` | mint | success | 0.93 | success | 1.07 | 0.868 |
| 239 | `mint__COVID__Crispr__Crispr_fromMINT` | mint | success | 1.07 | fail | 60.47 | 0.018 |
| 240 | `mint__COVID__Detectr__Detectr_fromMINT` | mint | success | 1.27 | success | 482.70 | 0.003 |
| 241 | `mint__COVID__Elisa__Elisa_fromMINT` | mint | fail | 0.17 | success | 23.40 | 0.007 |
| 242 | `mint__COVID__Gel_Electrophoresis__Gel_Electrophoresis_fromMINT` | mint | fail | 0.17 | success | 63.94 | 0.003 |
| 243 | `mint__COVID__Hybri_Detect__Hybri_Detect_fromMINT` | mint | success | 1.03 | success | 10.09 | 0.102 |
| 244 | `mint__COVID__Part_1_Rna_Prep__Part_1_Rna_Prep_fromMINT` | mint | success | 1.02 | success | 8.50 | 0.120 |
| 245 | `mint__COVID__Part_2_Rt_Step__Part_2_Rt_Step_fromMINT` | mint | success | 0.97 | success | 2.74 | 0.356 |
| 246 | `mint__COVID__Part_3_Gel__Part_3_Gel_fromMINT` | mint | success | 1.07 | success | 62.32 | 0.017 |
| 247 | `mint__COVID__Rt_Pcr__Rt_Pcr_fromMINT` | mint | success | 0.93 | success | 1.09 | 0.849 |
| 248 | `mint__Constraints__Array_Constraint__Array_Constraint_fromMINT` | mint | success | 4.18 | fail | 1799.86 | 0.002 |
| 249 | `mint__Constraints__Orthogonal_Constraint_Large__Orthogonal_Constraint_Large_fromMINT` | mint | success | 1.42 | fail | 299.34 | 0.005 |
| 250 | `mint__Constraints__Orthogonal_Constraint__Orthogonal_Constraint_fromMINT` | mint | success | 0.97 | success | 1.17 | 0.828 |
| 251 | `mint__Constraints__Position_Constraint__Position_Constraint_fromMINT` | mint | success | 0.87 | success | 1.02 | 0.856 |
| 252 | `mint__Constraints__Relative_Orientation_Constraint__Relative_Orientation_Constraint_fromMINT` | mint | success | 0.93 | success | 1.13 | 0.816 |
| 253 | `mint__Constraints__Tree_Constraint__Tree_Constraint_fromMINT` | mint | success | 0.92 | success | 2.19 | 0.419 |
| 254 | `mint__Distribute_Expressions__And_Annotation_Test__And_Annotation_Test_fromMINT` | mint | success | 3.58 | fail | 1798.67 | 0.002 |
| 255 | `mint__Distribute_Expressions__Dist_Expression_1__Dist_Expression_1_fromMINT` | mint | success | 0.82 | success | 0.97 | 0.851 |
| 256 | `mint__Distribute_Expressions__Dist_Expression_2__Dist_Expression_2_fromMINT` | mint | success | 0.93 | success | 1.39 | 0.669 |
| 257 | `mint__Distribute_Expressions__Dist_Expression_3__Dist_Expression_3_fromMINT` | mint | success | 0.92 | success | 1.47 | 0.625 |
| 258 | `mint__Distribute_Library__Cell_Traps_4__Cell_Traps_4_fromMINT` | mint | success | 0.82 | success | 0.98 | 0.838 |
| 259 | `mint__Distribute_Library__Hv_Storage_Grid_04__Hv_Storage_Grid_04_fromMINT` | mint | success | 0.82 | success | 0.97 | 0.844 |
| 260 | `mint__Distribute_Library__Hv_Storage_Grid_08__Hv_Storage_Grid_08_fromMINT` | mint | success | 0.82 | success | 0.99 | 0.830 |
| 261 | `mint__Distribute_Library__Hv_Storage_Grid_16__Hv_Storage_Grid_16_fromMINT` | mint | success | 0.82 | success | 0.97 | 0.846 |
| 262 | `mint__Distribute_Library__Hv_Storage_Grid_32__Hv_Storage_Grid_32_fromMINT` | mint | success | 0.82 | success | 0.97 | 0.845 |
| 263 | `mint__Distribute_Library__Hv_Storage_Grid_64__Hv_Storage_Grid_64_fromMINT` | mint | success | 0.82 | success | 0.92 | 0.886 |
| 264 | `mint__Distribute_Library__MUX_02_In__MUX_02_In_fromMINT` | mint | success | 1.27 | fail | 1798.67 | 0.001 |
| 265 | `mint__Distribute_Library__MUX_02_Out__MUX_02_Out_fromMINT` | mint | success | 1.27 | success | 1.49 | 0.855 |
| 266 | `mint__Distribute_Library__MUX_04_In__MUX_04_In_fromMINT` | mint | success | 17.47 | fail | 1798.65 | 0.010 |
| 267 | `mint__Distribute_Library__MUX_04_Out__MUX_04_Out_fromMINT` | mint | success | 16.67 | fail | 1798.47 | 0.009 |
| 268 | `mint__Distribute_Library__MUX_08_In__MUX_08_In_fromMINT` | mint | timeout | 1800.01 | fail | 1798.61 | 1.001 |
| 269 | `mint__Distribute_Library__MUX_08_Out__MUX_08_Out_fromMINT` | mint | timeout | 1800.02 | fail | 1798.64 | 1.001 |
| 270 | `mint__Distribute_Library__MUX_16_In__MUX_16_In_fromMINT` | mint | timeout | 1800.02 | fail | 1798.51 | 1.001 |
| 271 | `mint__Distribute_Library__MUX_16_Out__MUX_16_Out_fromMINT` | mint | timeout | 1800.02 | fail | 1798.64 | 1.001 |
| 272 | `mint__Distribute_Library__MUX_32_In__MUX_32_In_fromMINT` | mint | timeout | 1800.02 | fail | 1798.55 | 1.001 |
| 273 | `mint__Distribute_Library__MUX_32_Out__MUX_32_Out_fromMINT` | mint | timeout | 1800.03 | fail | 1798.70 | 1.001 |
| 274 | `mint__Distribute_Library__MUX_64_In__MUX_64_In_fromMINT` | mint | timeout | 1800.02 | fail | 1798.51 | 1.001 |
| 275 | `mint__Distribute_Library__MUX_64_Out__MUX_64_Out_fromMINT` | mint | timeout | 1800.02 | fail | 1798.56 | 1.001 |
| 276 | `mint__Distribute_Library__Single_Storage_Grid_01__Single_Storage_Grid_01_fromMINT` | mint | success | 0.87 | success | 0.94 | 0.931 |
| 277 | `mint__Distribute_Library__Single_Storage_Grid_02__Single_Storage_Grid_02_fromMINT` | mint | success | 0.87 | success | 0.99 | 0.885 |
| 278 | `mint__Distribute_Library__Single_Storage_Grid_04__Single_Storage_Grid_04_fromMINT` | mint | success | 0.82 | success | 0.97 | 0.844 |
| 279 | `mint__Distribute_Library__Single_Storage_Grid_08__Single_Storage_Grid_08_fromMINT` | mint | success | 0.88 | success | 0.97 | 0.906 |
| 280 | `mint__Distribute_Library__Single_Storage_Grid_16__Single_Storage_Grid_16_fromMINT` | mint | success | 0.87 | success | 0.92 | 0.948 |
| 281 | `mint__Distribute_Library__Single_Storage_Grid_32__Single_Storage_Grid_32_fromMINT` | mint | success | 0.83 | success | 0.97 | 0.856 |
| 282 | `mint__Distribute_Library__Single_Storage_Grid_64__Single_Storage_Grid_64_fromMINT` | mint | success | 0.82 | success | 0.97 | 0.851 |
| 283 | `mint__Distribute_Library__Transposer_02__Transposer_02_fromMINT` | mint | fail | 0.17 | fail | 1798.54 | 0.000 |
| 284 | `mint__Distribute_Library__Transposer_03__Transposer_03_fromMINT` | mint | fail | 0.17 | fail | 1798.59 | 0.000 |
| 285 | `mint__Distribute_Library__Transposer_04__Transposer_04_fromMINT` | mint | fail | 0.17 | timeout | 1800.03 | 0.000 |
| 286 | `mint__Distribute_Library__Transposer_08__Transposer_08_fromMINT` | mint | success | 0.82 | success | 0.92 | 0.893 |
| 287 | `mint__Distribute_Library__Transposer_16__Transposer_16_fromMINT` | mint | success | 0.82 | success | 0.94 | 0.875 |
| 288 | `mint__Distribute_Library__Transposer_32__Transposer_32_fromMINT` | mint | success | 0.87 | success | 0.97 | 0.896 |
| 289 | `mint__Distribute_Library__Transposer_64__Transposer_64_fromMINT` | mint | success | 0.82 | success | 0.92 | 0.892 |
| 290 | `mint__Drop_Ref__Droplet_Generator_1__Droplet_Generator_1_fromMINT` | mint | success | 0.92 | success | 18.53 | 0.050 |
| 291 | `mint__Drop_Ref__Droplet_Generator_2__Droplet_Generator_2_fromMINT` | mint | success | 1.18 | timeout | 1800.03 | 0.001 |
| 292 | `mint__Drop_Ref__Droplet_Generator_3__Droplet_Generator_3_fromMINT` | mint | fail | 0.17 | timeout | 1800.05 | 0.000 |
| 293 | `mint__Drop_Ref__Droplet_Generator_4__Droplet_Generator_4_fromMINT` | mint | fail | 0.17 | timeout | 1800.04 | 0.000 |
| 294 | `mint__Drop_Ref__Dropx_Test_1__Dropx_Test_1_fromMINT` | mint | success | 0.92 | success | 18.69 | 0.049 |
| 295 | `mint__Drop_Ref__Dropx_Test_2__Dropx_Test_2_fromMINT` | mint | success | 1.07 | fail | 5.58 | 0.191 |
| 296 | `mint__Drop_Ref__Dropx_Test_3__Dropx_Test_3_fromMINT` | mint | success | 1.13 | success | 1295.93 | 0.001 |
| 297 | `mint__Drop_Ref__Dropx_Test_4__Dropx_Test_4_fromMINT` | mint | fail | 0.17 | success | 16.27 | 0.010 |
| 298 | `mint__Drop_Ref__Dx_10_Ref__Dx_10_Ref_fromMINT` | mint | success | 1.03 | success | 3.59 | 0.288 |
| 299 | `mint__Drop_Ref__Dx_10__Dx_10_fromMINT` | mint | success | 1.02 | success | 8.46 | 0.121 |
| 300 | `mint__Drop_Ref__Dx_11_Ref__Dx_11_Ref_fromMINT` | mint | success | 1.22 | success | 318.81 | 0.004 |
| 301 | `mint__Drop_Ref__Dx_11__Dx_11_fromMINT` | mint | success | 1.17 | success | 204.95 | 0.006 |
| 302 | `mint__Drop_Ref__Dx_12_Ref__Dx_12_Ref_fromMINT` | mint | success | 1.07 | success | 70.02 | 0.015 |
| 303 | `mint__Drop_Ref__Dx_12__Dx_12_fromMINT` | mint | success | 1.07 | success | 128.22 | 0.008 |
| 304 | `mint__Drop_Ref__Dx_13_Ref__Dx_13_Ref_fromMINT` | mint | success | 1.33 | timeout | 1800.04 | 0.001 |
| 305 | `mint__Drop_Ref__Dx_13__Dx_13_fromMINT` | mint | success | 1.27 | fail | 486.20 | 0.003 |
| 306 | `mint__Drop_Ref__Dx_14_Ref__Dx_14_Ref_fromMINT` | mint | fail | 0.17 | success | 887.04 | 0.000 |
| 307 | `mint__Drop_Ref__Dx_14__Dx_14_fromMINT` | mint | fail | 0.17 | fail | 37.55 | 0.004 |
| 308 | `mint__Drop_Ref__Dx_15_Ref__Dx_15_Ref_fromMINT` | mint | success | 0.97 | success | 1.49 | 0.653 |
| 309 | `mint__Drop_Ref__Dx_15__Dx_15_fromMINT` | mint | success | 0.97 | success | 40.81 | 0.024 |
| 310 | `mint__Drop_Ref__Dx_1_Ref__Dx_1_Ref_fromMINT` | mint | success | 1.02 | success | 90.42 | 0.011 |
| 311 | `mint__Drop_Ref__Dx_1__Dx_1_fromMINT` | mint | success | 1.07 | success | 250.95 | 0.004 |
| 312 | `mint__Drop_Ref__Dx_2_Ref__Dx_2_Ref_fromMINT` | mint | success | 1.12 | timeout | 1800.04 | 0.001 |
| 313 | `mint__Drop_Ref__Dx_2__Dx_2_fromMINT` | mint | success | 1.13 | fail | 116.92 | 0.010 |
| 314 | `mint__Drop_Ref__Dx_3_Ref__Dx_3_Ref_fromMINT` | mint | success | 1.07 | success | 38.61 | 0.028 |
| 315 | `mint__Drop_Ref__Dx_3__Dx_3_fromMINT` | mint | success | 1.07 | success | 81.41 | 0.013 |
| 316 | `mint__Drop_Ref__Dx_4_Ref__Dx_4_Ref_fromMINT` | mint | success | 1.22 | success | 586.35 | 0.002 |
| 317 | `mint__Drop_Ref__Dx_4__Dx_4_fromMINT` | mint | fail | 0.17 | success | 683.65 | 0.000 |
| 318 | `mint__Drop_Ref__Dx_5_Ref__Dx_5_Ref_fromMINT` | mint | success | 1.23 | success | 162.98 | 0.007 |
| 319 | `mint__Drop_Ref__Dx_5__Dx_5_fromMINT` | mint | success | 1.18 | success | 179.31 | 0.007 |
| 320 | `mint__Drop_Ref__Dx_6_Ref__Dx_6_Ref_fromMINT` | mint | success | 1.02 | success | 8.56 | 0.119 |
| 321 | `mint__Drop_Ref__Dx_6__Dx_6_fromMINT` | mint | success | 1.03 | success | 30.69 | 0.034 |
| 322 | `mint__Drop_Ref__Dx_7_Ref__Dx_7_Ref_fromMINT` | mint | success | 1.23 | timeout | 1800.05 | 0.001 |
| 323 | `mint__Drop_Ref__Dx_7__Dx_7_fromMINT` | mint | success | 1.22 | timeout | 1800.04 | 0.001 |
| 324 | `mint__Drop_Ref__Dx_8_Ref__Dx_8_Ref_fromMINT` | mint | success | 1.28 | timeout | 1800.04 | 0.001 |
| 325 | `mint__Drop_Ref__Dx_8__Dx_8_fromMINT` | mint | success | 1.28 | timeout | 1800.05 | 0.001 |
| 326 | `mint__Drop_Ref__Dx_9_Ref__Dx_9_Ref_fromMINT` | mint | success | 1.17 | timeout | 1800.04 | 0.001 |
| 327 | `mint__Drop_Ref__Dx_9__Dx_9_fromMINT` | mint | success | 1.12 | success | 1451.26 | 0.001 |
| 328 | `mint__Expressions__Expression_10__Expression_10_fromMINT` | mint | success | 1.02 | success | 4.80 | 0.212 |
| 329 | `mint__Expressions__Expression_11__Expression_11_fromMINT` | mint | success | 0.89 | success | 1.12 | 0.793 |
| 330 | `mint__Expressions__Expression_12__Expression_12_fromMINT` | mint | fail | 0.17 | timeout | 1800.03 | 0.000 |
| 331 | `mint__Expressions__Expression_13__Expression_13_fromMINT` | mint | success | 0.94 | success | 1.07 | 0.876 |
| 332 | `mint__Expressions__Expression_14__Expression_14_fromMINT` | mint | fail | 0.12 | timeout | 1800.07 | 0.000 |
| 333 | `mint__Expressions__Expression_15__Expression_15_fromMINT` | mint | success | 1.24 | success | 1149.60 | 0.001 |
| 334 | `mint__Expressions__Expression_1__Expression_1_fromMINT` | mint | success | 1.07 | fail | 5.73 | 0.186 |
| 335 | `mint__Expressions__Expression_2__Expression_2_fromMINT` | mint | success | 0.97 | success | 9.59 | 0.101 |
| 336 | `mint__Expressions__Expression_3__Expression_3_fromMINT` | mint | success | 1.02 | success | 3.42 | 0.298 |
| 337 | `mint__Expressions__Expression_4__Expression_4_fromMINT` | mint | success | 1.03 | success | 5.58 | 0.185 |
| 338 | `mint__Expressions__Expression_5__Expression_5_fromMINT` | mint | success | 1.03 | success | 25.52 | 0.041 |
| 339 | `mint__Expressions__Expression_6__Expression_6_fromMINT` | mint | success | 1.08 | fail | 5.69 | 0.189 |
| 340 | `mint__Expressions__Expression_7__Expression_7_fromMINT` | mint | fail | 0.17 | timeout | 1800.03 | 0.000 |
| 341 | `mint__Expressions__Expression_8__Expression_8_fromMINT` | mint | fail | 0.17 | success | 8.79 | 0.019 |
| 342 | `mint__Expressions__Expression_9__Expression_9_fromMINT` | mint | success | 1.04 | success | 4.73 | 0.219 |
| 343 | `mint__Ghissues__Issue_10__Issue_10_fromMINT` | mint | fail | 0.17 | timeout | 1800.03 | 0.000 |
| 344 | `mint__Ghissues__Issue_15__Issue_15_fromMINT` | mint | success | 1.04 | fail | 151.62 | 0.007 |
| 345 | `mint__Ghissues__Issue_2__Issue_2_fromMINT` | mint | success | 0.88 | success | 0.92 | 0.953 |
| 346 | `mint__Ghissues__Issue_3__Issue_3_fromMINT` | mint | fail | 0.17 | timeout | 1800.03 | 0.000 |
| 347 | `mint__Ghissues__Issue_6__Issue_6_fromMINT` | mint | fail | 0.17 | fail | 1799.22 | 0.000 |
| 348 | `mint__Ghissues__Issue_7__Issue_7_fromMINT` | mint | fail | 0.18 | fail | 1799.66 | 0.000 |
| 349 | `mint__Ghissues__Issue_8__Issue_8_fromMINT` | mint | fail | 0.17 | fail | 1798.55 | 0.000 |
| 350 | `mint__Ghissues__Issue_9__Issue_9_fromMINT` | mint | fail | 0.17 | timeout | 1800.05 | 0.000 |
| 351 | `mint__Graph_Coverage__Tree_Fanin__Tree_Fanin_fromMINT` | mint | success | 1.14 | success | 2.32 | 0.489 |
| 352 | `mint__Graph_Coverage__Tree_Fanout__Tree_Fanout_fromMINT` | mint | success | 1.08 | success | 1.97 | 0.550 |
| 353 | `mint__Grid__Grid_03__Grid_03_fromMINT` | mint | fail | 0.12 | timeout | 1800.07 | 0.000 |
| 354 | `mint__Grid__Grid_04__Grid_04_fromMINT` | mint | fail | 0.17 | timeout | 1800.07 | 0.000 |
| 355 | `mint__Grid__Grid_05__Grid_05_fromMINT` | mint | fail | 0.17 | fail | 1799.21 | 0.000 |
| 356 | `mint__Grid__Grid_06__Grid_06_fromMINT` | mint | fail | 0.17 | fail | 1799.54 | 0.000 |
| 357 | `mint__Grid__Grid_07__Grid_07_fromMINT` | mint | fail | 0.17 | fail | 1798.69 | 0.000 |
| 358 | `mint__Grid__Grid_08__Grid_08_fromMINT` | mint | fail | 0.17 | fail | 1798.94 | 0.000 |
| 359 | `mint__Grid__Grid_09__Grid_09_fromMINT` | mint | fail | 0.17 | fail | 1799.30 | 0.000 |
| 360 | `mint__Grid__Grid_10__Grid_10_fromMINT` | mint | fail | 0.17 | fail | 1798.59 | 0.000 |
| 361 | `mint__Grid__Grid_11__Grid_11_fromMINT` | mint | fail | 0.17 | fail | 1799.25 | 0.000 |
| 362 | `mint__Grid__Grid_12__Grid_12_fromMINT` | mint | fail | 0.17 | timeout | 1800.12 | 0.000 |
| 363 | `mint__Grid__Grid_13__Grid_13_fromMINT` | mint | fail | 0.17 | fail | 1799.40 | 0.000 |
| 364 | `mint__Grid__Grid_14__Grid_14_fromMINT` | mint | fail | 0.17 | timeout | 1800.12 | 0.000 |
| 365 | `mint__Grid__Grid_15__Grid_15_fromMINT` | mint | fail | 0.17 | timeout | 1800.13 | 0.000 |
| 366 | `mint__Grid__Grid_16__Grid_16_fromMINT` | mint | fail | 0.17 | fail | 1799.11 | 0.000 |
| 367 | `mint__Literature_Benchmarks__Device_1_Sc_Rna_Seq__Device_1_Sc_Rna_Seq_fromMINT` | mint | fail | 0.18 | success | 2.98 | 0.060 |
| 368 | `mint__Literature_Benchmarks__Device_2_Artificial_Cells__Device_2_Artificial_Cells_fromMINT` | mint | success | 1.18 | fail | 15.74 | 0.075 |
| 369 | `mint__Literature_Benchmarks__Device_4_Molecular_Diagnostics__Device_4_Molecular_Diagnostics_fromMINT` | mint | success | 1.08 | success | 6.90 | 0.157 |
| 370 | `mint__Literature_Benchmarks__Device_5_Bacteria_Diagnostics__Device_5_Bacteria_Diagnostics_fromMINT` | mint | success | 1.38 | success | 2.98 | 0.464 |
| 371 | `mint__Literature_Benchmarks__Device_6_Organic_Chemical_Synthesis__Device_6_Organic_Chemical_Synthesis_fromMINT` | mint | success | 2.33 | timeout | 1800.05 | 0.001 |
| 372 | `mint__Literature_Benchmarks__Device_7_Enzyme_Screening__Device_7_Enzyme_Screening_fromMINT` | mint | success | 28.14 | timeout | 1800.04 | 0.016 |
| 373 | `mint__Mars__Antibiotic_Resistance__Antibiotic_Resistance_fromMINT` | mint | success | 1.17 | success | 8.30 | 0.141 |
| 374 | `mint__Mars__Cell_Lysis__Cell_Lysis_fromMINT` | mint | success | 1.07 | success | 2.84 | 0.379 |
| 375 | `mint__Mars__Dna_Digest__Dna_Digest_fromMINT` | mint | success | 1.45 | timeout | 1800.04 | 0.001 |
| 376 | `mint__Mars__Fluorescence__Fluorescence_fromMINT` | mint | success | 1.18 | success | 300.80 | 0.004 |
| 377 | `mint__Mars__Ligation__Ligation_fromMINT` | mint | success | 2.33 | timeout | 1800.03 | 0.001 |
| 378 | `mint__Mars__Pcr__Pcr_fromMINT` | mint | success | 1.12 | success | 2.04 | 0.550 |
| 379 | `mint__Mars__Pre_Processor_Dump__Pre_Processor_Dump_fromMINT` | mint | success | 0.92 | success | 1.24 | 0.739 |
| 380 | `mint__Mars__Sorting__Sorting_fromMINT` | mint | success | 0.97 | success | 1.23 | 0.796 |
| 381 | `mint__Mars__Transformation__Transformation_fromMINT` | mint | success | 1.12 | fail | 1799.92 | 0.001 |
| 382 | `mint__Primitive__Capacitance_Sensor__Capacitance_Sensor_fromMINT` | mint | success | 0.87 | success | 1.09 | 0.797 |
| 383 | `mint__Primitive__Curved_Mixer__Curved_Mixer_fromMINT` | mint | success | 0.88 | success | 1.09 | 0.807 |
| 384 | `mint__Primitive__Diamond_Chamber__Diamond_Chamber_fromMINT` | mint | success | 0.87 | success | 1.17 | 0.742 |
| 385 | `mint__Primitive__Droplet_Generator_T__Droplet_Generator_T_fromMINT` | mint | success | 0.87 | success | 1.15 | 0.762 |
| 386 | `mint__Primitive__Droplet_Merger__Droplet_Merger_fromMINT` | mint | success | 0.88 | success | 1.10 | 0.803 |
| 387 | `mint__Primitive__Droplet_Sorter__Droplet_Sorter_fromMINT` | mint | success | 0.93 | success | 1.22 | 0.761 |
| 388 | `mint__Primitive__Filter__Filter_fromMINT` | mint | success | 0.89 | success | 1.19 | 0.746 |
| 389 | `mint__Primitive__Flow_Focus_Droplet_Generator__Flow_Focus_Droplet_Generator_fromMINT` | mint | success | 0.89 | success | 1.04 | 0.856 |
| 390 | `mint__Primitive__Gradient_Generator__Gradient_Generator_fromMINT` | mint | success | 0.93 | success | 2.10 | 0.444 |
| 391 | `mint__Primitive__Long_Cell_Trap__Long_Cell_Trap_fromMINT` | mint | success | 0.87 | success | 1.14 | 0.767 |
| 392 | `mint__Primitive__MUX_3d__MUX_3d_fromMINT` | mint | success | 0.97 | success | 1.74 | 0.556 |
| 393 | `mint__Primitive__MUX__MUX_fromMINT` | mint | success | 1.18 | fail | 5.83 | 0.202 |
| 394 | `mint__Primitive__Mixer_To_Mixer__Mixer_To_Mixer_fromMINT` | mint | fail | 0.13 | success | 1.14 | 0.114 |
| 395 | `mint__Primitive__Mixer__Mixer_fromMINT` | mint | success | 0.88 | success | 1.12 | 0.781 |
| 396 | `mint__Primitive__Node__Node_fromMINT` | mint | success | 0.87 | success | 1.12 | 0.775 |
| 397 | `mint__Primitive__Nozzle_Droplet_Generator__Nozzle_Droplet_Generator_fromMINT` | mint | success | 0.92 | success | 1.62 | 0.566 |
| 398 | `mint__Primitive__Picoinjector__Picoinjector_fromMINT` | mint | success | 0.92 | success | 1.29 | 0.714 |
| 399 | `mint__Primitive__Pump_3d__Pump_3d_fromMINT` | mint | success | 0.87 | success | 1.40 | 0.625 |
| 400 | `mint__Primitive__Pump__Pump_fromMINT` | mint | success | 7.70 | success | 1.17 | 6.560 |
| 401 | `mint__Primitive__Rotary_Mixer__Rotary_Mixer_fromMINT` | mint | success | 0.87 | success | 1.07 | 0.810 |
| 402 | `mint__Primitive__Splitter__Splitter_fromMINT` | mint | success | 0.92 | success | 1.12 | 0.824 |
| 403 | `mint__Primitive__Square_Cell_Trap__Square_Cell_Trap_fromMINT` | mint | success | 0.92 | success | 1.45 | 0.636 |
| 404 | `mint__Primitive__Transposer__Transposer_fromMINT` | mint | success | 0.93 | success | 1.44 | 0.643 |
| 405 | `mint__Primitive__Tree__Tree_fromMINT` | mint | success | 0.92 | fail | 2.20 | 0.418 |
| 406 | `mint__Primitive__Valve__Valve_fromMINT` | mint | success | 0.87 | success | 1.37 | 0.633 |
| 407 | `mint__Primitive__Y_Tree__Y_Tree_fromMINT` | mint | success | 0.92 | fail | 2.07 | 0.445 |
| 408 | `mint__Protocols__Cell_Sorting__Cell_Sorting_fromMINT` | mint | success | 0.88 | success | 1.10 | 0.804 |
| 409 | `mint__Protocols__Directed_Evolution__Directed_Evolution_fromMINT` | mint | fail | 0.17 | timeout | 1800.04 | 0.000 |
| 410 | `mint__Technology_Mapping__Cycle__Cycle_fromMINT` | mint | success | 0.93 | success | 1.80 | 0.518 |
| 411 | `mint__Technology_Mapping__Instance_Mapping__Instance_Mapping_fromMINT` | mint | success | 0.87 | success | 1.30 | 0.669 |
| 412 | `mint__Technology_Mapping__N_Greater_M_Map__N_Greater_M_Map_fromMINT` | mint | success | 1.08 | success | 3.20 | 0.337 |
| 413 | `mint__Technology_Mapping__N_Less_M_Map__N_Less_M_Map_fromMINT` | mint | success | 1.03 | success | 2.38 | 0.433 |
| 414 | `mint__Technology_Mapping__One_To_One_Mapping__One_To_One_Mapping_fromMINT` | mint | success | 0.89 | success | 1.29 | 0.687 |
| 415 | `mint__Technology_Mapping__Tree_Bus__Tree_Bus_fromMINT` | mint | fail | 0.17 | success | 462.84 | 0.000 |
| 416 | `mint__Technology_Mapping__Tree_Fanin_Mapping__Tree_Fanin_Mapping_fromMINT` | mint | fail | 0.17 | success | 45.24 | 0.004 |
| 417 | `mint__Technology_Mapping__Tree_Fanout_Mapping_1__Tree_Fanout_Mapping_1_fromMINT` | mint | fail | 0.17 | fail | 1799.61 | 0.000 |
| 418 | `mint__Technology_Mapping__Tree_Fanout_Mapping_2__Tree_Fanout_Mapping_2_fromMINT` | mint | success | 1.07 | fail | 1798.74 | 0.001 |
| 419 | `mint__Technology_Mapping__Tree_Fanout_Mapping_3__Tree_Fanout_Mapping_3_fromMINT` | mint | fail | 0.17 | timeout | 1800.02 | 0.000 |
| 420 | `mint__Technology_Mapping__Tree_Storage_Bus_Mapping__Tree_Storage_Bus_Mapping_fromMINT` | mint | fail | 0.17 | timeout | 1800.03 | 0.000 |
| 421 | `mint__Transport_Networks__Distribute_Network_Examples__Distribute_Network_Examples_fromMINT` | mint | timeout | 1800.02 | fail | 1798.52 | 1.001 |
| 422 | `mint__Transport_Networks__One_To_8__One_To_8_fromMINT` | mint | timeout | 1800.01 | fail | 1798.52 | 1.001 |
| 423 | `mint__Transport_Networks__One_To_One__One_To_One_fromMINT` | mint | success | 0.87 | success | 1.32 | 0.656 |
| 424 | `quick__DIYcomponent__DIYcomponent_fromLFR` | quick | success | 0.92 | success | 1.13 | 0.815 |
| 425 | `quick__Super_MUX_8__Super_MUX_8_fromMINT` | quick | success | 1.63 | success | 12.53 | 0.130 |
| 426 | `quick__constrain_mixer__constrain_mixer_fromLFR` | quick | success | 0.88 | success | 1.07 | 0.820 |
| 427 | `quick__constrain_pump__constrain_pump_fromLFR` | quick | success | 7.54 | success | 1.27 | 5.921 |
| 428 | `quick__diy_with_mixer_demo__diy_with_mixer_demo_fromLFR` | quick | success | 0.92 | success | 1.28 | 0.718 |
| 429 | `quick__droplet_generator__droplet_generator_fromLFR` | quick | success | 0.92 | success | 3.73 | 0.246 |
| 430 | `quick__flow_and_control_demo__flow_and_control_demo_fromLFR` | quick | success | 1.13 | success | 2.27 | 0.496 |
| 431 | `quick__flow_and_control_demo__flow_and_control_demo_fromMINT` | quick | success | 1.12 | success | 2.26 | 0.496 |
| 432 | `quick__flow_only_demo__flow_only_demo_fromLFR` | quick | success | 0.88 | success | 1.07 | 0.823 |
| 433 | `quick__flow_only_demo__flow_only_demo_fromMINT` | quick | success | 0.88 | success | 1.10 | 0.798 |
| 434 | `quick__import_droplet_reaction__import_droplet_reaction_fromLFR` | quick | success | 2.04 | timeout | 1800.02 | 0.001 |
| 435 | `quick__import_mixer_and_incubator__import_mixer_and_incubator_fromLFR` | quick | success | 0.93 | success | 1.35 | 0.693 |
| 436 | `quick__import_parallel_premix__import_parallel_premix_fromLFR` | quick | success | 1.10 | success | 6.30 | 0.174 |
| 437 | `quick__incubator__incubator_fromLFR` | quick | success | 0.87 | success | 1.04 | 0.838 |
| 438 | `quick__long_mixer__long_mixer_fromLFR` | quick | success | 0.88 | success | 1.19 | 0.739 |
| 439 | `quick__long_mixer__long_mixer_fromMINT` | quick | success | 0.93 | success | 1.14 | 0.813 |
| 440 | `quick__map_droplet__map_droplet_fromLFR` | quick | success | 0.93 | success | 2.22 | 0.419 |
| 441 | `quick__map_mixer__map_mixer_fromLFR` | quick | success | 0.89 | success | 1.33 | 0.671 |
| 442 | `quick__map_mux__map_mux_fromLFR` | quick | success | 1.19 | success | 1.34 | 0.884 |
| 443 | `quick__map_via__map_via_fromLFR` | quick | success | 0.89 | success | 1.02 | 0.873 |
| 444 | `quick__map_ytree__map_ytree_fromLFR` | quick | success | 0.92 | success | 1.73 | 0.536 |
| 445 | `quick__multi_mixer__multi_mixer_fromLFR` | quick | success | 0.97 | success | 2.54 | 0.383 |
| 446 | `quick__multi_mixer__multi_mixer_fromMINT` | quick | success | 0.98 | success | 1.42 | 0.692 |
| 447 | `quick__test_DIY_crossing__test_DIY_crossing_fromLFR` | quick | success | 0.93 | success | 1.14 | 0.815 |
| 448 | `quick__test_DIY_fork__test_DIY_fork_fromLFR` | quick | success | 0.88 | success | 1.10 | 0.800 |
| 449 | `quick__test_device_v1_MUX_1to4__test_device_v1_MUX_1to4_fromLFR` | quick | success | 6.95 | success | 52.08 | 0.133 |
| 450 | `quick__test_device_v1_MUX_4to1__test_device_v1_MUX_4to1_fromLFR` | quick | success | 10.37 | fail | 1798.64 | 0.006 |
| 451 | `quick__test_device_v2_2MUX__test_device_v2_2MUX_fromLFR` | quick | success | 1.58 | fail | 35.77 | 0.044 |
| 452 | `quick__test_device_v3_2MUX_fork__test_device_v3_2MUX_fork_fromLFR` | quick | success | 1.57 | success | 274.25 | 0.006 |
| 453 | `quick__three_in_mixer__three_in_mixer_fromLFR` | quick | success | 0.92 | fail | 1.55 | 0.593 |
| 454 | `quick__two_in_mixer__two_in_mixer_fromLFR` | quick | success | 0.87 | success | 1.14 | 0.762 |
