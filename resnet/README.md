# ResNet Implementation
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Jadest03/cv-paper-study/blob/main/resnet/ResNet_18_CIFAR.ipynb)

## 1. 개요 (Overview)
이 프로젝트는 **ResNet**논문을 읽고 PyTorch를 사용하여 **ResNet-18** 모델을 구현하고, CIFAR-10 데이터셋으로 학습하였습니다.
공부 중 작성하여 틀린 부분이 있을 수 있습니다.

* **Title**: Deep Residual Learning for Image Recognition (ResNet)
* **Link**: [Original Paper](https://arxiv.org/abs/1512.03385)
* **Blog Review**: [📄 ResNet 정리 블로그](https://velog.io/@jjadestarr/Deep-Residual-Learning-for-Image-RecognitionResNet)

## 2. 구현 환경 (Environment)
* **OS**: macOS
* **Language**: Python 3.x
* **Framework**: PyTorch
* **Dataset**: CIFAR-10

## 3. 학습 결과 (Results)
20 Epoch 학습을 진행하였고 다음과 같은 성능을 달성하였습니다.

| Metric | Value |
| :--- | :--- |
| **Best Accuracy** | **88.5%** |
| **Final Loss** | 0.34 |
| **Epochs** | 20 |

## 4. 실행 방법 (Usage)
1. 상단의 `Open In Colab` 링크를 클릭합니다.
2. Google Drive를 마운트합니다.
3. `모두 실행`을 실행하여 학습을 시작하거나, 제공된 가중치 파일을 로드하여 테스트할 수 있습니다.