# Hakaton

# Digital Breakout 2022: artificial intelligence

## MPTI Contest: Georeferencing aerial images to the basemap

### Introduction
```shell
In the modern world, a huge number of tasks are solved with the help of satellite and aerial images. Often, the speed and quality of interpreting these data depends on how quickly fires, floods and other emergencies are detected. Unfortunately, machine vision technologies are on the first stage of being implemeted to solve such tasks, but the need for them is constantly growing. The solution of this problem will allow to quickly connect images with geographical coordinates, speed up geodetic works, quickly search for the missing people, and control deforestation.
```

### Conditions

```shell
For a better understanding of the context, let's clarify the following terms:

* Basemap is an extremely large image with a geographical reference to the terrain, i.e. the coordinates of basemap' each pixel are known or they can be calculated.
* Aerial image is an image captured by a satellite, UAV, or the aircraft. It has a significantly lower resolution compared to the basemap. The main feature is that compared to the basemap the aerial image was taken in other time of the year, or even in a completely different year, and at different heights.
* Overlap - the position of images in which the same area of the basemap is visible on two or more aerial images. Mutual orientation of multi-temporal images can be done by operator manually.

The purpose of the challenge is to find a location and orientation of the image relative to the basemap.
```

### Important links

```shell
Download train dataset from here: https://lodmedia.hb.bizmrg.com/case_files/768820/train_dataset_train.zip
Download test dataset from here: https://lodmedia.hb.bizmrg.com/case_files/768820/test_dataset_test.zip
Download prepared a recent ESRI basemap from here: https://disk.yandex.ru/d/beHmDGZjzw_50A
```

### Main file
Hakaton_Permyakov_final_project.ipynb is a Jupyter notebook. Start it.

Thanks to @boangri for code ideas.
