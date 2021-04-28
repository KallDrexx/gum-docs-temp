---
title: NineSlice Introduction
order: 1
parent: NineSlice
grand_parent: Gum Elements
---

# NineSlice

## Introduction

NineSlice is a standard component which can be used to create visual objects which can stretch to any size without creating distortion on the source image. For example, consider the following image:

![](../../.gitbook/assets/metalPanel_blue.png)

This image could be used to create nine slices of various sizes without any distortion:

![](../../.gitbook/assets/NineSliceScreenShot.png)

The NineSlice achieves this effect by splitting the texture into nine pieces, and scales each one differently to prevent distortion. Highlighting a nine slice shows how it is split:

![](../../.gitbook/assets/NineSliceSplit.png)

This is achieved by splitting the texture into 1/3 sections wide and tall. The following image shows how the original image will be split:

![](../../.gitbook/assets/NineSliceImageSplit.png)

## NineSlice Texture

The simplest way to assign a texture to a NineSlice is to use a single file. Setting the _SourceFile_ to a single PNG will result in the NineSlice using that one texture, where each section of the NineSlice displays 1/3 of the width of the file and 1/3 of the height of the file.

Alternatively, nine files can be used to specify each section of the NineSlice independently. To use nine individual files, each file must be given a specific suffix.

The following suffixes can be added to create nine slice graphics. For example, assuming your NineSlice image is called "Image" and you are using the .png file format:

* Image\_BottomCenter.png
* Image\_BottomLeft.png
* Image\_BottomRight.png
* Image\_Center.png
* Image\_Left.png
* Image\_Right.png
* Image\_TopCenter.png
* Image\_TopLeft.png
* Image\_TopRight.png

NineSlice Properties

* [NineSlice.Texture Address](https://github.com/KallDrexx/gum-docs-temp/tree/34f8cf390aa0e8acda804733eaad97a22b8c533b/pages/gum%20elements/nineslice/NineSlice.Texture%20Address)

