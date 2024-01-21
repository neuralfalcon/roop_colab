# I don't have an RTX, so Google Colab is the only option.
# Disclaimer
This software is meant to be a productive contribution to the rapidly growing AI-generated media industry. It will help artists with tasks such as animating a custom character or using the character as a model for clothing etc.

The user of this software are aware of its possible unethical applicaitons and are committed to take preventative measures against them.

Users of this software are expected to use this software responsibly while abiding the local law. If face of a real person is being used, users are suggested to get consent from the concerned person and clearly mention that it is a deepfake when posting content online. Developers of this software will not be responsible for actions of end-users.



# How to run roop on Google Colab 

![roop](https://github.com/neuralfalcon/roop_colab/assets/139750329/253d85a7-d06e-4758-b3e1-507d18d017b6)


## Step 1:
Download [roop.zip](https://github.com/neuralfalcon/roop_colab/raw/main/roop.zip) (This 3.2mb file used for step 2)<br>
## Step 2:
Roop Permanent BackUp on Google Drive (Lifetime Backup): <br>
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/neuralfalcon/roop_colab/blob/main/Make_Roop_Backup.ipynb)
## Step 3:
Access new roop.zip file(1.7GB) from Google drive and Run roop (Remove opennsfw2 for little speed up) , Use same gmail account or share the 'RoopFaceSwap_Backup' with your current gmail account<br>
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/neuralfalcon/roop_colab/blob/main/roop_no_ban.ipynb)


## If you see this pop up just download the .ipynb files and manually upload it on google colab
![save](https://github.com/neuralfalcon/roop_colab/assets/139750329/33fb5bdd-f8ae-4d71-ab02-f994168026ec)

## Still you have this issue
![image](https://github.com/neuralfalcon/roop_colab/assets/139750329/0faace44-a0b4-4a0a-ac50-3fcb1ed081b2) <br>
## Follow these step to make a new roop.zip file (may be 1.7 gb) from local computer then upload it in google drive inside 'RoopFaceSwap_Backup'folder
1. Download [roop.zip](https://github.com/neuralfalcon/roop_colab/raw/main/roop.zip) (3.2mb)
2. Extract roop.zip
3. Download all Models<br>
[inswapper_128](https://huggingface.co/countfloyd/deepfake/resolve/main/inswapper_128.onnx) <br>
[inswapper_128_fp16](https://github.com/Hillobar/Rope/releases/download/Sapphire/inswapper_128.fp16.onnx) (Optional) <br>
[buffalo_l](https://github.com/deepinsight/insightface/releases/download/v0.7/buffalo_l.zip)   (you need to extract this one)<br>
[GFPGANv1_4 ](https://github.com/TencentARC/GFPGAN/releases/download/v1.3.4/GFPGANv1.4.pth)  <br>
[detection_Resnet50_Final](https://github.com/xinntao/facexlib/releases/download/v0.1.0/detection_Resnet50_Final.pth)  <br>
[parsing_parsenet](https://github.com/xinntao/facexlib/releases/download/v0.2.2/parsing_parsenet.pth) <br>
[onnx_gpu_1.17.0](https://github.com/karaokenerds/python-audio-separator/releases/download/v0.12.1/onnxruntime_gpu-1.17.0-cp310-cp310-linux_x86_64.whl) <br>
4. Follow the folder structure to move the models to specific path
[Folder Structure ](https://github.com/neuralfalcon/roop_colab/blob/main/folder_tree.txt) <br>
If you know Python, take a look at this code for a better understanding.
[Make_Roop_Backup.ipynb](https://github.com/neuralfalcon/roop_colab/blob/main/Make_Roop_Backup.ipynb)
6. Make a new roop.zip file (may be 1.7gb)
7. Open google drive make a folder 'RoopFaceSwap_Backup' then upload the roop.zip there
8. Download roop_no_ban.ipynb [roop colab](https://github.com/neuralfalcon/roop_colab/blob/main/roop_no_ban.ipynb) and upload it on google colab
9. Then run this step by step first it will access  RoopFaceSwap_Backup/roop.zip from google drive make sure you are using same gmail account



