# OnePredict AI Study

## 소개

OnePredict AI Study 자료를 공유하는 레포지토리입니다.

처음 오신 분은 아래의 내용을 꼭 정독해주세요!

## 목표

1. 구성원의 당면한 문제를 해결할 수 있는 다양한 도구 습득
2. 자주 사용되는 방법론 혹은 새로운 기술 트렌드 습득
3. 원문을 통해 이론적, 구현 및 적용을 통한 실용적인 학습
4. 뛰어난 동료들과의 교류를 통한 다방면에서의 상향평준화
5. (+) 구현이 되어 있지 않은 알고리즘의 구현 및 배포
6. (+) 논문 작성

## 진행방법

1. 매 주 1개 이상의 주제와 발표자 선정
2. 발표자는 30분 이내로 주제에 대한 발표 진행
3. 구성원은 주제에 대하여 간단한 실험 결과 공유 및 질의응답(선택)

## 작성방법

각 주차별 폴더와 해당 주에 진행한 내용을 jupyter notebook으로 작성합니다.

```bash
├── README.md
└── W00_Template
    └── Guardian_Template.ipynb
```

notebook template은 아래의 템플릿 파일에 작성되어 있습니다.

5W1H(where 제외) + 결론의 구성입니다.

혹시 다른 구성원이 해당 문서의 코드를 활용하거나 결과의 재현이 필요한 경우가 있을 수 있습니다.

***사내 보유 데이터라면 보안 이슈를 신경 써주시고, 오픈 데이터라면 출처를 정확히 명시해주세요.***

## Cell Formatting

코드의 재사용성을 높이기 위해 [blackcellmagic](https://github.com/csurfer/blackcellmagic)을 사용하여 코드의 가독성을 높입시다.

설치 방법은 다음과 같습니다.

```bash
python3 -m pip install blackcellmagic
```

사용 방법은 다음과 같습니다. 코드가 시작하는 맨 위의 셀에서 다음 코드를 실행합니다.

```python
%load_ext blackmagiccell
```

extension이 실행된 뒤 각 셀 맨 위에 `%%black`을 넣고 셀을 실행하면, black이 해당 셀의 내용을 formatting 해줍니다.

## Repo 관리

각자가 각자의 파일에서 작업하므로 모든 작업은 master branch에서 작업하시면 됩니다.

아래 순서와 같이하시면 push과정에서 문제가 발생하지 않을 것 같습니다.

commit을 먼저하신 경우 reset으로 commit을 되돌리고 위 순서대로 진행하시면 됩니다.

```bash
git pull
git commit -m "Blah Blah"
git push
```

너무 많은 plot은 github webpage에서 열람이 불가하니 감안하셔서 작성하시길 부탁드립니다.

