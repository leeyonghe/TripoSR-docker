# TripoSR: Fast 3D Object Reconstruction from a Single Image (Docker Version)

이 저장소는 [원본 TripoSR 프로젝트](https://github.com/VAST-AI-Research/TripoSR)의 Docker 버전입니다. 원본 프로젝트는 단일 이미지로부터 빠르게 3D 객체를 재구성하는 오픈소스 프로젝트이며, 이 저장소는 이를 Docker 컨테이너로 쉽게 실행할 수 있도록 구성되어 있습니다.

## 원본 프로젝트 정보

- **원본 저장소**: [VAST-AI-Research/TripoSR](https://github.com/VAST-AI-Research/TripoSR)
- **원작자**: VAST-AI-Research
- **라이센스**: MIT License

## 주요 특징

- **빠른 처리 속도**: 단일 이미지에서 3D 모델을 0.5초 이내에 생성
- **고품질 결과**: 상세한 텍스처와 정확한 3D 구조
- **사용자 친화적 인터페이스**: Gradio 기반의 웹 인터페이스 제공
- **Docker 지원**: 간편한 배포와 실행을 위한 Docker 컨테이너화

## 시스템 요구사항

- NVIDIA GPU (CUDA 지원)
- Docker 및 Docker Compose
- NVIDIA Container Toolkit

## 설치 및 실행

### Docker를 사용한 설치

1. 저장소 클론:
```bash
git clone https://github.com/leeyonghe/TripoSR-docker.git
cd TripoSR-docker
```

2. Docker 컨테이너 실행:
```bash
docker-compose up --build
```

3. 웹 브라우저에서 접속:
```
http://localhost:7860
```

### 직접 설치 (원본 프로젝트 방식)

원본 프로젝트의 설치 방법은 [원본 저장소](https://github.com/VAST-AI-Research/TripoSR)를 참조하세요.

## 사용 방법

1. 웹 인터페이스에 접속
2. 이미지를 업로드
3. "Generate" 버튼 클릭
4. 생성된 3D 모델 확인

## 예제

프로젝트는 다양한 예제 이미지를 포함하고 있습니다:
- `examples/` 디렉토리에서 다양한 입력 이미지 확인 가능
- `figures/` 디렉토리에서 결과물 예시 확인 가능

## 기술 스택

- **프론트엔드**: Gradio
- **백엔드**: Python
- **딥러닝 프레임워크**: PyTorch
- **3D 렌더링**: ModernGL
- **컨테이너화**: Docker

## 라이센스

이 프로젝트는 원본 프로젝트와 동일한 MIT 라이센스 하에 배포됩니다. 자세한 내용은 [LICENSE](LICENSE) 파일을 참조하세요.

## 기여

기여를 환영합니다! 이슈 보고, 기능 요청, 또는 풀 리퀘스트를 통해 프로젝트에 기여할 수 있습니다.

## 참고 자료

- [원본 논문](https://arxiv.org/abs/your-paper)
- [원본 GitHub 저장소](https://github.com/VAST-AI-Research/TripoSR)
- [Docker 버전 저장소](https://github.com/leeyonghe/TripoSR-docker)
