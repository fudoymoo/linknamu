# 링크 나무 (Link in Bio 서비스)

## 프로젝트 개요

Linktree처럼 내 모든 링크를 한 페이지에 모아두고 하나의 URL로 공유할 수 있는 서비스 입니다.

## 참고 문서
- Next.js 에이전트 규칙: @AGENTS.md
- 제품 요구사항: @PRD.md
- 화면 와이어프레임: `docs/wireframe.png` — UI 작업 전 반드시 이 이미지를 열어 레이아웃(원형 프로필 사진 → 이름 → 한 줄 소개 → 링크 카드 목록, 가운데 정렬)을 확인할 것

## 기술 스택
- Next.js 16 (App Router)
- Tailwind CSS
- MongoDB Atlas (클릭 수 저장)
- Vercel (배포)

## 주요 기능
- 프로필 표시 (이름, 소개, 사진)
- 링크 카드 목록
- 링크 클릭 수 집계

## 코드 규칙
- TypeScript 사용
- 컴포넌트는 src/components/ 아래에 작성
- 환경 변수는 .env.local에 저장 (절대 커밋하지 않음)
- 모바일 우선 반응형 디자인
