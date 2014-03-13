Netlib LP Test Problems (MAT Format)
====================================

### Problem format:
```
  min   c'x 
  s.t.  Ax = b,
        lbounds<= x <= ubounds
```
### Credits:
1. The mat files were downloaded from the [**Weichung Wang's webpage**](http://www.math.ntu.edu.tw/~wwang/cola_lab/test_problems/netlib_lp/) at National Taiwan University.
2. The mat files were generated from MPS files by using the code **mps2mat.f** that is a part of the package [LIPSOL](http://www.caam.rice.edu/~zhang/lipsol/index.html) by [Yin Zhang](http://www.caam.rice.edu/~zhang/). 


### Notes
1. In the mat files, 1e+32 should be considered as +inf. This large constant presents because it is used as inf in mps2mat.f.
2. These problems have not been preprocessed or scaled. A may not be full row rank.
3. For more infomation such as the structure of the problems, the optimal values, etc, see **00readme.txt** in foler **MPS_Files**.  

- - -
Yiming Yan @ The University of Edinburgh

March 12, 2014
