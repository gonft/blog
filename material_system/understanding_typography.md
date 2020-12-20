# Understanding typography
타이포그래피는 계층과 브랜드 존재를 표현합니다.

## 서체 속성
서체는 글자 모음입니다. 각 문자는 고유하지만 특정 모양은 문자간에 공유됩니다. 서체는 편지 모음에서 공유되는 패턴을 나타냅니다.

스타일, 가독성 및 가독성을 위해 선택된 서체는 인쇄 디자인의 기본 원칙을 따를 때 가장 효과적입니다.
![](https://lh3.googleusercontent.com/XN6ATtQ7Q_NxH5Eb_ZMiAZI6Wh61nClqWKHyx10vhIly8lzEOKmswVEAxjQOzldyCJ_q5W6dTznM0fn5wS8ArPzhpDq4vfhUxnOz=w1064-v0)

## Baseline
**Baseline**은 텍스트 행이 놓이는 보이지 않는 선입니다. 머티리얼 디자인에서 베이스 라인은 텍스트와 요소 사이의 수직 거리를 측정 할 때 중요한 사양입니다.

### 4dp grid
서체는 4dp 기준선 그리드에 맞춰집니다.
![](https://lh3.googleusercontent.com/mNkwfYnbuTcOwsNz2YVjhf671pizs_a9WR7TSlA4mM6UuUpx7tbJ1i0VP2MqM_XE0-Vq0tpu-TzV3vnXgVqFvE30gUuViiApGWum=w1064-v0)
pt / sp 크기에 관계없이 텍스트의 기준선은 4dp 그리드에 있어야합니다. 그리드를 유지하려면 Line-height는 4로 나눌 수있는 값이어야합니다.

### Measurement from the baseline
기준선에서 UI 요소까지의 거리를 지정합니다. 기준 값은 소프트웨어와 무관하므로 모든 디자인 프로그램에서 작동하고 그리드와 함께 작동합니다. Android 및 iOS에서 코드는 기준 기준 사양에서 패딩으로 변환 될 수 있습니다. 웹의 경우 Sass 또는 CSS를 사용하여 계산을 자동화합니다.

![](https://lh3.googleusercontent.com/Ff6eGNbOu56cP-dnwB12aNVwwj5-E63WDw50QSyz_nvuuv-KDk9Zwa94uXZhtC8JkoZGY-s3PUdmn3kx7DagED-vK1tvmzuqiS31Tw=w1064-v0)
경계 상자 대신 수직 정렬을위한 기준 기준선을 참조하십시오. 이를 통해 설계 소프트웨어 및 플랫폼 전반에서보다 정확한 구현이 가능합니다.

![](https://lh3.googleusercontent.com/I9TxT6CNxN9Qjq_PVeBDD7qKRX_QRqZFGmDMfLV8SLYYgnRL10oVq6RbZAmPdPqgt95C2vBXCWUZbmWxXioN3_WFJXgyCoApk6U0oA=w1064-v0)
다른 구성 요소와 관련하여 텍스트를 측정합니다.

## Cap height
**Cap height**는 기준선에서 측정 한 서체의 평평한 대문자 (예 : M 또는 I)의 높이를 나타냅니다. S 및 A와 같은 둥글고 뾰족한 대문자는 동일한 크기의 효과를 얻기 위해 캡 높이 위에 약간 오버 슈트로 그려져 광학적으로 조정됩니다. 모든 서체에는 고유 한 캡 높이가 있습니다.
![](https://lh3.googleusercontent.com/GV5FQ8hady9sQU0eHxUw_6O3TqPBxd1hezBNMSyw8WfdibMPZIMqt3x4gXVJWN7exKc-MT6teHqKNGnrbXPvLYq01weNCr2NVhVb5Q=w1064-v0)

## X-height
X-height는 서체의 소문자 x 높이를 나타내며 서체의 각 글리프의 높이 또는 길이를 나타냅니다.
x- 높이가 긴 서체는 각 글자의 공백이 더 읽기 쉽기 때문에 작은 글꼴 크기에서 더 가독성이 좋습니다.
![](https://lh3.googleusercontent.com/iF6wBmzTnSHNp-T_P5fIOhLoqiaiPQGSkXwprlQYa7sYzxgieax7zCm2OgKXInHSsDIbgjUWZKUk2eM6y1yb7ud623QmleY6qfJdz4M=w1064-v0)
서체의 소문자 x 높이에 따라 x 높이가 결정됩니다.

## Ascenders and descenders
Ascenders는 캡 높이 또는 기준선을 넘어 확장되는 특정 소문자에서 발견되는 획의 수직선상 가장 위. Descenders는 수직선상 획의 가장 아래. 경우에 따라 **line height** (기준선 사이의 수직 거리)가 너무 좁을 때 이러한 스트로크간의 충돌이 발생할 수 있습니다.
![](https://lh3.googleusercontent.com/YuIcT_rJ-AI0Efux7od-ufftpYmTDzdnXr0Nh8r7HPyq612tNJbjZDthpV-i1JUNcPc7hiddSLtwDSWPvB0OdGNvdHCYsK8Gd6qfpg=w1064-v0)

## Weight
**Weight**는 글꼴 획의 상대적 두께를 나타냅니다. 서체는 여러 가지 가중치로 올 수 있습니다. 4-6 개의 가중치는 서체에 사용할 수있는 일반적인 숫자입니다.
![](https://lh3.googleusercontent.com/p1KHRGapQZb8fK8Rbzlcn7Iav_wkhcIR7m2s6FlM77Bxd5xooIFVAruSKZahO0nSwkfeWNK9NoDEgBE1ZCX8KB6AmtGAs_5PrGFeXQ=w1064-v0)

