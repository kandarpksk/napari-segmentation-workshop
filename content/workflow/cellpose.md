![Samples of images segmented by Cellpose](images/Cellpose-banner.png)
Cellpose-napari + FIJI
=======================

## Learning Objectives

In this lesson, you'll learn how to use the Cellpose plugin for napari, coupled with FIJI, to complete a segmentation workflow.

1.  Loading an image correctly in *Cellpose-napari*
2.  Understanding and adjusting parameters in Cellpose
3.  Segmenting and exporting your image's mask in FIJI 

- **Time to learn**: 1 hour

## Prerequisites

| Napari version and plugins                                                                     | Importance | Notes |
| -------------------------------------------------------------------------------- | ---------- | ----- |
| [napari v 0.4.14](https://chanzuckerberg.github.io/napari-segmentation-workshop/onboard/lesson3.html) | Mandatory  | In the napari viewer, verify your version of napari by clicking on the **Help** menu, then **napari info**. | |
| [cellpose v 0.1.4](https://www.napari-hub.org/plugins/cellpose-napari) | Mandatory  | Install this plugin from within the napari viewer, by going to the **Plugin** menu, then clicking on **Install/uninstall plugins**. Search for *Cellpose-napari* and click **install**. | |
| [FIJI](https://imagej.net/software/fiji/) | Mandatory  | | |
| <center>**Image inputs**</center> |  |  |
| tiffs, JPEGs or PNGs | Mandatory  | Any of these three file types will be supported | |
| Single plane images | *Optional*  | Channels can be read as: (**nY x nX x**) or (**x nY x nX**)| |
| Multiplane images | *Optional*  | Required image shape: (**nZ x nY x nX**)  | |
| Multichannel images, like multi-Z tiffs | *Optional*  | The expected format: (**nZ x nC x nY x nX**) | |


## 