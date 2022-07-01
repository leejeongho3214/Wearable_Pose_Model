# Wearable_Pose_Model ✨✨


This is our research code of [Our_Model]("docs/2022_KSCI.pdf"). 

Our Model is a transformer-based method for hand pose from an input image. 
This image is obtained from wrist-attached RGB camera.
In this work, We study how to use our synthetic images.

 <img src="docs/model.png" width="650"> 

## Installation(Download)
Build as below architecture 
```
{$ROOT}
|-- build
|-- src
|-- datasets
|-- models
|-- docs
```

## Installation(Conda)
```bash
git clone https://github.com/leejeongho3214/Wearable_Pose_Model.git
cd Wearable_Pose_Model
conda env create -f requirements.yaml
```

## Model Download
Please download our files that are important to run our code. [download](https://dkuniv-my.sharepoint.com/:f:/g/personal/72210297_dankook_ac_kr/Em6dacaP1AlNmTAmaBbX2osBxkTx8km8k7BeHT2d-TWF5A?e=poqt1A)

## Train
```
run 'src/tools/train.py'
```
## Error
If it happens error message about path as "src/...", you can insert below code.
```python
import sys
sys.path.append("/usr/your/path/Wearable_Pose_Model")
```

## Result
 <img src="docs/result1.png" width="650"> 
 <img src="docs/result2.png" width="650"> 
 <img src="docs/result3.png" width="650"> 
 