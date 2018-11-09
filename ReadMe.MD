# ========================================
# Utility to Create FORTRAN Block Data Source Code From Analysis Results Data:
# ========================================

## Utility to Create FORTRAN Block Data Source Code From Analysis Results Data.

##
## I. Utility Executable: "./bin/qshep3.exe"



##
## II. Utility Output Files:
### II.a. "./output/output_deck_avg.out"
    =================================
    START: "output_deck_avg.out"
    =================================
       data N /      83 /
       data davg_NQ, davg_NW, davg_NR, davg_RMAX,r_i_index_max,r_i_index_min,r_j_index_max,r_j_index_min,r_k_index_max,r_k_index_min,r_h_max,r_h_min /      30,      40,       3,  0.11123611E+01,  0.45000000E+05,  0.00000000E+00,  0.85000002E+00,  0.10000000E-02,  0.83000000E+02,  0.20000000E+02,  0.14800000E+02,  0.21400001E+01 /
       data davg_XYZMIN(  1) ,davg_XYZDEL(  1) /  0.00000000E+00,  0.33333334E+00 /
    ... CONTENT REMOVED ...
    =================================
    END: "output_deck_avg.out"
    =================================

### II.b. "./output/output_seal_avg.out"
    =================================
    START: "output_seal_avg.out"
    =================================
       data N /      83 /
       data avg_NQ, avg_NW, avg_NR, avg_RMAX,r_i_index_max,r_i_index_min,r_j_index_max,r_j_index_min,r_k_index_max,r_k_index_min,r_h_max,r_h_min /      30,      40,       3,  0.11123611E+01,  0.45000000E+05,  0.00000000E+00,  0.85000002E+00,  0.10000000E-02,  0.83000000E+02,  0.20000000E+02,  0.16600000E+02,  0.23199999E+01 /
       data avg_XYZMIN(  1) ,avg_XYZDEL(  1) /  0.00000000E+00,  0.33333334E+00 /
       data avg_LCELL(  1,  1,  1) /       1 /
       data avg_LCELL(  1,  1,  2) /       3 /
       data avg_LCELL(  1,  1,  3) /       4 /
       data avg_LCELL(  1,  2,  1) /       5 /
       data avg_LCELL(  1,  2,  2) /       7 /
       data avg_LCELL(  1,  2,  3) /       8 /
       data avg_LCELL(  1,  3,  1) /      35 /
       data avg_LCELL(  1,  3,  2) /      37 /
       data avg_LCELL(  1,  3,  3) /       0 /
    ... CONTENT REMOVED ...
    =================================
    END: "output_seal_avg.out"
    =================================

### II.c. "./output/output_seal_max.out"
    =================================
    START: "output_seal_max.out"
    =================================
       data N /      83 /
       data max_NQ, max_NW, max_NR, max_RMAX,r_i_index_max,r_i_index_min,r_j_index_max,r_j_index_min,r_k_index_max,r_k_index_min,r_f_max,r_f_min /      30,      40,       3,  0.11123611E+01,  0.45000000E+05,  0.00000000E+00,  0.85000002E+00,  0.10000000E-02,  0.83000000E+02,  0.20000000E+02,  0.25790001E+02,  0.32900000E+01 /
       data max_XYZMIN(  1) ,max_XYZDEL(  1) /  0.00000000E+00,  0.33333334E+00 /
       data max_LCELL(  1,  1,  1) /       1 /
       data max_LCELL(  1,  1,  2) /       3 /
       data max_LCELL(  1,  1,  3) /       4 /
       data max_LCELL(  1,  2,  1) /       5 /
       data max_LCELL(  1,  2,  2) /       7 /
       data max_LCELL(  1,  2,  3) /       8 /
       data max_LCELL(  1,  3,  1) /      35 /
       data max_LCELL(  1,  3,  2) /      37 /
       data max_LCELL(  1,  3,  3) /       0 /
       data max_XYZMIN(  2) ,max_XYZDEL(  2) / -0.11778563E-02,  0.33372596E+00 /
    ... CONTENT REMOVED ...
    =================================
    END: "output_seal_max.out"
    =================================

### II.d. "./output/output_seal_min.out"

    =================================
    START: "output_seal_min.out"
    =================================
       data N /      83 /
       data min_NQ, min_NW, min_NR, min_RMAX,r_i_index_max,r_i_index_min,r_j_index_max,r_j_index_min,r_k_index_max,r_k_index_min,r_g_max,r_g_min /      30,      40,       3,  0.11123611E+01,  0.45000000E+05,  0.00000000E+00,  0.85000002E+00,  0.10000000E-02,  0.83000000E+02,  0.20000000E+02,  0.13540000E+02,  0.18900000E+01 /
       data min_XYZMIN(  1) ,min_XYZDEL(  1) /  0.00000000E+00,  0.33333334E+00 /
       data min_LCELL(  1,  1,  1) /       1 /
       data min_LCELL(  1,  1,  2) /       3 /
       data min_LCELL(  1,  1,  3) /       4 /
       data min_LCELL(  1,  2,  1) /       5 /
       data min_LCELL(  1,  2,  2) /       7 /
       data min_LCELL(  1,  2,  3) /       8 /
       data min_LCELL(  1,  3,  1) /      35 /
       data min_LCELL(  1,  3,  2) /      37 /
       data min_LCELL(  1,  3,  3) /       0 /
    ... CONTENT REMOVED ...
    =================================
    END: "output_seal_min.out"
    =================================

