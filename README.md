# Visual Artificial Intelligence Projects

안녕하세요!  
이 레포지토리는 Visual Artificial Intelligence 수업에서 진행한 과제와 프로젝트를 정리한 공간입니다.  
딥러닝과 컴퓨터 비전 기술을 실습하며 얻은 다양한 결과물을 공유합니다.

---

## 수업 개요
- **Convolutional Neural Networks(CNN) 설계 및 학습**  
  MNIST 데이터셋을 활용해 손글씨 숫자 분류 모델을 구현하고 성능 분석.  

- **Residual Network(ResNet) 이해**  
  Gradient Vanishing 문제를 해결하는 ResNet의 잔여 연결 구조를 분석.  

- **데이터 전처리 및 하이퍼파라미터 최적화**  
  데이터 증강, 학습률 스케줄, 드롭아웃 등 다양한 최적화 기법 실습.  

---

## 주요 프로젝트
### 1. CNN 기반 영상 분류 및 시각화
- **목적**: MNIST 데이터셋으로 손글씨 숫자 분류 및 특징 시각화.
- **결과**:
  - 훈련 정확도: 94%, 테스트 정확도: 89%.
  - CNN의 학습된 활성화 값을 산점도로 시각화하여 클래스 간 분포 확인.
- **개선 작업**: 데이터 증강, L2 규제, 드롭아웃을 적용하여 성능 최적화.

### 2. Residual Block 설계
- **목적**: ResNet의 잔여 연결을 통해 Gradient Vanishing 문제를 해결.
- **활동**:
  - 수식을 통해 잔여 블록 구조 분석.
  - Conv5 레이어의 Receptive Field 계산.

### 3. 논문 리뷰
- **주제**: "Automatic Classification of Radar Signals Using CNN"
- **요약**: 레이더 신호를 CNN으로 분류하여 기존 매핑 기반 접근법의 한계 해결.

### 4. 과적합 및 과소적합 문제 해결
- **내용**:
  - 과적합: 배치 크기 증가와 학습률 조정으로 해결.
  - 과소적합: 다양한 특징 추가 및 더 많은 에포크 학습.
- **결과**: 손실 값 변화와 모델 경계 명확성을 분석하여 개선.

---

## 활용 기술
- **프로그래밍**: Python, TensorFlow
- **알고리즘 및 모델**: CNN, ResNet, Gradient Descent
- **데이터셋**: MNIST
- **영상 처리**: Sobel, Canny 등 엣지 감지 알고리즘

---

Visual AI 기술을 통해 다양한 문제를 해결하며 배운 내용을 바탕으로 더 나은 프로젝트를 만들고 싶습니다.  
피드백이나 협업 제안은 언제든 환영합니다! 😊
