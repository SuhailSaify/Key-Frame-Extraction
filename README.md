# Key-Frame-Extraction
This is python implentaion of the key frame extraction technique described here:

Example :
```
from Key_Frames_0.2 import get_key_frames
key_frames_index=get_key_frames_1(frame_images,show_plot=True,N=21,constant=True,N_frames=20)

```

img_seq: Frames extracted from a video
show_plot: plot 'difference measure vs frame number' graph
N: Interval 
M: refer to paper
p_factor: refer to paper
block_size: face are devided into (block_size,block_size)
lbp_r: lbp radius
constant: Return constant key-frames or all
N_frames: Number of key-frames to return if constant==True
