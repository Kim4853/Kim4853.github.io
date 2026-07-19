# BongSeok Kim Academic Homepage

## 1. 압축 해제

이 압축 파일의 모든 내용을 다음 폴더에 넣으세요.

C:\bongseok-homepage

## 2. WebStorm에서 열기

WebStorm에서 `C:\bongseok-homepage` 폴더를 엽니다.

## 3. 설치

터미널에서 다음 명령을 실행합니다.

```powershell
cd C:\bongseok-homepage
bundle install
```

## 4. 실행

```powershell
bundle exec jekyll serve
```

브라우저에서 다음 주소를 엽니다.

http://127.0.0.1:4000

## 5. 반드시 교체할 파일

- `assets/images/profile-placeholder.svg`
  - 본인 사진 파일로 교체
  - 예: `profile.jpg`
  - 교체 후 `index.md`의 이미지 경로도 수정

- `assets/files/BongSeok_Kim_CV.pdf`
  - 현재 CV PDF로 교체

## 6. GitHub Pages 설정

사용자 저장소가 `username.github.io`이면 `_config.yml`을 다음처럼 설정합니다.

```yaml
url: "https://username.github.io"
baseurl: ""
```

프로젝트 저장소가 `username.github.io/homepage`이면:

```yaml
url: "https://username.github.io"
baseurl: "/homepage"
```
