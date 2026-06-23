# Kim Haerang

임베디드 AI, 컴퓨터 비전, FPGA, 하드웨어 연동 소프트웨어에 관심이 있습니다.

소프트웨어, AI 추론, 신호처리, 하드웨어 제어를 연결해 실제로 동작하는 시스템을 만드는 것을 좋아합니다. 최근에는 스마트 자동 세척기 캡스톤, 공학경진대회 토마토 로봇팔, MUSIC 기반 실내 위치추정 연구, Verilog/Vivado FPGA 실습을 정리하고 있습니다.

## 대표 프로젝트

### 스마트 자동 세척기

이미지 기반 얼룩 분류와 세척 계획 추천을 구현한 캡스톤 프로젝트입니다.

- 웹 UI, FastAPI 백엔드, TensorFlow Lite 추론 서버 구성
- MobileNet 기반 CNN 모델로 얼룩 이미지 분류
- 얼룩 색상, 원단 맥락, 사용자 피드백을 활용한 보정 로직 구현
- 세제 종류, 펌프 시간, 브러시 강도/횟수를 포함한 세척 계획 산출

저장소: [2026_capstone](https://github.com/Kim-haerang/2026_capstone)

### 토마토 로봇팔

공학경진대회에서 진행한 토마토 수확 보조 로봇팔 프로젝트입니다.

- 토마토 이미지 데이터셋 분석 및 bounding box 시각화
- 토마토 탐지/익은 정도 판단 흐름 정리
- 카메라 입력, 좌표 계산, 로봇팔 제어로 이어지는 시스템 구조 설계
- 대회 시연을 위한 프로토타입 문서화

저장소: [Tomato-Robot-Arm](https://github.com/Kim-haerang/Tomato-Robot-Arm)

### MUSIC 기반 실내 위치추정 연구

학부연구생 활동 중 진행한 실내 GPS/위치추정 연구 기록입니다.

- SNR, AoD 조건을 바꿔 무선 채널 데이터 생성
- 수신 위상, phase unwrapping, CFO 영향 분석
- MUSIC 기반 AoD/DoA 추정 가능성 검토
- CNN 기반 denoising/복원 실험과 RMSE 변화 관찰

저장소: `indoor-localization-music-aod`

### Verilog / Vivado 학습 기록

디지털 회로와 FPGA 실습을 정리한 저장소입니다.

- Verilog 모듈, constraints, Vivado 프로젝트 흐름 실습
- counter, seven-segment, text LCD, 초음파 센서, TFT 출력, SoC/IP 예제 정리
- Vivado 자동 생성물과 직접 작성한 소스 코드를 분리해 관리

저장소: `verilog-vivado-study`

## 기술 스택

- 언어: Python, C++, MATLAB, Verilog, HTML, CSS, JavaScript
- AI/CV: TensorFlow Lite, OpenCV, MobileNet, CNN regression
- 신호처리: MUSIC, AoD/DoA 추정, MIMO/MISO/SIMO 채널 시뮬레이션
- 백엔드: FastAPI, Uvicorn
- 하드웨어: Raspberry Pi, Arduino, FPGA, Vivado
- 도구: Git, GitHub, MATLAB, Xilinx Vivado

## 현재 정리 중인 것

- 프로젝트별 README와 실행 흐름 정리
- 실험 결과와 시연 자료를 재사용 가능한 형태로 문서화
- AI, 신호처리, 임베디드 하드웨어를 연결한 포트폴리오 구성
