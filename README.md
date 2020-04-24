# ELEC0098_IMS_Research-and-Development-on-HTTP-Video-Streaming
IMS Assignment: Research and Development on HTTP Video Streaming.  Study of bitrate-quality-complexity of several video encoders supported by FFmpeg (or libav or similar), such as H.264/AVC, HEVC, VP9

Download Anaconda Navigator from https://www.anaconda.com/distribution/
You can install it for Windows, Mac or Linux machines

For this project, a Windows 10 64-bitd machine have been used
Install Anaconda

Once installed, launcch Anaconda Navigator
Install and then launch Jupyter Notebook

once the web tab is open, go the drectory you wish to run the code and hit New-->Terminal

A new tab with a linux terminal should have appear:

Please type the below commands in order to install the required packages and updates:

***Note that Python 3.7 will be used***

>>conda update conda

>>conda create --name IMS python=3.7

>>activate IMS

>>conda install -c conda-forge matplotlib
>>conda install -c anaconda numpy
>>conda install -c anaconda pandas

Go back to http://localhost:8888/tree and launch the:

"video_quality_plots.ipynb" file 

The file and the json files required for this code to run, can be found at:


https://github.com/uceert0/ELEC0098_IMS_Research-and-Development-on-HTTP-Video-Streaming

If you store the .json files elsewhere rather the run directory, then you will need to edit the path name


Type the commands below to see which packages and their versions will be required:
S C:\Users\user> conda list numpy
# packages in environment at C:\Users\user\AppData\Local\Continuum\anaconda3:
#
# Name                    Version                   Build  Channel
numpy                     1.16.5           py37h19fb1c0_0
numpy-base                1.16.5           py37hc3f5095_0
numpydoc                  0.9.1                      py_0
PS C:\Users\user> conda list python
# packages in environment at C:\Users\user\AppData\Local\Continuum\anaconda3:
#
# Name                    Version                   Build  Channel
ipython                   7.8.0            py37h39e3cac_0
ipython_genutils          0.2.0                    py37_0
msgpack-python            0.6.1            py37h74a9793_1
python                    3.7.4                h5263a28_0
python-dateutil           2.8.0                    py37_0
python-libarchive-c       2.8                     py37_13
python_abi                3.7                     1_cp37m    conda-forge
PS C:\Users\user> conda list pandas
# packages in environment at C:\Users\user\AppData\Local\Continuum\anaconda3:
#
# Name                    Version                   Build  Channel
pandas                    0.25.1           py37ha925a31_0
PS C:\Users\user> conda list matplotlib
# packages in environment at C:\Users\user\AppData\Local\Continuum\anaconda3:
#
# Name                    Version                   Build  Channel
matplotlib                3.1.1            py37hc8f65d3_0

also run conda list to see the full set of packages listed in your new environment

>>conda list
