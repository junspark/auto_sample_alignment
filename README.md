# auto_sample_alignment
Automatically computes the center of beam using computer vision. 

*******************************
installation information for
222d4c76dfada014439792d672b6564617490954
*******************************
conda create -n auto_alignment python=3
conda activate auto_alignment
conda install numpy
conda install click
conda install -c conda-forge scikit-image
conda install -c conda-forge trackpy 

'''
*******************************
# packages in environment at /home/beams/PARKJS/anaconda3/envs/auto_alignment:
#
# Name                    Version                   Build  Channel
blas                      1.0                         mkl  
bzip2                     1.0.6             h14c3975_1002    conda-forge
ca-certificates           2019.6.16            hecc5488_0    conda-forge
cairo                     1.16.0            h18b612c_1001    conda-forge
certifi                   2019.6.16                py37_0    conda-forge
click                     7.0                      py37_0  
cloudpickle               1.2.1                      py_0    conda-forge
cycler                    0.10.0                     py_1    conda-forge
cytoolz                   0.9.0.1         py37h14c3975_1001    conda-forge
dask-core                 2.0.0                      py_0    conda-forge
dbus                      1.13.6               he372182_0    conda-forge
decorator                 4.4.0                      py_0    conda-forge
expat                     2.2.5             he1b5a44_1003    conda-forge
ffmpeg                    4.1.3                h167e202_0    conda-forge
fontconfig                2.13.1            he4413a7_1000    conda-forge
freetype                  2.10.0               he983fc9_0    conda-forge
gettext                   0.19.8.1          hc5be6a0_1002    conda-forge
giflib                    5.1.9                h516909a_0    conda-forge
glib                      2.58.3            h6f030ca_1001    conda-forge
gmp                       6.1.2             hf484d3e_1000    conda-forge
gnutls                    3.6.5             hd3a4fd2_1002    conda-forge
graphite2                 1.3.13            hf484d3e_1000    conda-forge
gst-plugins-base          1.14.5               h0935bb2_0    conda-forge
gstreamer                 1.14.5               h36ae1b5_0    conda-forge
harfbuzz                  2.4.0                h37c48d4_1    conda-forge
hdf5                      1.10.5          nompi_h3c11f04_1100    conda-forge
icu                       58.2              hf484d3e_1000    conda-forge
imageio                   2.5.0                    py37_0    conda-forge
intel-openmp              2019.4                      243  
jasper                    1.900.1           h07fcdf6_1006    conda-forge
jpeg                      9c                h14c3975_1001    conda-forge
kiwisolver                1.1.0            py37hc9558a2_0    conda-forge
lame                      3.100             h14c3975_1001    conda-forge
libblas                   3.8.0                    10_mkl    conda-forge
libcblas                  3.8.0                    10_mkl    conda-forge
libedit                   3.1.20181209         hc058e9b_0  
libffi                    3.2.1                hd88cf55_4  
libgcc-ng                 9.1.0                hdf63c60_0  
libgfortran-ng            7.3.0                hdf63c60_0  
libiconv                  1.15              h516909a_1005    conda-forge
liblapack                 3.8.0                    10_mkl    conda-forge
liblapacke                3.8.0                    10_mkl    conda-forge
libpng                    1.6.37               hed695b0_0    conda-forge
libstdcxx-ng              9.1.0                hdf63c60_0  
libtiff                   4.0.10            h57b8799_1003    conda-forge
libuuid                   2.32.1            h14c3975_1000    conda-forge
libwebp                   1.0.2                h576950b_1    conda-forge
libxcb                    1.13              h14c3975_1002    conda-forge
libxml2                   2.9.9                h13577e0_0    conda-forge
lz4-c                     1.8.3             he1b5a44_1001    conda-forge
matplotlib                3.1.0            py37h5429711_0  
mkl                       2019.4                      243  
mkl_fft                   1.0.12           py37ha843d7b_0  
mkl_random                1.0.2            py37hd81dba3_0  
ncurses                   6.1                  he6710b0_1  
nettle                    3.4.1             h1bed415_1002    conda-forge
networkx                  2.3                        py_0    conda-forge
numpy                     1.16.4           py37h7e9f1db_0  
numpy-base                1.16.4           py37hde5b4d6_0  
olefile                   0.46                       py_0    conda-forge
opencv                    4.1.0            py37h3aa1047_5    conda-forge
openh264                  1.8.0             hdbcaa40_1000    conda-forge
openssl                   1.1.1b               h14c3975_1    conda-forge
pandas                    0.24.2           py37hb3f55d8_0    conda-forge
pcre                      8.41              hf484d3e_1003    conda-forge
pillow                    5.3.0           py37h00a061d_1000    conda-forge
pip                       19.1.1                   py37_0  
pixman                    0.38.0            h516909a_1003    conda-forge
pthread-stubs             0.4               h14c3975_1001    conda-forge
pyparsing                 2.4.0                      py_0    conda-forge
pyqt                      5.9.2            py37hcca6a23_0    conda-forge
python                    3.7.3                h0371630_0  
python-dateutil           2.8.0                      py_0    conda-forge
pytz                      2019.1                     py_0    conda-forge
pywavelets                1.0.3            py37hd352d35_1    conda-forge
pyyaml                    5.1.1            py37h516909a_0    conda-forge
qt                        5.9.7                h52cfd70_2    conda-forge
readline                  7.0                  h7b6447c_5  
scikit-image              0.14.2           py37hf484d3e_0    conda-forge
scipy                     1.2.1            py37h7c811a0_0  
setuptools                41.0.1                   py37_0  
sip                       4.19.8          py37hf484d3e_1000    conda-forge
six                       1.12.0                py37_1000    conda-forge
sqlite                    3.28.0               h7b6447c_0  
tk                        8.6.8                hbc83047_0  
toolz                     0.9.0                      py_1    conda-forge
tornado                   6.0.3            py37h516909a_0    conda-forge
trackpy                   0.4.1                      py_1    conda-forge
wheel                     0.33.4                   py37_0  
x264                      1!152.20180806       h14c3975_0    conda-forge
xorg-kbproto              1.0.7             h14c3975_1002    conda-forge
xorg-libice               1.0.9             h516909a_1004    conda-forge
xorg-libsm                1.2.3             h84519dc_1000    conda-forge
xorg-libx11               1.6.7             h14c3975_1000    conda-forge
xorg-libxau               1.0.9                h14c3975_0    conda-forge
xorg-libxdmcp             1.1.3                h516909a_0    conda-forge
xorg-libxext              1.3.4                h516909a_0    conda-forge
xorg-libxrender           0.9.10            h516909a_1002    conda-forge
xorg-renderproto          0.11.1            h14c3975_1002    conda-forge
xorg-xextproto            7.3.0             h14c3975_1002    conda-forge
xorg-xproto               7.0.31            h14c3975_1007    conda-forge
xz                        5.2.4                h14c3975_4  
yaml                      0.1.7             h14c3975_1001    conda-forge
zlib                      1.2.11               h7b6447c_3  
zstd                      1.4.0                h3b9ef0a_0    conda-forge

*******************************
'''
