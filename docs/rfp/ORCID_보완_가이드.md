# ORCID 누락 업적 보완 가이드 (0000-0001-5395-3284)

ORCID에 등록된 31편과 전수 조사 42편을 비교해 **빠진 11편**을 `orcid_missing_works.bib`에 담았다. ORCID는 외부에서 계정 로그인 없이 쓸 수 없으므로 아래 순서로 직접 올린다. 전체 소요 시간은 5분 내외.

## 빠진 11편

| # | 연도 | 저널 | 제목(요약) | 식별자 | 가장 빠른 등록 방법 |
|---|---|---|---|---|---|
| 1 | 2024 | Am J Emerg Med | Early lactate-related variables and 6-month neurological outcome (OHCA) | DOI 10.1016/j.ajem.2024.01.005 / PMID 38217899 | Search & link (DOI) |
| 2 | 2021 | Am J Emerg Med | Return to ED and hospitalization in elderly UTI | DOI 10.1016/j.ajem.2021.08.015 / PMID 34419709 | Search & link (DOI) |
| 3 | 2025 | Abdom Radiol | Double low-dose abdominopelvic CT for acute appendicitis | DOI 10.1007/s00261-025-05029-0 / PMID 40471255 | Search & link (DOI) |
| 4 | 2017 | Clin Exp Emerg Med | MERS outbreak and ED resource use in febrile patients (저자명 "Im") | DOI 10.15441/ceem.16.166 / PMID 28717779 | Search & link (DOI) |
| 5 | 2013 | J Korean Geriatr Soc | Chief complaints of elderly ED patients | DOI 10.4235/jkgs.2013.17.3.118 | Search & link (DOI) |
| 6 | 2014 | 대한응급의학회지 25(6):722-729 | Tertiary hospital beds expansion and ED overcrowding (저자명 "Im") | DOI 없음 | BibTeX 가져오기 |
| 7 | 2022 | 대한응급의학회지 33(6):565-572 | NLR and bacteremia in elderly ED patients | DOI 없음 | BibTeX 가져오기 |
| 8 | 2022 | 대한응급의학회지 33(6):573-580 | External validation of STONE score | DOI 없음 | BibTeX 가져오기 |
| 9 | 2023 | 대한응급의학회지 34(6):558-567 | Trends of criminal responsibility in emergency care (의료법) | DOI 없음 | BibTeX 가져오기 |
| 10 | 2024 | 대한응급의학회지 35(4):267-274 | D-dimer to fibrinogen ratio and OHCA outcome | DOI 없음 | BibTeX 가져오기 |
| 11 | 2026 | 대한응급의학회지 37(5):287-294 | SIRI and OHCA neurologic outcome | DOI 없음 | BibTeX 가져오기 |

※ Research Square 2022 프리프린트(KORHN risk score, 10.21203/rs.3.rs-1485762/v1)는 본인 확인 후 필요하면 "preprint" 유형으로 별도 추가.

## 방법 A. DOI가 있는 5편 (1~5번): 1편당 20초

1. https://orcid.org 로그인 → **Works** → **+ Add** → **Search & link** → **Crossref Metadata Search** (또는 **Add DOI**)
2. DOI를 붙여넣고 검색 → 해당 논문 옆 **Add to ORCID** 클릭
3. 추가 후 각 업적의 **Visibility**를 Everyone(공개)으로 설정

※ Crossref 검색이 어려우면 **Europe PMC**를 선택하고 PMID로 검색해도 된다(1~4번은 PMID 있음).

## 방법 B. DOI가 없는 6편 (6~11번): 한 번에 가져오기

1. `orcid_missing_works.bib`를 내려받는다 (저장소 `docs/rfp/` 폴더).
2. ORCID **Works** → **+ Add** → **Import BibTeX** → 파일 선택
3. 미리보기 목록에서 11편이 모두 보이면, **이미 방법 A로 올린 1~5번은 체크 해제**하고 6~11번만 저장 (중복 방지). 방법 A를 생략했다면 11편 전부 저장해도 된다. ORCID는 같은 DOI를 자동으로 묶어 주지만 DOI 없는 항목은 묶지 못하므로 한 번만 올릴 것.
4. 저장 후 각 항목 Visibility를 Everyone으로.

## 올린 뒤 할 일

- **이름 표기 추가**: ORCID 프로필 **Names** → **Also known as**에 `Jeeyong Lim`, `Jee-Yong Lim`, `Jee Yong Im`, `임지용`을 추가한다. 2014·2017 논문이 "Im"으로 색인된 탓에 자동 매칭에서 빠졌던 문제가 이걸로 줄어든다.
- **경력·학력 보완**: Employment에 국제진료센터(2025.05~)는 있으나 Education이 비어 있다. 박사는 2027.2 취득 예정이므로 지금은 학위 과정(in progress)으로만 적거나 취득 후 추가한다.
- **KRI 동기화**: KRI(한국연구자정보)는 ORCID 연동으로 업적을 가져올 수 있다. ORCID를 먼저 채운 뒤 KRI에서 "ORCID 업적 가져오기"를 쓰면 입력이 줄어든다. 단 대한응급의학회지 6편은 KRI 학술지 목록에서 직접 선택해 등록하는 편이 검증(기관 담당자 확인)에 유리하다.
- **Crossref 자동 갱신 켜기**: ORCID **Account settings** → **Trusted organizations**에서 Crossref 자동 업데이트를 허용해 두면 앞으로 DOI 논문은 저절로 들어온다.

## 검증 체크
- ORCID works 수가 31 → 42가 됐는지
- 11.16 이후 KRI 대표연구실적 선택 화면에서 CEU(Healthcare 2026), AI 2026, Sci Rep 2026, AGG 2021, Resuscitation 2021이 모두 선택 가능한지
