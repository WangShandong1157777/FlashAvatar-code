
## Setup


```
git clone https://github.com/WangShandong1157777/FlashAvatar-code.git --recursive 
```

## Error Solving:
- [Errno 2] No such file or directory: 'flame/generic_model.pkl'
download FLAME2020 from https://flame.is.tue.mpg.de/index.html
- [Errno 2] No such file or directory: 'flame/FLAME_masks/FLAME_masks.pkl'
download FLAME2020 from https://flame.is.tue.mpg.de/index.html
- x

```
x
```

```
## Running
- **Evaluating pre-trained model**
```shell
python test.py --idname <id_name> --checkpoint dataset/<id_name>/log/ckpt/chkpnt.pth
```
-  **Training on your own data** 
```shell
python train.py --idname <id_name>
```

