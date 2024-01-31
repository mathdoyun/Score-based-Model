## Score-based Model

논문 링크: [Score-based Model](https://arxiv.org/pdf/1907.05600.pdf)

Score-based model은 score function과 물리학에서 입자의 움직임을 수학적으로 분석하여 얻은 식인 Langevin dynamics를 이용하여 샘플을 생성하는 모델이다. 본 논문에서는 Langevin dynamics의 한계점을 제시하며 더욱 발전된 방법인 Annealed Langevin dynamics를 제안하고 있다.

<img src="https://github.com/mathdoyun/Score-based-Model/assets/135238974/f0870c22-6ccd-417d-ad78-f9d6ac4b2c37" width="75%" height="75%"/>

Score-based model을 이용하면 score function을 학습하고 이를 이용하여 기존의 데이터 분포를 따르는 샘플을 생성할 수 있는데, 직접 코드를 작성하며 실습해보았다.

> 출처: https://github.com/JeongJiHeon/ScoreDiffusionModel/tree/main/NCSN
