# painting-animation
Animating paintings using CNN:

## 1. Motion prediction

Recurrently computed on each frame to predict the next frame.

## 2. Color transfer

Applied independantly to each frame.

## To try on any .png image:
- put your image in the inputs directory
- go to your terminal and type: 

```
python test.py --gpu 0 -i ./inputs/your_image.png -o ./outputs  
```
- the videos (motion loop, color loop, final video) will be generated in the outputs directory

## References

This repository contains mostly code of the following paper:
```
@article{endo2019animatinglandscape,
  title = {Animating Landscape: Self-Supervised Learning of Decoupled Motion and Appearance for Single-Image Video Synthesis},
  author = {Yuki Endo and Yoshihiro Kanamori and Shigeru Kuriyama},
  journal = {ACM Transactions on Graphics (Proceedings of ACM SIGGRAPH Asia 2019)},
  year = {2019},
  volume = 38,
  number = 6,
  pages = {175:1--175:19}
}
```
