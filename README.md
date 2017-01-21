#SGM-disparity


This is an implement of the algorithm(SGM) about the paper (Stereo Processing by Semiglobal Matching and Mutual Information by Heikoin 2008 IEEE). However, in order to getting a better performance, I also did some modification about matching cost and spacial design about data-structure for a better use of SIMD(Single Instruction Multiple Data) and multi-thread technique.


 
By the way, there is some testing datas and associate results in the directory of data. One can use it for some test.

And some running results:   
![alt tag](https://raw.githubusercontent.com/xxsong5/SGM-disparity/master/data/imLLL.png)
![alt tag](https://raw.githubusercontent.com/xxsong5/SGM-disparity/master/data/_depth_imLLL.png)
![alt tag](https://raw.githubusercontent.com/xxsong5/SGM-disparity/master/data/imLLLL.png)
![alt tag](https://raw.githubusercontent.com/xxsong5/SGM-disparity/master/data/_depth_imLLLL.png)

how to run this code ?(compile)  

cd SGM-disparity   
mkdir build   
cd build    
cmake ..    
make   





