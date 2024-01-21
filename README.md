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
### Scenario 1: You have Python installed on your local machine. (Just 2 clicks to download all models and make new `roop.zip`)
1. Download [roop.zip](https://github.com/neuralfalcon/roop_colab/raw/main/roop.zip) (3.2mb)
2. Download [Make_roop.zip.ipynb](https://github.com/neuralfalcon/roop_colab/blob/main/Make_roop.zip.ipynb)
3. Move roop.zip(3.2MB) and Make_roop.zip.ipynb inside any folder like this<br>
   ![image](https://github.com/neuralfalcon/roop_colab/assets/139750329/220da98b-b0ac-4aa6-a464-aa3a9b806488)
4. Run `Make_roop.zip.ipynb`. It will take time depending on your internet speed.
5. You will get new roop.zip file (may be 1.7GB)
6. Open google drive and make a folder called  `'RoopFaceSwap_Backup'` and upload `roop.zip`(may be 1.7GB) inside this folder
7. Download [roop_no_ban.ipynb](https://github.com/neuralfalcon/roop_colab/blob/main/roop_no_ban.ipynb) and upload it on google colab
9. Then run this step by step first it will access  `RoopFaceSwap_Backup/roop.zip` from google drive make sure you are using same gmail account
10. While installing the requirements.txt file on Google Colab, it automatically restarts. Don't panic. After the restart, run the next cell.

### Scenario 2: You don't have Python installed on your local machine.  (Manually download each model, configure path and make new `roop.zip`)
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
7. Open google drive make a folder `'RoopFaceSwap_Backup'` then upload the roop.zip there
8. Download [roop_no_ban.ipynb](https://github.com/neuralfalcon/roop_colab/blob/main/roop_no_ban.ipynb) and upload it on google colab
9. Then run this step by step first it will access  `RoopFaceSwap_Backup/roop.zip` from google drive make sure you are using same gmail account
10. While installing the requirements.txt file on Google Colab, it automatically restarts. Don't panic. After the restart, run the next cell.


## Note We have 2 Face Swapper Model
`inswapper_128.onnx` 529MB (By default we are using this, slow but good result)
`inswapper_128.fp16.onnx` 264MB (Fast but sometime not perform good) from https://github.com/Hillobar/Rope

if you want to use `inswapper_128.fp16.onnx`
open `roop\roop\processors\frame\face_swapper.py`
Comment out line 24 and uncomment line 25.
# Credit 
- [s0md3v](https://github.com/s0md3v/roop) for Original roop code.
- [deepinsight](https://github.com/deepinsight) for their [insightface](https://github.com/deepinsight/insightface) project which provided a well-made library and models.
- [GFPGAN](https://github.com/TencentARC/GFPGAN)  for their code and models.

