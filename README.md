# ml_lab_ecsc_306
Basic Example For ML Tutorial

Prerequsites:

Linux Platform : Ubuntu 16.04

Programming Language :
Python

Software:
Python v3.6
TensorFlow
Anaconda3 for Jupyter Notebook



Installing software:


1. Download anaconda from https://www.continuum.io/downloads

	bash Anaconda3-4.4.0-Linux-x86_64.sh  // Downloaded fileName

2. Add this in .bashrc file
	export PATH=~/anaconda3/bin:$PATH

3. conda create -n tensorflow

4. Find latestWheel for tensorFlow from 

	https://www.tensorflow.org/install/install_linux#InstallingAnaconda

	Get binaryURL for CPU only - Python 3.6 , sample url is provided

	binaryurl=https://storage.googleapis.com/tensorflow/linux/cpu/tensorflow-1.2.1-cp36-cp36m-linux_x86_64.whl

pip install --ignore-installed --upgrade $binaryUrl


