# Korea Weather MCP Server

본 MCP 서버는 기상청 단기 예보 조회서비스 API를 이용한 MCP 서버입니다.

## 소개

Korea Weather MCP Server는 날씨 정보를 수집하고, 이를 MCP를 통해 Claude나 Cursor와 같은 MCP Client(Host)에게 제공합니다.  
해당 서버는 기상 정보를 기반으로 한 다양한 응용 서비스에 활용될 수 있습니다.

## 주요 기능

- 기상청 단기 예보 API 연동
- MCP 형식의 기상 데이터 제공

## 사용 방법

1. [data.go.kr](https://www.data.go.kr/)에서 기상청 단기예보 API 활용 신청 후 API 키를 발급받습니다.  
2. 환경설정 파일에 MCP 서버를 등록하고, API 키는 환경변수에 설정합니다.

## 의존성

- Python 3.x
- `requests` 등 (자세한 내용은 `pyproject.toml` 참고)

## 라이선스

본 프로젝트는 내부 시험용으로 개발되었으며, 별도의 라이선스 규정 없이 자유롭게 배포 및 수정이 가능합니다.

## 문의

개발자: 한국항공우주연구원 오한 (ohhan@kari.re.kr)
