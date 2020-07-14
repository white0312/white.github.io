---
layout: post
title:  "A Simpler Ray Tracer"
date:   2020-05-11
excerpt: "This project is a simple ray-tracer written in C++."
project: true
tag:
- Computer Graphics
comments: true
---

## Github
[https://github.com/navining/raytracing](https://github.com/navining/raytracing)

## Introduction
This project is a simple ray-tracer written in C++.

## Features
- Spheres
- Diffuse material
- Metal material
- Dielectric material
- Emissive material
- Shadows
- Positionable camera 
  
## Build
```
make
```

## Run
```
./raytracing [samples per pixel]
```
This will render an image of 960×540 with multiple samples per pixel (5000 by default).

The image is saved as "result.ppm" which uses PPM format. You can view the picture with
```
display result.ppm
```
or convert it into PNG format with
```
convert result.ppm result.png
```
## Result

![Result](https://raw.githubusercontent.com/navining/raytracing/master/result.png)

This image is rendered with 5000 samples per pixel, which takes approximately 30 minutes on my laptop.