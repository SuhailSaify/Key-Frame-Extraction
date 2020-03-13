# Key-Frame-Extraction

Example :
```
from Key_Frames_0.2 import get_key_frames_1
key_frames_index=get_key_frames_1(frame_images,show_plot=True,N=21,constant=True,N_frames=20)

```  
returns index of key frames  
  
  
    
Function Parameters:    
img_seq: Frames extracted from a video  
show_plot: plot 'difference measure vs frame number' graph  
N: Interval   
M: refer to paper  
p_factor: refer to paper  
block_size: face is devided into (block_size X block_size)  
lbp_r: lbp radius  
constant: Return constant key-frames or all  
N_frames: Number of key-frames to return if constant==True
  
  
  

![difference measure vs frame number' graph](https://github.com/SuhailSaify/Key-Frame-Extraction/blob/master/Key_Frame_N_21.png)
