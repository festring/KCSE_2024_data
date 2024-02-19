# Coupang Fake Reviewer Dataset
본 데이터셋은 KCSE_2024에 게재된 "KNN 기반의 가짜 리뷰 계정 분류 모델 및 서비스 개발" 논문에 사용된 데이터 입니다. 

리뷰수, 성실도, 쿠팡비율, 글자수, 작성일수 라는 5가지의 특성과 가짜리뷰(리뷰알바) 여부를 포합니다. 

**가짜 리뷰 계정 379 개**는 쿠팡 리뷰 알바 모집에 직접 참여한 뒤, 일정 기간동안 교차검증을 거쳐 수집했습니다.

**일반 계정 확보 380 개**는 쿠팡에서 애플(Apple)의 맥북 제품 판매 페이지에 접속하여 리뷰를 작성한 계정을 수집했습니다.

더 자세한 데이터의 수집 과정은 논문에 기재되어 있습니다.

본 논문에서는 해당 데이터를 KNN 알고리즘을 사용한 군집분석을 사용하여 모델을 학습했습니다. 

논문 링크 : https://drive.google.com/file/d/101KFHvzcPjdnRjvUpIcIx52hzjzj9o3Q/view?usp=sharing

논문 발표  PPT 링크 : https://drive.google.com/file/d/103WUVOTpQPE5UeIm92n9txpHohvecrlb/view?usp=sharing

## Sample
<img width="588" alt="image" src="https://github.com/festring/coupang_review_dataset/assets/146055385/9fc35c47-139f-4014-b869-f40b8bbbdd79">


## Basic Information
 
|클래스|Info|
|:----:|:------:|
|리뷰수 | 해당 계정이 작성한 리뷰개수  | 
|성실도  | 전체 리뷰 중 ‘성실한 리뷰’ 비율    | 
|쿠팡비율  |전체 리뷰 중 판매자가 쿠팡(주)로 표기된 제품에 작성한 리뷰의 비율|
|글자수 |평균 리뷰 글자수      |
|작성일수 | 리뷰를 작성된 날짜의 수 |
|알바여부 |해당 계정의 알바 여부입니다. 0은 일반 계정, 1은 가짜 계정입니다. |


## Authors
|:----:|:---:|:-----:|
|**[Cheolhyeon Han <br> 한철현](https://github.com/festring)**|**[Sebin Kwon <br> 권세빈](https://github.com/)**|**[Sangkuen Park <br> 박상근](https://skpark-khu.github.io)**|

  
## License
  
This dataset is licensed under a [CC-BY-NC-SA 4.0 License](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.ko).
  
## Citation
  
```
@conference{han2024developing
  title     = {Developing an Account-Level Fake Reviewer Detection Model and Service using KNN},
  author    = {Han, Cheolhyeon and Kwon, Sebin and Park, Sangkuen },
  booktitle = {Korea Conference on Software Engineering},
  pages     = {146--151},
  year      = {2024}

}
```
