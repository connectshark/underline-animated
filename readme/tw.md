# underline-animated
[![build status](https://github.com/connectshark/underline-animated/actions/workflows/deploy.yml/badge.svg?branch=main)](https://github.com/connectshark/underline-animated/actions/workflows/deploy.yml)
[![GitHub last commit](https://img.shields.io/github/last-commit/connectshark/underline-animated.svg?style=flat)](https://github.com/connectshark/underline-animated)
![GitHub stars](https://img.shields.io/github/stars/connectshark/underline-animated.svg?style=social&label=Stars&style=plastic)

[English](/README.md)

![](/readme/cover.png)
本專案使用背景顏色實現漸層底線功能，即在文字下方添加一條由多種顏色組成的漸層線

實現方法是利用CSS的background-image屬性，將一張包含漸變色彩的圖片設置為元素的背景，並通過background-size和background-position控制圖片的大小和位置，使其與文字底線重合

此外，還使用了CSS的transition屬性，讓背景圖片在滑鼠摸到時產生移動效果，從而增加視覺畫線效果

本專案參考了Kevin Powell的YouTube影片

- [Live Demo](https://connectshark.github.io/underline-animated/#/)
- [Kevin Powell](https://www.youtube.com/shorts/_1vEGYWaaQY)