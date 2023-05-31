# sass 사용거의 안함. scss를 사용한다. scss-->샤스라고 읽음
![image](https://github.com/3dodam/scss/assets/129016953/999f9e0e-59de-464d-8723-f5a33bd9729a)

## scss 컴파일
![image](https://github.com/3dodam/scss/assets/129016953/2f9a8601-53f4-480b-9748-a4ffa96937b3)

## css 위치변경
![image](https://github.com/3dodam/scss/assets/129016953/936a7573-434f-4e3b-90f5-5b0db0634a82)

## savaPath:null이면 scss파일과 같은위치에 style.css가 생긴다
![image](https://github.com/3dodam/scss/assets/129016953/2c69dd20-fa65-4ed1-a6bb-ec787c959de7)

## ~은 style.scss를 의미, /는 style.scss가있는 폴더
![image](https://github.com/3dodam/scss/assets/129016953/95d585fd-b32d-4b1e-b3cd-9d6de92305fe)

## scss파일이 있는 폴더의 상위요소에 생성
![image](https://github.com/3dodam/scss/assets/129016953/2476a96a-3f86-422f-8c5e-9bd803651ae6)

## 주석처리 방법
## //주석처리방법은 css로 컴파일되지 않는다
## /* */주석처리방법은 css로 컴파일되어 나타남
![image](https://github.com/3dodam/scss/assets/129016953/95793d88-f629-4cb4-bac9-ec6a59a6d610)

## 변수만들기 --> $로 시작함,(영문, 숫자, - , _)만 사용할수 있음. 숫자로 시작할수 없음.
![image](https://github.com/3dodam/scss/assets/129016953/6eeefead-122b-4c7c-90ef-e2851338dd62)


## Partials(파샬)
-- 관련된것끼리 묶어서 분리/ 소스에 반복되는 부분들을 분리 분산시켜서 모듈화 시키는 기능

Partials의 파밍명은 _로 시작하며
불러들일때는 @import '파일명', 이때 파일명에 _는 포함시키지 않고, 확장명도 포함시키지 않는다.
💠 Scss는 _로 시작하는 파일은 컴파일하지 않는다.

![image](https://github.com/3dodam/scss/assets/129016953/3730abb0-53b5-44ee-9c1f-f5b0a98706ce)

