# Coupang Fake Reviewer Dataset
본 데이터셋은 KCSE_2024에 게재된 "KNN 기반의 가짜 리뷰 계정 분류 모델 및 서비스 개발" 논문에 사용된 데이터 입니다. 리뷰수, 성실도, 쿠팡비율, 글자수, 작성일수 라는 5가지의 특성과 리뷰알바 여부를 포합니다. 

쿠팡 리뷰 알바에 직접 컨택하여 "빈박스 배송"이라는 리뷰알바의 특성을 파악했습니다. 이 "빈 박스 배송" 이라는 특성에 맞게 리뷰 조작 작업 시작 이후 3 일 이내에 리뷰를 작성한 379 개 계정을 가짜 리뷰로 결정했습니다.

일반 계정 확보는 쿠팡에서 애플(Apple)의 맥북 제품 판매 페이지에 접속하여 리뷰를 작성한 계정의 ID 380 개를 수집했습니다.

본 논문에서는 해당 데이터를 KNN 알고리즘을 사용한 군집분석을 사용하여 모델을 학습했습니다. 

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

|Software engineer|Data scientist|Software engineer & Data scientist|
|:----:|:----:|:----:|
|**[Cheolhyeon Han <br> 한철현](https://github.com/festring)**|**[Sebin Kwon <br> 권세빈](https://github.com/)**|**[Sangkuen Park <br> 박상근](https://skpark-khu.github.io)**|

  
## License
  
This dataset is licensed under a [CC-BY-NC-SA 4.0 License](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.ko).
  
## Citation
  
```
@misc{coupang_review_dataset
TBD
}
```
