# AES_System_with_Arbiter_PUF
This is the graduated project for our department. 

## Physical Unclonable Function (PUF)’s application and extension in Advanced Encryption Standard (AES) System
This project is the extension of the Arbiter PUF, using Verilog to simulate and implement on FPGA board. 
We take the advantages of PUF for its physical feature with AES to create the unique Key, which enhanced the security and broaden the application of PUF. 

### Implementation
Xilinx ZC-702

#### DEMO Video
* AES System implementation <br>
https://youtu.be/OkCJ7bmQvAY
* AES System's key go through Arbiter PUF first, then regards the output from PUF as the key for AES System <br>
https://youtu.be/KdBpwB4q1zk
* Same with the above, but changes the data which is needed to be encrypted <br>
https://youtu.be/oGrUIWSobdk

### Reference
1. G. E. Suh and S. Devadas, "Physical Unclonable Functions for Device Authentication and Secret Key Generation," 2007 44th ACM/IEEE Design Automation Conference, 2007, pp. 9-14.
2. C. Herder, M. Yu, F. Koushanfar and S. Devadas, "Physical Unclonable Functions and Applications: A Tutorial," in Proceedings of the IEEE, vol. 102, no. 8, pp. 1126-1141, Aug. 2014, doi: 10.1109/JPROC.2014.2320516.
3. Maiti, A., Schaumont, P., "Improved Ring Oscillator PUF: An FPGA-friendly Secure Primitive", J Cryptol 24, 375–397, 2011, doi: 10.1007/s00145-010-9088-4
4. S. S. Kumar, J. Guajardo, R. Maes, G. Schrijen and P. Tuyls, "Extended abstract: The butterfly PUF protecting IP on every FPGA," 2008 IEEE International Workshop on Hardware-Oriented Security and Trust, 2008, pp. 67-70, doi: 10.1109/HST.2008.4559053.
5. D. P. Sahoo, D. Mukhopadhyay and R. S. Chakraborty, "Design of low area-overhead ring oscillator PUF with large challenge space," 2013 International Conference on Reconfigurable Computing and FPGAs (ReConFig), 2013, pp. 1-6, doi: 10.1109/ReConFig.2013.6732277.
6. National Institute of Standards and Technology, " Announcing the ADVANCED ENCRYPTION STANDARD (AES)," Federal Information Processing Standards Publication 197, Nov 2001, doi: 10.6028/NIST.FIPS.197
7. 戴宏運。「8位元進階加密器FPGA設計」。碩士論文，國立臺灣師範大學工業教育學系，2007。https://hdl.handle.net/11296/368684。

## Keywords
Physical Unclonable Function, Arbiter PUF, Advanced Encryption Standard System
