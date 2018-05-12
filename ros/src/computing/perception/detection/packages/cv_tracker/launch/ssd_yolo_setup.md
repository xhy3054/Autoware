## yolo setup successfully
### set
1. with gpu
2. with yolo.weights

### next
1. the node is not complete,without a offical tutorial video,so i don't sureit can run effectively
2. should give the node a input (a camera or a video)
 
## ssd setup successfully
follow the weiliu's tutorial ,finally make distribute

### some problems(such as):
#### Makefile in ssd_caffe
change `COMMON_FLAGS += $(foreach includedir,$(INCLUDE_DIRS),-isystem $(includedir))`
to `COMMON_FLAGS += $(foreach includedir,$(INCLUDE_DIRS),-I $(includedir))`

### set
1. with gpu0
2. with ssd_300*300 model

### next
- should give the node a input(a camera or a video)

