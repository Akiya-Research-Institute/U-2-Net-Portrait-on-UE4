# U<sup>2</sup>-Net Portrait on UE4

Example UE4 project for U<sup>2</sup>-Net Portrait.  

https://user-images.githubusercontent.com/89242761/154793846-912ee234-eea7-459b-b423-83a873bfa2c0.mp4  

(Note that environment assets in this video is not included. You can get the asset from [UE market place for free](https://www.unrealengine.com/marketplace/ja/product/infinity-blade-plain-lands))

## Environment

- OS: Windows 10 64bit
- Unreal Engine: 4.26.2
- [NNEngine plugin](https://www.unrealengine.com/marketplace/product/74892c770dc149b1b5c4e872804e6ade) v1.2 or above

## Download

Please download from the [release](https://github.com/Akiya-Research-Institute/U-2-Net-Portrait-on-UE4/releases) page.  
(Or, clone this repository, download ONNX model from [here (GitHub release page)](https://github.com/Akiya-Research-Institute/U-2-Net-Portrait-on-UE4/releases/download/v0.1/U2Net_Protrait_1x512x512x3xBGRxByte.onnx) or [here (Google Drive)](https://drive.google.com/file/d/1gmS84EwwOxKy1-hhG-e477ezbMQgncis/view?usp=sharing), and place it under `Source/ThirdParty/Models`.)

## Run the demo

1. Extract the downloaded zip file and double-click `U2NetPortrait.uproject`.  
2. After launching, follow the tutorial of `/Content/NNEngineDemo-U2NetPortrait/Tutorial.uasset`.

## Model details

See the following pages for the details of the model used in this project.

- [U<sup>2</sup>-Net: Going Deeper with Nested U-Structure for Salient Object Detection](https://arxiv.org/pdf/2005.09007.pdf)
- [GitHub](https://github.com/xuebinqin/U-2-Net)
