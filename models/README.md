# GLB 모델 파일 사용법

이 폴더에 GLB 파일을 넣어서 3D 가구 배치 앱에서 사용할 수 있습니다.

## 사용 방법

### 1. 파일 업로드 (권장)
- 앱의 "GLB 파일 업로드" 버튼을 클릭하여 GLB 파일을 직접 업로드
- 가장 간단하고 안전한 방법

### 2. 콘솔 명령어
- 콘솔에서 `load <모델타입> <URL>` 명령어 사용
- 예시: `load chair /models/chair.glb`

### 3. 직접 배치
- 이 폴더에 GLB 파일을 넣고 `load <파일명>` 명령어 사용
- 예시: `chair.glb` 파일을 이 폴더에 넣고 콘솔에서 `load chair` 입력

## 예시 GLB 파일들

다음 예시 파일들이 포함되어 있습니다:
- `SheenChair.glb` - 의자 모델
- `ChairDamaskPurplegold.glb` - 의자 모델 (다른 스타일)
- `GlamVelvetSofa.glb` - 소파 모델
- `SheenWoodLeatherSofa.glb` - 소파 모델 (가죽)
- `Lantern.glb` - 램프 모델
- `LightsPunctualLamp.glb` - 램프 모델
- `IridescenceLamp.glb` - 램프 모델

## 지원 형식

- GLB (Binary glTF) - 권장
- GLTF (JSON glTF)

## 권장사항

- 파일 크기는 10MB 이하로 유지
- 텍스처가 포함된 GLB 파일 사용 권장
- 적절한 크기로 모델링된 파일 사용
- 파일명은 영문 소문자와 숫자만 사용

## 문제 해결

- GLB 로딩 실패 시 기본 geometry(빨간 박스)로 표시됩니다
- 파일 경로가 올바른지 확인하세요- 브라우저 개발자 도구에서 네트워크 탭을 확인하여 파일 로딩 상태를 확인할 수 있습니다 
