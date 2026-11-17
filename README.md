# 건축공학딥러닝프로그래밍 — 실습 노트북

경희대학교 건축공학과 · 실습 노트북 저장소
강의노트(이론): [Notion 강의노트](https://positive-wakeboard-965.notion.site/6f8d1e3037c54b0788bf77e010612e00) · 강의 영상: e-campus(Canvas) 과목 모듈

## 실습 목록

| 실습 | 주제 | 실습본 (빈칸 채우기) | 완성본 (정답 · 실행결과) |
|:-:|---|:-:|:-:|
| PyTorch 첫걸음 · Part 1 | 손으로 풀었던 XOR, PyTorch로 다시 풀기 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/baekja/Lecture_DL-AE/blob/main/PyTorch_XOR/xor_practice.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/baekja/Lecture_DL-AE/blob/main/PyTorch_XOR/xor_complete.ipynb) |
| PyTorch 실전 · Part 2 | 이미지 6만 장, FashionMNIST 옷 분류 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/baekja/Lecture_DL-AE/blob/main/PyTorch_FashionMNIST/fashion_mnist_practice.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/baekja/Lecture_DL-AE/blob/main/PyTorch_FashionMNIST/fashion_mnist_complete.ipynb) |
| PyTorch CNN | 손글씨 숫자(MNIST)를 합성곱 신경망으로 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/baekja/Lecture_DL-AE/blob/main/PyTorch_MNIST_CNN/mnist_cnn_practice.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/baekja/Lecture_DL-AE/blob/main/PyTorch_MNIST_CNN/mnist_cnn_complete.ipynb) |
| PyTorch RNN·LSTM·GRU | 예나(Jena) 기상 관측 데이터로 1시간 뒤 기온 예측 · 다음 6시간 한꺼번에(many-to-many) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/baekja/Lecture_DL-AE/blob/main/PyTorch_RNN_Jena/jena_rnn_practice.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/baekja/Lecture_DL-AE/blob/main/PyTorch_RNN_Jena/jena_rnn_complete.ipynb) |
| PyTorch 한영 번역 Seq2Seq→Transformer | 짧은 건설 문장 한→영 번역을 같은 데이터로 Seq2Seq(GRU) → 어텐션 → Transformer 순서로 직접 학습하고 비교 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/baekja/Lecture_DL-AE/blob/main/PyTorch_KoEn_Seq2Seq_Transformer/koen_steps_practice.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/baekja/Lecture_DL-AE/blob/main/PyTorch_KoEn_Seq2Seq_Transformer/koen_steps_complete.ipynb) |

## 사용법
1. 위 표의 **Open in Colab** 배지를 누릅니다.
2. Colab 메뉴 **파일 → Drive에 사본 저장** 을 누른 뒤, 사본에서 작업합니다.
3. 위에서부터 차례대로 셀을 실행합니다(`Shift + Enter`). GPU는 필요 없습니다.

## 라이선스
- 코드: [MIT](LICENSE)
- 노트북의 설명 글(마크다운): [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.ko)
