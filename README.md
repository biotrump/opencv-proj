opencv-proj
===========

projects based on openCV 3.x
with visual studio 2010
>setx /m $(OPENCV_ROOT) /path_to_opencv_src
linker's static lib
libwebpd.lib;kernel32.lib;user32.lib;gdi32.lib;winspool.lib;shell32.lib;ole32.lib;oleaut32.lib;uuid.lib;comdlg32.lib;advapi32.lib;opencv_calib3d300d.lib;opencv_contrib300d.lib;opencv_core300d.lib;opencv_cuda300d.lib;opencv_cudaarithm300d.lib;opencv_cudabgsegm300d.lib;opencv_cudacodec300d.lib;opencv_cudafeatures2d300d.lib;opencv_cudafilters300d.lib;opencv_cudaimgproc300d.lib;opencv_cudaoptflow300d.lib;opencv_cudastereo300d.lib;opencv_cudawarping300d.lib;opencv_features2d300d.lib;opencv_flann300d.lib;opencv_haartraining_engined.lib;opencv_highgui300d.lib;opencv_imgproc300d.lib;opencv_legacy300d.lib;opencv_ml300d.lib;opencv_nonfree300d.lib;opencv_objdetect300d.lib;opencv_optim300d.lib;opencv_photo300d.lib;opencv_shape300d.lib;opencv_softcascade300d.lib;opencv_stitching300d.lib;opencv_superres300d.lib;opencv_ts300d.lib;opencv_video300d.lib;opencv_videostab300d.lib;libjpegd.lib;libpngd.lib;libtiffd.lib;libjasperd.lib;IlmImfd.lib;zlibd.lib;comctl32.lib;setupapi.lib;ws2_32.lib;vfw32.lib

linker's path
$(OPENCV_ROOT)\build-3.0.x\lib\Debug;$(OPENCV_ROOT)\build-3.0.x\3rdparty\lib\Debug;%(AdditionalLibraryDirectories)

header include path
$(OPENCV_ROOT)\include;$(OPENCV_ROOT)\modules\core\include;$(OPENCV_ROOT)\modules\highgui\include;%(AdditionalIncludeDirectories)


