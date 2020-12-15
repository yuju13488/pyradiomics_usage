# pyradiomics_usage
To convert dicom file to nrrd file, and use pyradiomics to extract features.

因為pyradiomics僅使用nrrd檔案，因此從醫療影像dicom檔案，及醫師圈選後產生的RT-Struct.dcm，進行轉檔成nii檔案，及nrrd檔案後再透過pyradiomics取出特徵，並計算兩群特徵值的差異（p-value）。
可使用3Dbounding_box_nrrd.ipynb自行創造出label的nrrd檔案，再使用pyradiomics取得此bounding box內的特徵。

Because pyradiomics only uses nrrd files, the dicom files of medical images and the RT-Struct.dcm generated after the doctor’s circle are converted to nii file and nrrd file, then the features are extracted through pyradiomics and the two groups of feature values are calculated Difference (p-value).
You can use 3Dbounding_box_nrrd.ipynb to create the nrrd file by yourself, and then use pyradiomics to get the features in this bounding box.
