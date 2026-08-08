# 운동 가이드 — 배포용 레포

클라이밍 강습 가이드와 숄더 교정 가이드를 정적 사이트로 서빙한다.
Cloudflare Pages가 이 레포를 **빌드 없이 루트 그대로** 배포한다.

| 경로 | 내용 |
|---|---|
| `/` | 랜딩 |
| `/climbing/` | 클라이밍 강습 가이드 (Lesson 01–17) |
| `/shoulder/` | 숄더 교정 가이드 |

## 직접 수정하지 말 것

이 레포의 파일은 전부 **생성물**이다. 원본은 별도의 private 레포(`workout`)에
있고, 거기서 `bash publish.sh`를 실행하면 이 레포의 내용이 통째로 갱신된다.
여기서 고친 내용은 다음 배포 때 덮어써진다.

## Cloudflare Pages 설정

| 항목 | 값 |
|---|---|
| Framework preset | None |
| Build command | (비움) |
| Build output directory | `/` |
| Production branch | `main` |

## 이미지 라이선스

본문 사진은 Wikimedia Commons의 CC 라이선스 이미지를 핫링크로 사용하며,
저자와 라이선스는 각 문서 내 캡션에 표기했다.
