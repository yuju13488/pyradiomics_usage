# pyradiomics_usage
To convert dicom file to nrrd file, and use pyradiomics to extract features.

因為pyradiomics僅使用nrrd檔案，因此從醫療影像dicom檔案，及醫師圈選後產生的RT-Struct.dcm，進行轉檔成nii檔案，及nrrd檔案後再透過pyradiomics取出特徵，並計算兩群特徵值的差異（p-value）。

Because pyradiomics only uses nrrd files, the dicom files of medical images and the RT-Struct.dcm generated after the doctor’s circle are converted to nii file and nrrd file, then the features are extracted through pyradiomics and the two groups of feature values are calculated Difference (p-value).
