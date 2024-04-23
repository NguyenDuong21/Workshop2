---
title : "Giới thiệu"
date :  "`r Sys.Date()`" 
weight : 1 
chapter : false
pre : " <b> 1. </b> "
---
### Kiến trúc của bài lab

#### Nhập dữ liệu từ RDS(Postgres) vào S3 bằng AWS Database Migration Service

![IngestionToS3](/images/01-arch.png) 

#### Chuyển đổi dữ liệu với các service Glue và lưu lại vào S3

![TransformationsData](/images/02-arch.png) 

#### Khám phá dữ liệu bằng các công cụ truy vấn và trực quan hóa dữ liệu.

![VisualizationData](/images/03-arch.png)

#### Áp dụng Machine Learning sử dụng dịch vụ SageMaker

![VisualizationData](/images/04-arch.png)