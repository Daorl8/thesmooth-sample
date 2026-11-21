# STRUCTURE · thesmooth-sample (v0.1.3 · 흰 바탕 + 딥그린 · 모서리 2px · 배포 예정 thesmooth-sample.lgt3232.workers.dev)

```
thesmooth-sample/
├─ index.html                 단일 파일 (CSS · JS 인라인)
├─ wrangler.toml              name = thesmooth-sample
├─ .assetsignore              img/ · _old/ · 문서 · index_*.html · _deploy 배포 제외
├─ ts-marcellus.woff2         영문 워드마크 · 라벨 (Marcellus, 영문만)
├─ ts-pretendard.woff2        본문 · 한글 (Pretendard 300–700)
├─ ts-owner.webp              히어로 대표원장 사진 (320×400 · img/65bjkb.png · 다올 지시로 얼굴 사진 예외)
├─ ts-hero.webp               히어로 (초록 벽 간판 · 자격증, 736×920 · 4:5)
├─ ts-p2 · ts-p3 · ts-p4.webp 1:1 PRIVATE 사진 3장 (샤워실 · 관리실 · 슈가링)
├─ favicon.png · og-ts.jpg
├─ _old/                      이전 버전 백업 (배포 제외)
├─ img/                       다올 제공 원본 + _원문.md (배포 제외 · 레포에 올리지 말 것)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더 → 히어로 → `#private`(크림) → `#waxing` → `#therapy`(크림 · FACE & BODY 포함) → `#price`(탭) → `#visit`(크림) → 푸터(진한 그린) + 모바일 `.quick`.

## 버튼 · 링크
- 네이버 톡톡 `https://talk.naver.com/wd2d17w`(메인): 헤더(900 이상) · 히어로 · 오시는 길 · 하단 바
- 네이버 예약 `https://naver.me/FjmBe57p`: 히어로 · 하단 바 (다올이 링크 정상 확인 · v0.1.2)
- 전화 `tel:01065660062`: 히어로 · 오시는 길 · 푸터 · 하단 바
- 카카오톡 채널 `https://pf.kakao.com/_bpTRX`: 오시는 길
- 네이버 지도 `map.naver.com/p/entry/place/2044481788` · 인스타 · 블로그 · 플레이스(푸터)

## 가격 탭
- `.js` 있을 때만 탭 표시 · 패널 하나씩. JS 없으면 두 표 + h3 제목 모두 보임. 좌우 화살표 키 전환.
- 768 이상은 CSS `columns:2`(위→아래로 읽힘).

## 모션 (강제 재생 · 다올 방침)
- 히어로 `.intro` 등장 · 섹션 `.reveal`(setInterval) · 앵커 rAF 스크롤(R-25). reduced-motion 분기 없음.

## 폰트 재생성
문구 바꾸면 빠진 글자 검사(LESSONS §26). 한글은 Pretendard만, Marcellus는 영문만.
