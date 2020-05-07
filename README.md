# 15464 Final Project Submission

<img src='documentation/pose_examples.png' width='100%'>

## 2D Drawing Interface

```
cd interface/
python3 app.py
```

Loads up the kivy drawing interface.

<img src='documentation/sketch_interface.png' width='50%'>

To export rotations to a JSON format, run:
```
cd interface/
python3 joint_parsing.py
```


## 3D Posing Interface

```
cd model/
python3 -m http.server
```

Visit localhost to view the web-browser posing interface.

<img src='documentation/pose_interface.png' width='50%'>
