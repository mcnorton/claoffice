# Claoffice

Claude Code가 일하는 모습을 3D 사무실로 보여 주는 macOS 앱입니다.
Claude Code를 쓰는 프로젝트마다 층이 생기고, 그 안에서 Claude와 에이전트가 방을 오가며 일합니다.

## 다운로드

**[최신 버전 다운로드](https://github.com/mcnorton/claoffice/releases/latest)**: Release 페이지의 `claoffice_<버전>_universal.dmg`를 받으세요.

## 필요한 것
- macOS 13 이상 (Apple Silicon, Intel)
- Claude Code: 최근 7일 안에 쓴 프로젝트가 층으로 나타납니다.

## 설치
1. 받은 DMG를 엽니다.
2. `claoffice`를 `Applications` 폴더로 끌어다 놓습니다.
3. 응용 프로그램에서 Claoffice를 엽니다.

Claude 폴더(보통 `~/.claude`)는 스스로 찾습니다. 찾지 못하면 왼쪽의 **폴더 선택** 버튼으로 고르세요.

## 업데이트
새 버전이 나오면 오른쪽 위에 업데이트 버튼이 나타납니다. 누르면 새 버전을 받아 서명과 공증을 확인한 뒤 앱을 다시 엽니다.

## 읽는 데이터와 네트워크
- Claude Code 세션 기록(`~/.claude/projects`)을 읽기만 합니다. 고치지 않습니다.
- 네트워크는 업데이트를 확인하고 받을 때만 씁니다. 이때 GitHub에 다운로드 요청만 보내고, Claude Code 기록은 어디로도 보내지 않습니다.

이 저장소는 배포 전용이라 소스 코드는 없습니다.
