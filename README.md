# 딥러닝을 이용한 GAN 구현

### 2020.02~2020.03
------------------

### GAN 요약설명
  - GAN = Generative Adversarial Network = 적대적 생성 모델
    > <img src="https://user-images.githubusercontent.com/47767202/87246233-fd25dc00-c486-11ea-9bd5-ae517798961b.png" width="40%"> <br>
    >> **Generator** - 지폐 위조범 / **Discriminator** - 경찰 <br>
    >> **위조범**은 경찰의 단속을 피하기 위해서 더욱 **정교한 가짜 지폐를 만들어**내고 <br>
    >> **경찰**은 더욱 정교한 기법으로 지폐를 판별해내는 방법을 개발해냄 <br>
    
    
    
    
    > <img src="https://user-images.githubusercontent.com/47767202/87246247-1dee3180-c487-11ea-904c-9993775f0aef.png" width="50%"> <br>
    >> 위의 지폐위조범-경찰 예시를 모델에 적용하여 나타낸 구조

    - =>**실제같은 형태를 갖춘 데이터를 만들어내는 알고리즘**<br>
    
------------------

### keras gan mnist tutorial
  - data: **28x28** 사이즈의 손글씨 사진 **60000**장
  > <img src="https://user-images.githubusercontent.com/47767202/87944784-cc732180-cada-11ea-9ff0-9bb0caaf68ec.png" width="30%"> <br>
  > 손글씨 사진 예시
  - 참고자료: https://colab.research.google.com/drive/1RcYxh17bwST6Wi0N5TNidoeSZc-k_XoT

------------------

### keras gan with vein data
  - data: **152x60** 사이즈의 정맥사진 **2610장**(한 사람당 엄지를 제외한 8손가락 x 한 손가락당 10번 영상획득 - 불분명한 영상 제외)
  > <img src="https://user-images.githubusercontent.com/47767202/87944940-06442800-cadb-11ea-8d1b-a5587b34c588.jpg"> <br>
  > 정맥 사진 예시<br>
  
------------------
### 참고 자료
  - https://yamalab.tistory.com/98
  - https://www.samsungsds.com/global/ko/support/insights/Generative-adversarial-network-AI-2.html
