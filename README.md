# disperser-kiosk

일신오토클레이브 **고압분산기(Nano Disperser)** 터치 키오스크. 화면 구성과 조작 방식은 HPP·WIP 키오스크와 같습니다.

- 웹 주소: https://ilshinautoclave.github.io/disperser-kiosk/
- 온라인 전용입니다. 폰트(Pretendard), QR 라이브러리, 로고를 인터넷에서 불러옵니다.
- 1920×1080 기준이며 16:10 태블릿에서는 자동으로 맞춰집니다. KR/EN/中文 전환, 2분 무입력 시 홈으로 돌아갑니다.

## 화면 구성
1. **홈**: 양산형 챔버 영상 배경, 1,500 bar · 유량 · Z/Y 챔버 · 5종 라인업
2. **분산 원리**: 압력·챔버(Z/Y) 시뮬레이터, Z·Y 챔버 비교, 3가지 공정(분산·균질 / 에멀전 / 세포벽 파괴)
3. **적용 분야**: CNT·나노 분말, 전자 소재·화학, 화장품, 식품·의약품
4. **장비 소개**: NLM100(소형 Lab) · NH500(중형 파일럿) · NH8000(대형 양산), 전체 모델 제원표, 특장점 6가지
5. **작동 영상**: 대형 양산형 Z·Y 챔버, 소형 Lab Z 챔버
6. **상담 문의**: 제품문의·A/S 번호, 약도·구글 지도, 제품 페이지 QR

## 수정 포인트
- QR 주소: `index.html`의 `CONFIG.QR_URL` (현재 suflux.com 고압분산기 페이지)
- 문구·제원: `I18N`, `CH_DATA`, `PROC_DATA`, `APP_DATA`, `SPEC`, `EQUIP_DATA`, `FEATURES`, `VIDEO_DATA`
- 이미지·영상: `assets/img`, `assets/video`

## 출처
- 제품 설명·사양표·특장점: https://suflux.com/sub/disperser.php
