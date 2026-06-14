# 정리된 전체 프로젝트 ZIP

보안을 위해 `.git/`과 이름이 `state.json`인 Terraform State 사본을 제외했습니다.
로컬 검증 과정에서 생성된 `node_modules/`도 제외했습니다. Docker 빌드 과정에서 `npm ci --omit=dev`로 다시 설치됩니다.
