# Haneul Park Keyword Reasearch

## Overview

하늘공원의 방문자 데이터를 시각화한다.

## Prerequisites

1. 이미지를 label로 변환한다. ([참고](https://github.com/23tae/image2label))
2. 변환한 데이터를 형식에 맞게 병합한다.
   ![excel](/assets/image_label_excel.png)

## Features

### excel_to_csv

엑셀 파일을 csv 파일로 변환한다.

| label    | frequency | confidence        |
| -------- | --------- | ----------------- |
| Person   | 409       | 96.71505139451155 |
| Outdoors | 286       | 94.3059866978572  |
| Nature   | 220       | 94.10855775312943 |
| Sky      | 207       | 95.66781513011398 |
| ...      | ...       | ...               |

### image_occurence_google

인스타그램 이미지로 생성한 csv 데이터를 바탕으로 막대그래프와 워드클라우드를 생성한다.

- 막대그래프
  ![barchart](/assets/barchart_instagram.png)
- 워드클라우드
  ![wordcloud](/assets/wordcloud_instagram.png)

### image_occurence_google

구글 이미지로 생성한 csv 데이터를 바탕으로 막대그래프와 워드클라우드를 생성한다.

- 막대그래프
  ![barchart](/assets/barchart_instagram.png)
- 워드클라우드
  ![wordcloud](/assets/wordcloud_google_images.png)

### keyword_count_google_maps

구글 지도 방문자 리뷰를 바탕으로 특정 검색어의 빈도를 막대그래프로 나타낸다.

- 막대그래프
  ![barchart](/assets/haneulpark_night_keyword_count.png)

### wordcloud_google_maps

구글 지도 방문자 리뷰를 바탕으로 워드클라우드를 생성한다.

- 워드클라우드
  ![wordcloud](/assets/haneul_googlemaps_wordcloud.png)
