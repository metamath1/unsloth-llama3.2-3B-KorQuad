# Unsloth Llama 3.2 KorQuAD 파인튜닝 / Unsloth Llama 3.2 KorQuAD Fine-tuning

이 저장소는 KorQuAD 데이터셋을 사용하여 Unsloth 라이브러리와 Llama 3.2 모델을 실험한 내용을 담고 있습니다. / This repository contains an experiment using the Unsloth library and Llama 3.2 model on the KorQuAD dataset.

## 프로젝트 개요 / Project Overview

이 프로젝트는 다음과 같은 실험을 수행합니다: / This project performs the following experiments:

1. KorQuAD 데이터셋 전처리 및 준비 / KorQuAD dataset preprocessing and preparation
2. Unsloth 라이브러리를 사용한 Llama 3 모델 fine-tuning / Fine-tuning Llama 3.2 model using Unsloth library
3. 모델 성능 평가 및 결과 분석 / Model performance evaluation and result analysis

## 주요 내용 / Main Contents

- `unsloth-llama3.2-3B-KorQuad.ipynb`: 전체 실험 과정을 담은 Jupyter 노트북 / Jupyter notebook containing the entire experiment process
- KorQuAD 데이터셋 로딩 및 전처리 / Loading and preprocessing KorQuAD dataset
- Unsloth를 이용한 Llama 3.2 모델 fine-tuning / Fine-tuning Llama 3.2 model using Unsloth
- 모델 학습 및 평가 / Model training and evaluation
- 결과 분석 및 시각화 / Result analysis and visualization

## 실험 결과 / Experiment Results

- 학습 전후 모델 성능 비교 / Comparison of model performance before and after training
- Fine-tuning 효과 분석 / Analysis of fine-tuning effects
- 한국어 QA 태스크에 대한 Llama 3.2 모델의 적용 가능성 평가 / Evaluation of Llama 3.2 model's applicability to Korean QA tasks

## 사용 방법 / How to Use

1. 저장소를 클론합니다. / Clone the repository.
2. 필요한 라이브러리를 설치합니다. (requirements.txt 참조) / Install the required libraries (refer to requirements.txt).
3. `unsloth-llama3.2-3B-KorQuad.ipynb` 파일을 Jupyter Notebook이나 Google Colab에서 엽니다. / Open the `unsloth-llama3.2-3B-KorQuad.ipynb` file in Jupyter Notebook or Google Colab.
4. 노트북의 셀을 순서대로 실행하여 실험을 재현합니다. / Run the cells in the notebook in order to reproduce the experiment.

## 요구 사항 / Requirements

- Python 3.x
- PyTorch
- Transformers
- Unsloth
- Pandas
- Matplotlib
- (기타 필요한 라이브러리들) / (Other necessary libraries)

## 참고 자료 / References

- [KorQuAD 데이터셋](https://korquad.github.io/)
- [Unsloth 라이브러리](https://github.com/unslothai/unsloth)
- [Llama 3 모델](https://ai.meta.com/llama/)
- [Unsloth Notebooks](https://docs.unsloth.ai/get-started/unsloth-notebooks)
- [Youtube Tutorial](https://www.youtube.com/watch?v=0XPZlR3_GgI)

## 라이센스 / License

이 프로젝트는 MIT 라이센스 하에 배포됩니다. 

