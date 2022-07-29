# <center>Gaming with YOLOv5 🐝</center>
<div align="center">
        <img src="assets/yolov5.png" width="300" /> &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
        <img src="assets/wandb.png" width="300" /> 
</div>

This project aims at demonstrating the potential for using YOLOv5 for developing gesture-based control mechanisms for games.

# [Google Dinosaur Game](https://offline-dino-game.firebaseapp.com/)

```shell
python game_scripts/play_dinosaur.py \
        --source 0 \
        --conf-thres 0.48 \
        --artifact "wandb/hand-detection-yolov5/run_85dp129g_model:v0"
```

# Racing Game [WIP]