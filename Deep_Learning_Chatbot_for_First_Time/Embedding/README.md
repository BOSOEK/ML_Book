# Embedding
> 컴퓨터가 처리할 수 있도록 자연어를 __숫자나 벡터 형태로 변환하는 것.__

임베딩 기법에는 문장 임베딩과 단어 임베딩이 있다
* 문장 임베딩 : 문장 전체를 벡터로 표현하는 방법
  > 장점 : __문맥적 의미를 가진다.__ -> 단어 임베딩보다 품질이 좋으며, 상용 시스템에 많이 사용됨.
  > 단점 : 임베딩을 위한 문장 데이터가 많이 필요하며, __비용이 많이 든다__
* 단어 임베딩 : 개별 단어를 벡터로 표현하는 방법
  > 장점 : 문장 임베딩보다 학습이 간단하다
  > 단점 : 의미가 달라도 형태가 같다면 동일한 벡터값으로 표현

***

### 임베딩 방식
* #### [원-핫 인코딩](https://github.com/BOSOEK/Machine_Learning_with_Book/blob/main/Deep_Learning_Chatbot_for_First_Time/Embedding/one-hot-encodding.ipynb)
* #### [희소 표현과 분산 표현](https://github.com/BOSOEK/Machine_Learning_with_Book/blob/main/Deep_Learning_Chatbot_for_First_Time/Embedding/%ED%9D%AC%EC%86%8C%ED%91%9C%ED%98%84_%EB%B6%84%EC%82%B0%ED%91%9C%ED%98%84.md)
* #### [Word2Vec](https://github.com/BOSOEK/Machine_Learning_with_Book/blob/main/Deep_Learning_Chatbot_for_First_Time/Embedding/Word2Vec.ipynb)
