# Visual Artificial Intelligence Projects

안녕하세요!  
이 레포지토리는 **Visual Artificial Intelligence** 수업에서 진행한 과제와 프로젝트를 정리한 공간입니다.  
딥러닝과 컴퓨터 비전 기술을 학습하고, 다양한 AI 알고리즘을 활용해 문제를 해결한 결과물을 공유합니다.

---

## 수업 개요
- **딥러닝과 머신러닝의 기본 원리 학습**
- **Convolutional Neural Networks(CNN)** 구조 설계 및 활용
- 데이터 전처리, 모델 학습 및 하이퍼파라미터 최적화
- 휴리스틱 탐색 알고리즘을 활용한 문제 해결

---

## 주요 개념
### 1. Convolutional Neural Networks (CNN)
- **CNN**은 영상 데이터를 분석하고 분류하는 데 효과적인 딥러닝 모델입니다.
  - **Convolution Layer**: 이미지의 특징을 추출하는 필터 적용
  - **Pooling Layer**: 중요 특징만 추출하여 데이터 크기를 줄임
  - **Fully Connected Layer**: 출력 값을 기반으로 분류

### 2. Gradient Descent
- **Gradient Descent**는 손실 함수(Loss Function)를 최소화하기 위해 가중치를 조정하는 최적화 알고리즘입니다.
  - **Learning Rate**: 가중치 업데이트 크기를 조정하는 중요한 하이퍼파라미터
  - **Mini-Batch Gradient Descent**: 전체 데이터셋이 아닌 일부를 활용해 학습 속도 향상

### 3. Residual Network (ResNet)
- **ResNet**은 Gradient Vanishing 문제를 해결하기 위한 딥러닝 모델입니다.
  - 잔여 연결(Residual Connection)을 추가해 깊은 신경망에서도 효과적으로 학습 가능
  - 네트워크의 깊이가 증가할수록 성능이 떨어지는 문제를 해결

### 4. 탐색 알고리즘
- **BFS**: 최단 경로를 찾기 위해 노드를 계층적으로 탐색
- **DFS**: 가능한 한 깊이까지 탐색한 후 백트래킹
- **A***: 휴리스틱을 사용해 효율적으로 최적 경로 탐색

### 5. 데이터 전처리 및 시각화
- **데이터 전처리**: 이상치 제거, 데이터 정규화, 증강
- **시각화**: 학습된 모델의 활성화 값과 결과를 2D, 3D 그래프로 시각화

---

## 주요 프로젝트
### 1. CNN 기반 영상 분류
- **목적**: MNIST 데이터셋으로 손글씨 숫자 분류
- **구현**:
  - CNN 모델 설계 및 학습
  - Convolution, Pooling Layer 적용
  - 데이터 증강과 하이퍼파라미터 튜닝으로 성능 최적화
- **결과**: 테스트 정확도 89%, 학습 정확도 94%

### 2. Residual Network 실험
- **목적**: ResNet 구조와 Gradient Vanishing 문제 해결 방식을 이해
- **활동**:
  - 잔여 블록 설계 및 성능 분석
  - 깊이 있는 신경망에서도 효율적인 학습 가능성 확인

### 3. 탐색 알고리즘 실습
- **내용**:
  - BFS, DFS, 반복 심화 탐색을 통해 최적 경로 탐색
  - A* 알고리즘을 활용한 휴리스틱 기반 탐색

### 4. 머신러닝 모델 학습 및 분석
- **목적**: MNIST 데이터셋으로 모델 학습 및 활성화 값 시각화
- **결과**: 클래스 간 분포를 2D 산점도로 분석, 데이터 패턴 확인

---

## 활용 기술
- **프로그래밍**: Python, TensorFlow
- **딥러닝 모델**: CNN, ResNet
- **탐색 알고리즘**: BFS, DFS, A*
- **데이터 분석 및 시각화**: Matplotlib, Seaborn
- **데이터셋**: MNIST

---

Visual AI 기술을 통해 영상 처리 문제를 해결하며 배운 내용을 공유합니다.  
**피드백**이나 **협업 제안**은 언제든 환영합니다! 😊
