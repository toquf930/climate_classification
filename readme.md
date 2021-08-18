# [DACON] 자연어 기반 기후기술분류 AI 경진대회 4등 코드 

<NewStar>팀은 두명이 서로 다른 모델을 사용하였기 때문에 코드의 파이프라인은 크게 2가지로 나누었습니다.  

1. train_j.py -> inference_j.py
2. train_s.py -> inference_s.py

두 개의 파이프라인이 끝나면 inference.py를 실행하여 최종 csv파일이 생성됩니다.

위의 과정을 모두 포함한 스크립트 파일을 실행하면 됩니다.

```bash
bash run.sh
```

파일 용량이 큰 관계로 코드와 중분류를 위한 자료만 첨부합니다. 

다음 [링크](https://drive.google.com/drive/folders/1DXJkhQr3Eybut7XrBgjBt-GM3apNoWHM)에서 train.csv, test.csv를 data_s와 data_j/original/에 넣으면 됩니다.

============================================================================================

Since the team <NewStar> used two different models, the code pipeline was divided into two major parts.

1. train_j.py -> inference_j.py
2. train_s.py -> inference_s.py

At the end of both pipelines, the final csv file is generated by running inference.py.

All you have to do is run the script file that includes all of the above steps.

```bash
bash run.sh
```
Due to the large file size, only the code and material for middle classification are attached.
Just download train.csv and test.csv from [link](https://drive.google.com/drive/folders/1DXJkhQr3Eybut7XrBgjBt-GM3apNoWHM) and then put them in data_s and data_j/original/.

============================================================================================

### System Requirements
python=3.8  
tokenizers=0.10.3     
torch=1.9.0  
transformers=4.8.1  
pandas=1.2.5  
