# Region Layer
## Params (default value)
coords (4)  
classes (20)  
num (1)  
log (0)  
sqrt (0)  
softmax (0)  
background (0)  
max (30)  
jitter (.2)  
rescore (0)  
thresh (.5)  
classfix (0)  
absolute (0)  
random (0)  
coord_scale (1)  
object_scale (1)  
noobject_scale (1)  
mask_scale (1)  
class_scale (1)  
bias_match (0)  
tree (0)  
map (0)  
anchors (0) : str of anchors separated by comma (,)  
## Internals
type, n, batch, h, w, c, out_w, out_h, out_c, cost(ptr), biases(ptr), bias_updates(ptr), outputs, inputs, truths, delta(ptr), output(ptr)