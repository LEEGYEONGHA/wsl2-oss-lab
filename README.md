# WSL2 OSS Lab
# WSL2 기반 Ubuntu 개발환경 정리

## 📁 프로젝트: wsl2-oss-lab

WSL2 환경에서 설치하고 사용한 오픈소스 소프트웨어를 정리한 프로젝트입니다.

---

## 🧩 Fork 설치 및 WSL2 연동

### 1. Fork 설치 (Windows)

- 공식 웹사이트: https://fork.dev
- 설치 후 실행

### 2. WSL2 리포지터리 열기

- WSL2 Ubuntu에서 프로젝트 생성:
  ```bash
  mkdir ~/wsl2-oss-lab
  cd ~/wsl2-oss-lab
  git init


## 🧩 ChatGPT Desktop (Snap 버전) 설치

```bash
sudo apt update
sudo apt install snapd
sudo snap install chatgpt-desktop

### 설치 후 실행 명령어
snap run chatgpt-desktop


-WSL2 Ubuntu GUI 환경에서 실행됨
### 문제점
-한영 전환(fcitx)만 작동하지 않음
'''
## 원인 분석
-AppImage 앱은 샌드박스처럼 동작해서, 로컬 환경의 IME 설정(fcitx 등)이 반영되지 않는 경우가 있음.)
-GTK/Qt 계열 앱에서 입력기 연동을 위해서는 다음 환경 변수가 필요함.)

## 해결 과정

## 🧩 Cursor 설치
