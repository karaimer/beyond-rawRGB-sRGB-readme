This document explains how to reproduce the results presented in Karaimer and Brown [1]. 

Downloading the whole folder from [Dropbox](https://www.dropbox.com/sh/louamwxabofc0wi/AABN5f5J3Uohsaud7IQxWoz6a?dl=0) at once might be too large. I suggest downloading in parts and combining as in the folder structure in the CIC2019 folder in Dropbox. 

Please run main.m to reproduce the results in Table 1. The main.m is placed in every "code/visualization" folder for each lighting condition. 

"CIC2019/4340/CC/code/visualization/main.m" reproduces the (1) Color Rendition Chart for 4340K. 

"CIC2019/4340/C1/code/visualization/main.m" reproduces the (2) Paint Samples #1 for 4340K. 

"CIC2019/4340/C2/code/visualization/main.m" reproduces the (3) Paint Samples #2 for 4340K. 

"CIC2019/3200/CC/code/visualization/main.m" reproduces the (1) Color Rendition Chart for 3200K. 

"CIC2019/3200/C1/code/visualization/main.m" reproduces the (2) Paint Samples #1 for 3200K. 

"CIC2019/3200/C2/code/visualization/main.m" reproduces the (3) Paint Samples #2 for 3200K. 

"CIC2019/5500/CC/code/visualization/main.m" reproduces the (1) Color Rendition Chart for 5500K. 

"CIC2019/5500/C1/code/visualization/main.m" reproduces the (2) Paint Samples #1 for 5500K. 

"CIC2019/5500/C2/code/visualization/main.m" reproduces the (3) Paint Samples #2 for 5500K. 

In order to reproduce "Combined" columns in each table, please run main_combined.m. 

"\CIC2019\4340\CC\code\visualization\main_combined.m" reproduces the (1) Color Rendition Chart for combined ligting.

"\CIC2019\4340\C1\code\visualization\main_combined.m" reproduces the (2) Paint Samples #1 for combined ligting.

"\CIC2019\4340\C2\code\visualization\main_combined.m" reproduces the (3) Paint Samples #2 for combined ligting. 

In these scripts outputs, the Table 1's "raw-RGB", "white-balanced raw-RGB", "colorimetric image state (linear)", "colorimetric image state (non-linear)", and "sRGB" are indicated as "raw," "perfect wb-raw", "only linear pwb", "pwb stg5", and "pwb st11" respectively. 

[1] Karaimer H.C., Brown M.S. (2019) "Beyond raw-RGB and sRGB: Advocating Access to a Colorimetric Image State", Color and Imaging Conference (CIC`19), Oct 2019.
