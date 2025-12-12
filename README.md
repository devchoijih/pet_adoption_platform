# webPawinhand_copysite

Spring Framework와 Oracle DB 기반으로 구현한 반려동물 입양/분양 서비스 플랫폼입니다.
실제 서비스 “포인핸드(Pawinhand)”의 핵심 사용자 흐름을 분석하여,
입양 공고 관리 · 회원 인증 · 공고 조회/검색 · 상세 페이지 · 찜 기능 등을 풀스택 구조로 새롭게 설계하고 구현했습니다.

이 프로젝트의 목표는 단순 클론이 아니라
실제 서비스 구조를 분해 → 도메인 모델링 → 레이어드 아키텍처로 재구성하여
백엔드 실무 중심으로 풀스택 애플리케이션을 완성하는 것입니다.

## 📌 개발 목표
실서비스의 UI/UX를 참고하여 백엔드 중심 도메인 재설계
Spring MVC 기반 Controller–Service–Repository 구조 구현
회원 가입/로그인/세션 인증 흐름 직접 구현
Oracle 기반 데이터 모델링(ERD 설계 → 테이블 구축)
리스트/상세/검색 기능을 통한 비즈니스 플로우 전체 구현

## 🎯 프로젝트 개요
- 포인핸드 UI/UX를 참고한 웹 애플리케이션 클론
- 유기동물/입양 공고 목록 및 상세 페이지 구현
- 회원 가입 / 로그인 등 기본 인증 흐름 연습
- Oracle DB 연동을 통한 실서비스와 유사한 데이터 처리 경험

## 🛠 기술 스택
- **Backend**: Java, Spring (MVC)
- **Frontend**: JSP, JavaScript, CSS
- **Database**: Oracle 11g / 12c
- **Build & ETC**: Maven (pom.xml 기반)

## 🧩 핵심 기술 설계 & 선택 이유

✔ 왜 Spring MVC인가?
최초 실무에서 많이 쓰는 레이어드 아키텍처 학습 목적
스프링 생태계 구조(Controller–Service–DAO)를 직접 다뤄보기 위함
트랜잭션 처리와 DI 기반 설계 이해

✔ 왜 Oracle DB인가?
실무에서 사용하는 RDB 구조와 가장 비슷한 환경
외래키, 제약조건, 인덱스 설계 등 실무 DB 경험 강화
JOIN 기반의 복잡한 검색 쿼리 작성 경험
