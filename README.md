# Nintendo Switch 할인 정보 크롤러

닌텐도 스위치 게임의 할인 정보를 자동으로 수집하는 크롤러 프로그램입니다.

## 기능

- 닌텐도 스위치 한국 스토어의 게임 할인 정보 수집
- 할인율, 가격 정보 추출
- HTML 형식으로 결과 저장

## 프로젝트 구조

```
.
├── src/
│   ├── NintendoKorea.java    # 메인 크롤러 클래스
│   ├── model/                # 데이터 모델 클래스들
│   ├── html/                 # HTML 템플릿
│   └── util/                 # 유틸리티 클래스들
├── lib/                      # 외부 라이브러리
└── out/                      # 컴파일된 클래스 파일
```

## 요구사항

- Java 11 이상
- Maven 또는 Gradle (의존성 관리)

## 사용 방법

1. 프로젝트를 클론합니다:
```bash
git clone https://github.com/yourusername/nintendo-switch-discount.git
```

2. 프로젝트 디렉토리로 이동:
```bash
cd nintendo-switch-discount
```

3. 프로그램 실행:
```bash
java -jar nintendo-switch-discount.jar
```

## 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다.