# Walmart-dataset-samples

<h2>1001개 Walmart 제품의 샘플 データセット</h2>

![Walmart dataset header](https://github.com/luminati-io/Walmart-dataset-samples/blob/main/walmart-datasets.PNG)

1000개 이상의 제품으로 구성된 Walmart データセット 샘플입니다. データセット는 <b>Bright Data API</b>를 사용하여 추출되었습니다.

<h2>이 무료 データセット에 포함된 데이터 포인트:</h2>

* ```product_id```: 제품의 고유 식별자입니다
* ```url```: 제품 링크를 나타내는 URL입니다
* ```product_name```: 제품명입니다
* ```final_price```: 제품 가격입니다
* ```currency```: 제품 가격에 사용된 통화입니다
* ```sku```: 제품 식별을 위한 Stock Keeping Unit(SKU)입니다
* ```image_urls```: 제품 이미지를 나타내는 URL 배열입니다
* ```main_image```: 메인 제품 이미지입니다
* ```rating_stars```: 1성부터 5성까지 별점 분포를 나타내는 객체입니다
* ```top_reviews```: 상위 리뷰를 나타내는 객체로, 부정 및 긍정 리뷰를 포함합니다. 각 리뷰에는 평점과 리뷰 텍스트가 포함됩니다
* ```available_for_delivery```: 배송 가능 여부를 나타내는 Boolean 값입니다
* ```available_for_pickup```: 픽업 가능 여부를 나타내는 Boolean 값입니다
* ```brand```: 제품 브랜드를 나타내는 텍스트입니다
* ```description```: 제품 설명을 나타내는 텍스트입니다
* ```specifications```: 제품 사양을 나타내는 객체 배열입니다. 각 객체에는 name과 value가 포함됩니다
* ```category_name```: 제품과 연관된 카테고리 이름입니다
* ```category_url```: 제품과 연관된 카테고리 링크를 나타내는 URL입니다
* ```root_category_name```: 제품과 연관된 루트 카테고리 이름입니다
* ```root_category_url```: 제품과 연관된 URL 링크입니다
* ```related_pages```: 제품과 연관된 관련 페이지 배열입니다
* ```breadcrumbs```: 브레드크럼 링크를 나타내는 객체 배열입니다. 각 객체에는 URL과 name이 포함됩니다

그리고 더 많은 항목이 포함됩니다.

이는 "Walmart Products (public data)"에서 파생된 샘플 서브셋이며,
해당 データセット에는 <b>371,000,000개 이상의 companies</b>가 포함됩니다.

사용 가능한 データセット 파일 형식: <b>JSON, NDJSON, JSON Lines, CSV, 또는 Parquet. 선택적으로 파일을 .gz로 압축할 수 있습니다</b>.

データセット 전달 유형 옵션: <b>Email, API download, Webhook, Amazon S3, Google Cloud storage, Google Cloud PubSub, Microsoft Azure, Snowflake, SFTP</b>.

업데이트 빈도: <b>Once, Daily, Weekly, Monthly, Quarterly, 또는 Custom basis</b>.

추출된 데이터 포인트에 추가로 제공되는 데이터 강화: <b>요청에 따라 제공됩니다.</b>

<b>[전체 Walmart データセット 받기](https://brightdata.co.kr/products/datasets/walmart)</b>.

![Walmart dataset visual](https://github.com/luminati-io/Walmart-dataset-samples/blob/main/walmart-datasets-image.PNG)

<h2>Walmart データセット의 활용 사례는 무엇입니까?</h2>

<h3>1. 소비자 시장 인사이트</h3>

재고 부족, 제품 수요 급증, 그리고 소비자 사이에서 떠오르는 트렌드를 파악할 수 있습니다. Walmart データセット를 활용하면 기업은 재고 관리를 최적화하고, 재입고 프로세스를 간소화하며, 전반적인 공급망 효율성을 개선하기 위한 전략적 의사결정을 내릴 수 있습니다.

<h3>2. 경쟁사 벤치마킹</h3>

경쟁사 전반에서 유사한 제품 및 카테고리를 비교하여 효과적인 가격 전략을 수립하고 적응형 가격 모델을 개발할 수 있습니다. Walmart データセット는 최적 가격을 식별하고, 가격 불일치를 발견하며, 데이터 기반 가격 전략을 수립하는 데 필요한 핵심 인사이트를 제공합니다.

<h3>3. 브랜드 인식 분석</h3>

제품 리뷰와 평점을 평가하여 소비자 피드백을 파악하고, 판매 제안이 시장 기대치에 부합하는지 확인할 수 있습니다. Walmart データセット는 특정 제품 또는 브랜드 전체에 대한 소비자 감성을 포착할 수 있도록 하여, 마케팅 및 판매 전략을 정보에 기반해 조정하는 데 도움을 줍니다.

<h2>학술 연구자 및 NGO를 위한 Webスクレイピング 도구와 データセット 무료 이용</h2>

Bright Initiative는 다양한 환경 및 사회적 대의를 촉진하는 주요 학술 기관 및 연구자, NGO 및 NPO에 Bright Data의 <b>[Web Scraper APIs](https://brightdata.co.kr/products/web-scraper)</b>와 <b>[바로 사용할 수 있는 データセット](https://brightdata.co.kr/products/datasets)</b>에 대한 접근 권한을 제공합니다. <b>[여기](https://brightinitiative.com)</b>에서 신청서를 제출할 수 있습니다.