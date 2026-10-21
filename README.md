# fontIndex

내 PC의 서체를 한눈에 탐색하고 비교하는 Windows 서체 앱입니다.

## 다운로드

**[최신 버전 다운로드 및 설치 안내](https://github.com/jooyeohun/fontindex-downloads/releases/latest)**

[Windows 설치 파일 받기 · 약 62MB](https://github.com/jooyeohun/fontindex-downloads/releases/download/v1.0.0-build-894a882c0014/fontIndex-1.0.0-894a882c0014-Windows-x64-Setup.exe)

[압축 실행본 받기 · 약 42MB](https://github.com/jooyeohun/fontindex-downloads/releases/download/v1.0.0-build-894a882c0014/fontIndex-1.0.0-894a882c0014-Windows-x64-Unpacked.zip) · [SHA-256 체크섬](https://github.com/jooyeohun/fontindex-downloads/releases/download/v1.0.0-build-894a882c0014/SHA256SUMS.txt)

버전 **1.0.0** · 빌드 **894a882c0014** · Windows 64비트 · 2026-10-21 배포

## 시작하기

1. 설치 파일을 내려받아 실행합니다.
2. 바탕화면 또는 시작 메뉴에서 fontIndex를 실행합니다.
3. 첫 실행 시 설치된 서체를 자동으로 읽습니다.

Python·NexusFont·기존 폰트 DB가 필요하지 않습니다. TTF·OTF·WOFF2 파일을 가져오고 미리볼 수 있습니다. 설치되지 않은 서체는 앱에 드래그해서 추가합니다. 원본 서체를 변경하지 않습니다.

압축 실행본은 ZIP 전체를 압축 해제하고 fontIndex.exe를 실행하세요. _internal 폴더를 함께 유지해야 합니다. 데이터는 설치본과 동일하게 사용자 AppData에 저장됩니다. 사용자 서체 파일과 개인 DB는 배포 파일에 포함하지 않습니다.

## 보안 경고에 관하여

현재 **Authenticode 서명이 없는 개인 개발 배포본**입니다. Edge의 다운로드 평판 경고나 Windows 실행 경고가 표시될 수 있습니다. 이 배포 페이지나 ZIP 형식이 경고 해제를 보장하지 않습니다. 출처와 체크섬을 확인하고 신뢰하는 파일만 실행 여부를 결정하세요. 보안 기능을 전체 해제할 필요는 없습니다. 관리되는 PC에서는 정책에 따라 실행이 제한될 수 있습니다.

설치 파일 SHA-256:
```text
894a882c0014bedf8b55bd9422f5894b22ba980b3413bfd836d6132c9482eb92
```

파일 확인은 PowerShell의 `Get-FileHash -Algorithm SHA256 -LiteralPath '파일 경로'`로 할 수 있습니다. 체크섬은 동일성 확인이며 안전 인증은 아닙니다.

## 업데이트와 문의

업데이트는 [Releases](https://github.com/jooyeohun/fontindex-downloads/releases)에서 확인하세요. [오류 제보](https://github.com/jooyeohun/fontindex-downloads/issues)는 OS 버전·빌드 식별자·오류 문구를 포함해 주세요. 개인 DB, 유료 서체 파일, 계정 정보는 올리지 마세요.

이 저장소는 배포 파일과 안내 전용입니다. 현재 macOS용 최신 수정본은 게시하지 않습니다.
