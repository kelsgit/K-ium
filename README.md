# 2023년 제2회 K-ium 의료인공지능 경진대회

## Description

디지털 감산 혈관조영술 표준 영상에서 특정 환자의 뇌동맥류를 발견하는 인공지능 알고리즘 개발


(세부 목표 1) : 특정환자의 뇌동맥류 존재 여부를 제시(0~1 사이의 실수 값으로 반환)


(세부 목표 2) : 뇌동맥류의 위치 정보를 제시(미존재 0, 존재 1)


## 주최

경북대학교병원, 경북대학교병원, 전남대학교병원

## People

키움화이팅 (김수인, 곽엘림, 박민영, 박지은, 하민세, 한규원)

## Pipeline
![pipeline](https://github.com/kelsgit/K-ium/assets/109035535/17a8deaa-9205-495d-8aa3-08b429504825)


## Reference

Asymmetric Loss

https://github.com/Alibaba-MIIL/ASL/blob/main/src/loss_functions/losses.py

MedNet Weight

https://huggingface.co/TencentMedicalNet/MedicalNet-Resnet18
