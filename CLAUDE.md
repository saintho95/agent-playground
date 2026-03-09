# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

이 프로젝트는 **코드 개발이 아닌 기획문서 산출용 프로젝트**입니다.
**크러쉬팝(CrushPop)** — AI 캐릭터 챗 서비스에 대한 기획문서(PRD, 화면설계서/스토리보드 등)를 작성하고 관리하는 기획 자동화 에이전트입니다.

### 서비스 개요
- **서비스명**: 크러쉬팝 (CrushPop)
- **서비스 유형**: AI 캐릭터 챗 서비스
- **핵심 기능**: 사용자가 AI 캐릭터와 대화하는 챗 경험 제공

## 문서 작성 규칙

- **작성 언어**: 한국어
- **기본 포맷**: Markdown (.md)
- 요청에 따라 적절한 파일 형식을 선택:
  - `.pptx` — 화면설계서/스토리보드
  - `.docx` — 공식 기획서, 외부 공유용 문서, 보고서
  - `.pdf` — 최종 산출물, 리뷰용 문서
  - `.csv`, `.html` — 데이터 정리, 프로토타입 등
- **산출물 저장 위치**: `docs/` 폴더 아래 양식별로 분류 저장
  - 예: `docs/prd/`, `docs/storyboard/` 등
- 템플릿/섹션 규칙은 추후 정의 예정

## 주요 산출물 유형

- PRD (Product Requirements Document) — 제품 전체 기획서
- 화면설계서 / 스토리보드 — UI/UX 화면 흐름 및 설계

## Environment

- Python 3.14 with a local virtualenv at `.venv/`
- Activate: `source .venv/bin/activate`
- Install dependencies: `pip install -r requirements.txt` (when available)
- Python은 문서 생성 자동화 스크립트 등에 활용

## Language

- 문서 본문: 한국어
- 코드(자동화 스크립트) 내 주석 및 변수명: English