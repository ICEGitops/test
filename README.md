# 🚀 HUFS ICE GitOps Test Project

이 저장소는 **한국외국어대학교 정보통신공학과 GitOps 서비스**를 시범 운영하기 위한 테스트 프로젝트입니다. 학생 여러분은 아래 절차를 참고하여 자신의 프로젝트를 배포할 수 있습니다.

## 📋 배포 가이드 (학생용)

1. **레포지토리 생성**: 자신의 GitHub 계정에 **Public Repository**를 생성합니다.
2. **CI 설정 복사**: 
   - 이 레포지토리의 `.github/workflows/ci.yml` 파일을 자신의 레포지토리에 복사합니다.
   - `env` 섹션의 `PROJECT_NAME` 변수를 자신의 프로젝트 이름으로 변경하세요.
3. **코드 작성 및 Dockerfile**: 
   - 자신의 프로젝트 코드를 모두 작성합니다.
   - 배포를 위한 `Dockerfile`을 작성합니다. (이 레포지토리의 `Dockerfile`을 참고하여 작성하세요.)
4. **Push**: 작성한 파일을 `git push` 하여 GitHub에 올립니다.
5. **관리자 연락**: 파일 업로드가 완료되면 **관리자에게 메일**을 보내주세요! (GitOps 연동을 위함)
   - **문의처**: 고태규 21학번 (대표관리자) / [taekueko714@hufs.ac.kr](mailto:taekueko714@hufs.ac.kr)

---

## ✨ 주요 기능
- **자동화된 CI/CD**: 배포 과정을 자동화하여 코드 변경 사항을 실시간으로 반영합니다.
- **실시간 API 데모**: [api.html](https://iceweb.hufs.ac.kr/test/api.html)을 통해 동적 데이터 처리를 확인할 수 있습니다.

---
© HUFS ICE GitOps Project Team
