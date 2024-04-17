#GAN MNIST Image Generator

##프로젝트 소개
이 프로젝트는 GAN(Generative Adversarial Network)을 사용하여 MNIST 손글씨 숫자 이미지를 생성하는 심층 학습 모델을 구현합니다. 생성자(generator)와 판별자(discriminator) 두 부분으로 구성된 이 신경망은 무작위 노이즈로부터 실제와 유사한 이미지를 생성할 수 있도록 학습됩니다.

##특징
생성자 모델: 무작위 노이즈로부터 MNIST 이미지를 생성합니다.
판별자 모델: 이미지가 진짜인지 생성된 것인지를 판별합니다.
에포크별 이미지 저장: 학습 과정 중 정의된 간격마다 생성된 이미지를 저장합니다.
시각적 비교: 생성된 이미지와 실제 MNIST 이미지를 비교할 수 있는 기능을 제공합니다.
시작하기
이 섹션은 이 프로젝트를 로컬 환경에서 실행하는 방법을 설명합니다.

##필수 조건
Python 3.6 이상
TensorFlow 2.x
Matplotlib
Numpy

## 참고 : https://thebook.io/080324/0306/
