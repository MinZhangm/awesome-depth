# summary-depth

## data

CAM-CONVS [coord and FVO as coord-conv]

## network architecture & layers

densenet

DeMon

multi-stage[1.1, 1.2]

FRCNPool[1.3]

near-distillation[1.7]

ASPP [1.9, 1.14]

3dcnn [deepv2d]

## loss function

revisiting normal and edge loss [1.19](metric depth)

VNL[1.17](metric depth)

deep ordinal loss[1.9](discretization depth)

scale-invariance loss[2.2.9](self-/un- supervise)

midas[1.20](relative depth/relative disparity)

point ordinal[5.2](Megadepth, RedWeb, HR-WSI)

## training strategy

midas[1.20]

diverse depth[1.18]
