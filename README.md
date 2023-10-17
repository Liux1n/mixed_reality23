Check [https://github.com/hkchengrex/MiVOS/tree/MiVOS-STCN](URL)
and https://github.com/ruiliu-ai/DSTT

```
cd DSTT
pip install -r requirements.txt
```

specify your video directory or change the default directory in interactive_gui.py at:
```
parser.add_argument('--video', help='Video file readable by OpenCV. Either this or --images needs to be specified.', default='example/example.mp4')
```
specify change the default directory of pre-trained model:
```
parser.add_argument("-c", "--ckpt",   type=str, default= "G:\Mixed_Reality\project_2D_videoInpainting\DSTT\checkpoints\dstt.pth")
```

get all the required models.

```
python download_model.py
```


Download dstt pre-trained model into checkpoints folder in dstt folder:
```
cd dstt
mkdir checkpoints
```
https://drive.google.com/file/d/1Fq3seV2X6dthbjdw4RTNyVd4HH2WlL7g/view

