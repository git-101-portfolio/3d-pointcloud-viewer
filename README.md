# 3d-pointcloud-viewer

Read and visualize 3D point cloud data.

## Overview

3D 포인트 클라우드 파일을 읽어 GUI 창에 렌더링하는 뷰어입니다.
Point Cloud Library(PCL)를 기반으로 하며, 마우스로 회전·확대·이동하며 데이터를 확인할 수 있습니다.

## Features

- 포인트 클라우드 파일 로드 (PCD / PTS / PLY)
- 마우스 인터랙션 (회전, 확대/축소, 이동)

## Requirements

- C++14 이상
- CMake 3.10 이상
- PCL 1.10 이상 (VTK 포함)
