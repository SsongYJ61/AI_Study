# 🧠 이미지 및 영상처리 AI 학습 커리큘럼 (5일 완성)

## ✅ 목표
- 이미지와 영상 데이터의 구조 및 처리 원리를 이해하고  
- OpenCV 및 딥러닝 프레임워크(PyTorch, YOLO 등)를 활용하여  
- 실전 수준의 영상처리 AI 프로젝트를 구현하는 것을 목표로 한다.

---

## 📆 학습 계획

### 📅 DAY 1 (화요일) — 이미지 처리 기초 이해
**학습 주제**
- 이미지의 기본 구조 (픽셀, RGB, Grayscale)
- OpenCV를 활용한 이미지 파일 읽기/쓰기/표시
- 이미지 전처리: 크기 조절, 자르기, 회전
- 필터 처리: Blur, Sharpen, Canny Edge Detection

**실습 과제**
- 여러 필터를 조합하여 예술적 스타일 이미지 만들기
- 이미지 2장을 비교하여 차이점 시각화하기

---

### 📅 DAY 2 (수요일) — 영상 처리 기초 및 모션 감지
**학습 주제**
- 영상 데이터의 개념 (프레임, FPS, Codec 등)
- OpenCV로 웹캠 및 영상 파일 처리
- 프레임 간 차이 계산
- 배경 제거 및 모션 감지

**실습 과제**
- 웹캠 기반 모션 감지 시스템 구현
- 움직임이 감지될 때 녹화 및 저장 기능 구현

---

### 📅 DAY 3 (목요일) — 딥러닝 기반 이미지 분류
**학습 주제**
- CNN(Convolutional Neural Network) 기초 이론
- PyTorch를 활용한 이미지 분류 모델 구현
- 공개 데이터셋(CIFAR-10, MNIST 등) 활용
- 전이 학습(Transfer Learning) 소개 및 실습

**실습 과제**
- 직접 촬영한 이미지로 간단한 분류기 학습
- 전이 학습을 적용해 성능 비교

---

### 📅 DAY 4 (금요일) — 객체 탐지(Object Detection)
**학습 주제**
- 객체 탐지(Object Detection) 개념 이해
- YOLOv8 구조 및 기본 사용법
- Ultralytics YOLO 라이브러리 실습
- 실시간 객체 탐지 및 결과 시각화

**실습 과제**
- YOLO로 웹캠 또는 영상 파일 내 객체 탐지
- 특정 클래스만 필터링하여 탐지 결과 출력

---

### 📅 DAY 5 (토요일) — 실전 미니 프로젝트
**프로젝트 주제 예시**
- 신호등 건너는 사람 감지 시스템
- CCTV 영상 기반 사람 추적 시스템
- 특정 이벤트 감지 (예: 멈춰있는 사람 알림)

**실습 과제**
- AI Hub 등에서 공개된 데이터셋 사용
- 전처리 → 탐지 → 시각화 파이프라인 구현
- 결과 요약 및 영상 저장

---

## 🛠 사용 기술 스택

| 목적 | 도구 |
|------|------|
| 이미지/영상 처리 | OpenCV, PIL |
| 딥러닝 프레임워크 | PyTorch, Ultralytics YOLO |
| 시각화 도구 | matplotlib, cv2.imshow |
| 학습 데이터 | AI Hub, Kaggle |

---

## 🔗 참고 자료
- [OpenCV 공식 튜토리얼](https://docs.opencv.org/)
- [Ultralytics YOLO Docs](https://docs.ultralytics.com/)
- [PyTorch 튜토리얼](https://pytorch.org/tutorials/)
- [AIHub 영상 데이터](https://www.aihub.or.kr/aihubdata/data/list.do?domain=video)

---

## 📌 To-Do List
- [ ] OpenCV 설치 및 실습 환경 구성
- [ ] DAY 1 실습 완료
- [ ] DAY 2 실습 완료
- [ ] DAY 3 CNN 모델 학습 완료
- [ ] DAY 4 객체 탐지 결과 확인
- [ ] DAY 5 프로젝트 완성 및 정리
