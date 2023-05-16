# SRMT
This work has been submitted to NeurIPS2023.

Dependencies
--
* python >= 3.6
* pytorch >= 1.7.0
* torchvision >= 0.8.0

Training
--
1.Download Training Set ([DIV2K](https://data.vision.ee.ethz.ch/cvl/DIV2K/))    
2.Modify the ``dataroot_H`` and ``dataroot_L`` in ``options/train_sr_lightweight.json``  
3.Run ``main_train.py``  

Testing
--
1.Download Testing Set ([Set5](https://uofi.box.com/shared/static/kfahv87nfe8ax910l85dksyl2q212voc.zip), [Set14](https://uofi.box.com/shared/static/igsnfieh4lz68l926l8xbklwsnnk8we9.zip), [BSD100](https://uofi.box.com/shared/static/qgctsplb8txrksm9to9x01zfa4m61ngq.zip) and [Urban100](https://uofi.box.com/shared/static/65upg43jjd0a4cwsiqgl6o6ixube6klm.zip))  
2.Modify the ``folder_lq`` and ``folder_gt`` in ``main_test.py``  
3.Run ``main_test.py``  

Acknowledgement
--
We borrow some codes from [KAIR](https://github.com/cszn/KAIR), [SwinIR](https://github.com/JingyunLiang/SwinIR) and [TTSR](https://github.com/researchmm/TTSR). We thank the authors for their great work.
