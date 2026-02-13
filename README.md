## Tech Stack

### Languages
- **C / C++** (Embedded FW, ROS2 노드/라이브러리 연동)
- **Python** (ROS2 툴링/노드, 데이터 수집/전처리/실험 스크립트)

### Robotics / Middleware
- **ROS 2 (Humble)**: topic / service / action / parameter, custom interfaces, 노드 통합 및 디버깅
- **RViz2 / TF**: 센서/로봇 상태 시각화, 프레임 구성 점검
- **SLAM / Mapping**: LiDAR 기반 매핑 파이프라인 구성 및 검증(프로젝트별 적용)

### Simulation / Motion
- **Gazebo (Classic)**: URDF/SDF 환경 구성, 센서/플러그인 연동, 시뮬레이션 디버깅
- **Isaac Sim** : 시뮬레이션 환경 구성 및 시뮬레이션 디버깅
- **MoveIt2**: 매니퓰레이터 경로 계획/제어 파이프라인 구성(UR5e 기반)

### Computer Vision / ML
- **OpenCV**: 카메라 입력 처리, 전처리 파이프라인 구성
- **YOLO (Custom Fine-tuning)**: 객체 탐지 데이터셋 구성/학습/평가(버튼 인식 등)
- (필요 시) **VLM/로봇 비전 파이프라인** 연동 설계 경험

### Embedded / Hardware
- **STM32 (Nucleo-F103RB)**: CubeIDE 기반 FW 개발, USB/통신 디버깅
- **Arduino (Nano 33 IoT 등)**: 센서(Flex/IMU) 데이터 수집, 통신(UART/I2C) 연동
- **Jetson / Raspberry Pi 계열**: 로봇 컴퓨팅 보드 환경 구성 및 장치 연동

### Dev Environment / Tools
- **Linux (Ubuntu 22.04)**, **WSL + VSCode**
- **Git / GitHub**: 브랜치/이슈 기반 관리, 문서화(README/가이드) 중심 작업
- **Notion**: 협업 문서/실험 기록/설계 정리
