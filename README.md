# ORB-SLAM2 MacOS

This is a port of [ORB-SLAM2](https://github.com/raulmur/ORB_SLAM2) to MacOS. Tested on MacOS High Sierra and Xcode 9.

## Install
**CMake:** `mkdir xcode && cd xcode && cmake .. -G Xcode`

## Changes
The following changes were made from the original repository:

1. Remove Pangolin requirement.
2. Remove Viewers and Drawers as consequences of Pagolin removal.
3. Auto build and link `g2o` and `DBoW2` from `Thirdparty`.
4. Set build examples off by default.
