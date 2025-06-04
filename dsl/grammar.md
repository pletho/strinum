## Strinum DSL 문법 정의

### 기본 형태
[명령어] : [도메인.행위] (옵션=값, ...)

### 명령어 목록 (한글 원칙)
- 선언 : declare (alias)
- 조건문 : if (alias)
- 조건 성립 시 실행 : then (alias)
- 반복 : repeat (alias)
- 외부 호출 : call (alias)
- 결과 반환 : return (alias)

> 모든 명령은 한글 기반으로 정의되며,
> alias를 통해 영문 혹은 약어로 매핑할 수 있음

### 예시 선언문
선언 : 보고서.출력 (양식=매출, 대상=월간)
조건문 : 파일.존재 (경로=/data.xlsx)
조건 성립 시 실행 : 실행.파일열기 (경로=/data.xlsx)
