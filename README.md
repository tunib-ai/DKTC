# DKTC (<b>D</b>ataset of <b>K</b>orean <b>T</b>hreatening <b>C</b>onversations)

본 데이터셋은 [TUNiB](http://tunib.ai)이 [2021 인공지능 그랜드 챌린지](https://www.ai-challenge.kr/) 4차대회 음성인지 트랙에 참가하기 위해 자체적으로 제작한 데이터셋입니다. 이 챌린지는 임의의 대화 음성 파일을 놓고 그 대화의 성격을 위협 세부 클래스 4개 또는 일반 대화 중 하나로 예측하는 과제였습니다. 여느 대회와는 달리 주최측이 샘플 외에 별도로 학습 데이터를 제공하지 않아 참가팀이 스스로 데이터를 만들어야 했습니다. TUNiB도 대회를 준비하는 과정에서 crowd sourcing을 통해 학습 데이터를 제작하였습니다. 아쉽게도 대회 결과는 3위로 IITP원장상을 받는 것에 만족(?)해야 했으나, 우리는 이 데이터를 외부에 공개하기로 결정하였습니다. 여러 비상업적 목적으로 활용될 수 있기를 바라는 마음에서입니다.

이번에 공개하는 데이터는 학습 데이터와 테스트 데이터로 나뉘어 있습니다. 학습 데이터는 '협박', '갈취', '직장 내 괴롭힘', '기타 괴롭힘' 등 4개 클래스 각 1천 개 정도씩의 대화로 이루어져 있고, 테스트 데이터는 '협박', '갈취', '직장 내 괴롭힘', '기타 괴롭힘', '일반 대화' 등 5개 클래스 각 1백 개씩의 대화로 이루어져 있습니다. 테스트 데이터의 정답 레이블은 TUNiB에서 주관하는 AIFFEL 내부 컴피티션 종료 후에 공개 예정입니다. 학습 데이터 중 빠져 있는 '일반 대화'는 [AI Hub](https://aihub.or.kr/)의 여러 대화 데이터셋에서 내려받아 학습에 활용할 수 있습니다. 어떤 일반대화 데이터를 모으고 학습에 활용하느냐 하는 것도 중요한 학습 전략이 될 수 있습니다.:) 
    
## Quick peek
  
![image](https://user-images.githubusercontent.com/42150335/148638684-d176723b-5382-469b-847c-36047dccc3ef.png)
      
## Basic Statistics
 
|클래스|# Training|# Test |
|:----:|:------:|:------------:|
|협박 | 896    | 100   |
|갈취  |981     | 100 |
|직장 내 괴롭힘  |979     |100|
|기타 괴롭힘 |1,094      |100|
|일반 | - |100|

  
## Authors in TUNiB
  
|Data scientist|ML engineer|Software engineer|Software engineer|Research Scientist|  
|:----:|:---:|:-----:|:---:|:-----:|    
|<img src="members/sophia.png" width=150>|<img src="members/patrick.png" width=150>|<img src="members/ryu.png" width=150>|<img src="members/billie.png" width=150>|<img src="members/ryan.png" width=150>|  
|**[Soyoung Cho 조소영](https://github.com/SoYoungCho)**|**[Sangchun Ha 하상천](https://github.com/upskyy/upskyy)**|**[Myeonghyeon Ryu 류명현](https://github.com/ryubright)**|**[Bitna Keum 금빛나](https://github.com/BitnaKeum)**|**[Kyubyong Park 박규병](https://github.com/Kyubyong)**|
  
## License
  
This dataset is licensed under a [CC-BY-NC-SA 4.0 License](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.ko).
  
## Citation
  
```
@misc{DKTC
  author       = {Cho, Soyoung and Ha, Sangchun and Ryu, Myeonghyeon and
                  Keum, Bitna and Park, Kyubyong},
  title        = {DKTC, Dataset of Korean Threatening Conversations},
  howpublished = {\url{https://github.com/tunib-ai/DKTC}},
  year         = {2022},
}
```
