# Unofficial TensorFlow Build
 
This repository consists of unofficial TensorFlow WHL builds with custom build configurations. 


Refer to the table below to get more information about WHL files that are available for download. 


|No  |OS           |TensorFlow Ver.|Build Type |Python Ver.|Optimization Flags                          |CPU Features                  |WHL File   |
|----|-------------|---------------|-----------|--------------------------------------------------------|------------------------------|-----------|
|1   |Ubuntu 16.04 |1.10           |CPU        |2.7        |-march=native -mcx16                        |CX16                          |[Download](https://github.com/amikelive/tf-build/raw/master/ubuntu/1.10/tensorflow-1.10.0-noavx-cp27-cp27mu-linux_x86_64.whl)|
|2   |Ubuntu 16.04 |1.10           |CPU        |2.7        |-march=native -mssse3 -mfma -mcx16 -msse4.1 -msse4.2 -mpopcnt -mavx -mavx2|CX16, POPCNT, SSSE3, SSE-4.1, SSE-4.2, FMA,AVX, AVX2|[Download](https://github.com/amikelive/tf-build/raw/master/ubuntu/1.10/tensorflow-1.10.0-cp27-cp27mu-linux_x86_64.whl)|
