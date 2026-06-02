# Generating-a-Teeth-Image-with-Pix2pix
2023 Undergraduate Research Project, Creating Teeth Images

# Reference
- https://github.com/mrzhu-cool/pix2pix-pytorch/blob/master/train.py
- https://github.com/eriklindernoren/PyTorch-GAN
- https://www.kaggle.com/code/ibtesama/gan-in-pytorch-with-fid
- https://github.com/mseitzer/pytorch-fid

# 📋 연구 내용 요약

Pix2Pix를 이용한 이미지 생성 with FID 평가

치아 이미지(위에서 찍은 2D)를 대상으로 Pix2Pix GAN을 구현해 스케치, 실사 이미지 변환을 수행하고, 생성 품질을 FID(Fréchet Inception Distance) 지표로 정량 평가한 프로젝트.

3D 치아 데이터 → 2D로 직접 데이터 가공 (약 120~150장) → 스케치 데이터 가공(포토샵) → 원본 데이터, 스케치 데이터를 이용하여 Pix2Pix GAN으로 이미지 생성
→ 이미지가 원본과 비슷하게 생성 되었는지 FID 지표로 평가
