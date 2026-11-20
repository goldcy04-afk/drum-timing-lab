# Drum Timing Lab

메트로놈에 맞춰 드럼을 치면, 마이크로 타격을 듣고 박마다 얼마나 빠르고 늦은지 알려주는 웹 연습 도구예요.

- **연습**: 메트로놈, 실시간 타이밍 표시, 안정성·정확도, 박별 분석
- **악보 연습 (베타)**: 악보바다에서 받은 드럼 악보 PDF를 불러와서, 구간을 골라 따라 치면 마디별로 채점해요
- **분석**: 오차 분포, 타격 흐름, CSV 내보내기

설치 없이 브라우저에서 열면 돼요. 마이크를 쓰기 때문에 https 주소에서 열어야 해요.

## 개인정보

마이크 소리와 불러온 PDF는 모두 사용자의 기기(브라우저) 안에서만 처리하고, 어디로도 전송하지 않아요.
이 저장소에는 어떤 악보 파일도 포함되어 있지 않아요. 악보는 사용자가 직접 구매한 파일을 자기 기기에서 불러와 써야 해요.

## 사용한 오픈소스

- [pdf.js](https://github.com/mozilla/pdf.js) — Apache License 2.0 (실행 시 jsDelivr CDN에서 불러옴)
- [SEED Design](https://github.com/daangn/seed-design) 디자인 토큰 (`@seed-design/css`) — Apache License 2.0, Copyright 2025 주식회사 당근마켓. 당근마켓의 로고·상호 등 브랜드 리소스는 사용하지 않음
- [Lucide](https://lucide.dev) 아이콘 — ISC License. Copyright (c) for portions of Lucide are held by Cole Bemis 2013-2022 as part of Feather (MIT). All other copyright (c) for Lucide are held by Lucide Contributors 2022.
- [Pretendard](https://github.com/orioncactus/pretendard) 글꼴 — SIL Open Font License 1.1 (jsDelivr CDN에서 불러옴)
