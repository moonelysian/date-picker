# Date Picker
날짜 선택기 만들기

## Installation

```bash
> npm install
```


## Run Dev Server

```bash
> npm run start
```

## Build

```bash
> npm run build
```

----

# Snowpack
https://www.snowpack.dev/

## 주요개념
### unbundled development
- Babel, TypeScript, Scss와 같은 자주 사용하는 라이브러리로 파일을 빌드하고 EMS import/export 구문으로 브라우저에서 개별적으로 로드
- Snowpack은 파일이 변경되묜 해당 단일 파일만 다시 빌드
<img width="628" alt="스크린샷 2022-05-07 오후 2 44 10" src="https://user-images.githubusercontent.com/37898263/167240323-506f05f6-9897-46d6-bba2-f5a1c01583c9.png">

## 장점
1. 빠르다
2. 예측한 대로 동작
3. 디버깅이 더 용이함
4. 개발 파일 캐시가 더 좋음
  - 모든 파일이 개별적으로 빌드되고 캐시되기때문에 파일 변경이 없으면 다시 빌드하지 않고 브라우저에서 다시 다운로드 하지 않음
6. 프로젝트 크기가 개발 속도에 영향을 주지 않음
  - Snowpack은 50ms미만으로 시작하여 속도 저하없이 큰 프로젝트로 확장 가능
