# Passcend Server

---

Passcend 서버 프로젝트는 모든 Passcend 클라이언트 애플리케이션의 백엔드를 위한 API, 데이터베이스 및 기타 핵심 인프라를 포함합니다.

서버 프로젝트는 ASP.NET Core와 함께 .NET Core를 사용하여 C#으로 작성되었습니다. 데이터베이스는 T-SQL/SQL Server로 작성되었습니다. 코드베이스는 Windows, macOS 및 Linux 배포판에서 크로스 플랫폼으로 개발, 빌드, 실행 및 배포할 수 있습니다.

## 개발자 문서

빌드 지침, 권장 도구, 코드 스타일 팁 등에 대한 자세한 내용은 프로젝트 문서를 참조하세요.

## 배포

Docker 컨테이너를 사용하여 Windows, macOS 및 Linux 배포판에 Passcend를 배포할 수 있습니다. 제공된 PowerShell 및 Bash 스크립트를 사용하여 빠르게 시작하세요.

### Requirements

- [Docker](https://www.docker.com/community-edition#/download)
- [Docker Compose](https://docs.docker.com/compose/install/) (already included with some Docker installations)

_These dependencies are free to use._

### Linux & macOS

```sh
# Docker Compose를 사용한 설치
docker-compose up -d
```

### Windows

```cmd
# Docker Compose를 사용한 설치
docker-compose up -d
```

## 기여하기

코드 기여를 환영합니다! `main` 브랜치에 대해 Pull Request를 제출해주세요.

보안 감사 및 피드백을 환영합니다. 민감한 보안 문제는 비공개로 보고해주세요. 보안 정책은 [`SECURITY.md`](SECURITY.md) 파일을 참조하세요.

## 원본 프로젝트

이 프로젝트는 [Bitwarden Server](https://github.com/bitwarden/server)를 기반으로 합니다.

### Dotnet-format

Consider installing our git pre-commit hook for automatic formatting.

```bash
git config --local core.hooksPath .git-hooks
```
