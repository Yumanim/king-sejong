# 백성을 사랑한 임금, 세종대왕

바로 보기: https://yumanim.github.io/king-sejong/

**`index.html`이 두 자료를 합친 통합본입니다.** 읽는 자료(`sejong.html`)와 체험 자료(`sejong_activity.html`)를 한 페이지에 담았습니다. 업적 카드의 "🎮 직접 해 보기" 버튼으로 체험 섹션에 가고, 체험 섹션의 "📖 업적 카드 보기" 링크로 돌아옵니다. 버튼이나 메뉴로 이동한 뒤에는 화면 오른쪽 아래의 "↩ 돌아가기" 버튼을 누르면 보던 자리로 바로 돌아갑니다.

세종대왕의 생애와 업적 20가지를 정리한 학습 자료입니다. 세종대왕이 누구인지 알아본 뒤, 업적 TOP 20을 사진과 함께 카드로 살펴봅니다. 순위는 이 자료에서 정한 순서이며 공식 순위가 아닙니다.

## 대상

초등학교 중학년(3~4학년) 학생

`index.html`은 3~4학년이 읽을 수 있도록 쉬운 말로 다시 쓰고, 설명을 처음보다 약 1.5배 늘린 판입니다. 통합 전 파일인 `sejong.html`과 `sejong_activity.html`은 처음 기준인 고학년(5~6학년)용 글 그대로 남아 있습니다.

## 파일 구성

| 파일 | 내용 |
| --- | --- |
| `index.html` | 두 자료를 합친 통합본. CSS와 스크립트가 들어 있는 단일 파일 |
| `sejong.html` | 통합 전의 읽는 자료. 비교를 위해 남겨 둔 파일 |
| `sejong_activity.html` | 통합 전의 체험 자료. 비교를 위해 남겨 둔 파일 |
| `SPEC.md` | 내용, 정확도, 사진, 디자인 규칙을 정리한 기획 문서 |
| `prompt2.md`, `prompt3.md` | 체험 자료와 통합본을 만들 때 쓴 작업 지시서 |
| `README.md` | 이 안내 문서 |

## 보는 방법

1. `index.html`을 내려받습니다.
2. 파일을 더블클릭하거나 브라우저(Edge, Chrome 등)로 엽니다.
3. 위쪽 메뉴에서 묶음(세종대왕은 누구일까? · 업적 TOP 20 · 직접 해 보기 · 마무리)을 고르고, 그 아래 세부 번호를 눌러 이동합니다.

외부 라이브러리 없이 순수 JavaScript로 만들어 따로 설치할 것이 없습니다. 휴대폰에서도 볼 수 있습니다. 사진과 글꼴은 인터넷에서 불러오므로 인터넷에 연결해서 보는 것이 좋습니다. 연결이 없어도 실험은 모두 작동합니다. 이때 사진 자리에는 안내 상자가 나오고, 글자는 컴퓨터에 있는 글꼴로 보입니다. ④ 자격루에서는 소리가 나므로 필요하면 소리 끄기 버튼을 누릅니다.

## 체험 섹션 소개

읽기만 하는 자료가 아니라, 섹션마다 학생이 직접 조작하는 실험이 하나씩 있습니다. `index.html`에서는 ①~⑦이 "직접 해 보기" 묶음에, ⑧ 퀴즈가 "마무리" 묶음에 들어 있습니다.

### 섹션별 실험

| 번호 | 섹션 | 실험 |
| :---: | --- | --- |
| ① | 한글이 없었다면? | 토글을 눌러 안내문, 간판, 약 봉투의 글을 한자로 바꿔 봅니다. |
| ② | 한글은 이렇게 생겼어요 | 기본 자음과 발음 기관 그림을 짝짓고, 자음과 모음 버튼으로 글자를 조합합니다. |
| ③ | 앙부일구 해시계 | 슬라이더나 하루 재생으로 해를 움직이며 그림자와 띠 동물을 살펴봅니다. |
| ④ | 자격루 작동시키기 | 물을 부으면 살대가 떠오르고, 구슬이 굴러가 종·북·징이 울립니다. (`sejong_activity.html`은 종·징·북 순서) |
| ⑤ | 측우기로 비 재기 | 비를 내린 뒤 자의 눈금을 읽어 관측 기록장에 적고 정답을 확인합니다. |
| ⑥ | 세종 전과 후 | 카드 6장을 뒤집어 세종 전과 후의 변화를 비교합니다. |
| ⑦ | 내가 세종이라면? | 1430년 공법 의견 조사에 투표하고, 실제 결과를 막대그래프로 확인합니다. |
| ⑧ | 꼬마 역사학자 퀴즈 | 6문제를 풀며 바로 해설을 보고, 만점이면 🏆가 나옵니다. |

### 모형에 대한 참고 사항

- ③은 춘분·추분 무렵 해의 길을 위도 37.5도로 계산해 그린 모형입니다.
- ④는 원리를 줄인 모형입니다. 실제 자격루는 시에 종, 경에 북, 점에 징을 울렸으며, 세 소리가 이어서 울린 것은 아닙니다.
- ⑤의 치·푼 눈금은 실험을 위한 그림입니다. 실제로는 주척으로 물 깊이를 재서 기록했습니다.
- ⑦의 숫자는 『세종실록』 세종 12년 8월 10일 기사와 관련 자료를 기준으로 한 찬성 9만 8,657명, 반대 7만 4,149명입니다.

## 사진 출처와 라이선스

사진은 모두 위키미디어 커먼즈의 파일을 불러와 보여 줍니다. 저장소에 사진 파일을 넣지는 않았습니다. 표지의 기와지붕은 직접 그린 그림입니다.

| 순위 | 업적 | 파일 | 저작자·출처 | 라이선스 | 구분 |
| ---: | --- | --- | --- | --- | --- |
| 1 | 훈민정음 창제·반포 | [Hunminjeongeum Haerye 03.jpg](https://commons.wikimedia.org/wiki/File:Hunminjeongeum_Haerye_03.jpg) | 조선 정부(원저작) | Public domain | 현대 복원 |
| 2 | 집현전 확대 | [Sujeongjeon 2018-09-05.jpg](https://commons.wikimedia.org/wiki/File:Sujeongjeon_2018-09-05.jpg) | De-Shao Liu | CC BY-SA 4.0 | 후대 제작 |
| 3 | 측우기와 수표 | [측우기 (1).JPG](https://commons.wikimedia.org/wiki/File:%EC%B8%A1%EC%9A%B0%EA%B8%B0_%281%29.JPG) | Jocelyndurrey | CC BY-SA 4.0 | 현대 복원 |
| 4 | 농사직설 | [農事直說 농사직설.jpg](https://commons.wikimedia.org/wiki/File:%E8%BE%B2%E4%BA%8B%E7%9B%B4%E8%AA%AA_%EB%86%8D%EC%82%AC%EC%A7%81%EC%84%A4.jpg) | 한국도량형박물관 소장(e뮤지엄) | Public domain(커먼즈 표시) | 시대 미상 |
| 5 | 4군 6진 개척 | [八道総図.jpg](https://commons.wikimedia.org/wiki/File:%E5%85%AB%E9%81%93%E7%B7%8F%E5%9B%B3.jpg) | 이행 외 | Public domain | 후대 제작 |
| 6 | 자격루 | [Model of the Borugak Clepsydra (Borugak Jagyeongnu) IMG 2057.jpg](https://commons.wikimedia.org/wiki/File:Model_of_the_Borugak_Clepsydra_%28Borugak_Jagyeongnu%29_IMG_2057.jpg) | G41rn8 | CC BY-SA 4.0 | 현대 복원 |
| 7 | 앙부일구 | [Gyeongbokgung Angbuilgu (50605001138).jpg](https://commons.wikimedia.org/wiki/File:Gyeongbokgung_Angbuilgu_%2850605001138%29.jpg) | Nina R | CC BY 2.0 | 현대 복원 |
| 8 | 칠정산 | 사진 없음(영상 링크로 대체) | - | - | - |
| 9 | 혼천의·간의 등 천문기구(간의대) | [혼천의 (1).JPG](https://commons.wikimedia.org/wiki/File:%ED%98%BC%EC%B2%9C%EC%9D%98_%281%29.JPG) | Jocelyndurrey | CC BY-SA 4.0 | 현대 복원 |
| 10 | 공법 | [Veritable Records of Sejong Cover.jpg](https://commons.wikimedia.org/wiki/File:Veritable_Records_of_Sejong_Cover.jpg) | 춘추관(원저작) | Public domain | 간접 자료 |
| 11 | 갑인자 | [갑인자 (3).JPG](https://commons.wikimedia.org/wiki/File:%EA%B0%91%EC%9D%B8%EC%9E%90_%283%29.JPG) | Jocelyndurrey | CC BY-SA 4.0 | 현대 복원 |
| 12 | 향약집성방 | [향약집성방 (1).JPG](https://commons.wikimedia.org/wiki/File:%ED%96%A5%EC%95%BD%EC%A7%91%EC%84%B1%EB%B0%A9_%281%29.JPG) | Jocelyndurrey | CC BY-SA 4.0 | 후대 제작 |
| 13 | 관노비 출산휴가 | [世宗总序.jpg](https://commons.wikimedia.org/wiki/File:%E4%B8%96%E5%AE%97%E6%80%BB%E5%BA%8F.jpg) | 저작자 표시 없음 | CC0 | 간접 자료 |
| 14 | 아악 정비와 편경 | [Musical instruments on display at the MIM (14328676636).jpg](https://commons.wikimedia.org/wiki/File:Musical_instruments_on_display_at_the_MIM_%2814328676636%29.jpg) | Frank Kovalchek | CC BY 2.0 | 현대 복원 |
| 15 | 정간보 | [Museum of Traditional Korean Music 041.JPG](https://commons.wikimedia.org/wiki/File:Museum_of_Traditional_Korean_Music_041.JPG) | Piotrus | CC BY-SA 3.0 | 후대 제작 |
| 16 | 용비어천가 | [Yongbieocheonga display.jpg](https://commons.wikimedia.org/wiki/File:Yongbieocheonga_display.jpg) | Nuyos | Public domain | 현대 복원 |
| 17 | 삼강행실도 | [Samganghaengsildo in museum.jpg](https://commons.wikimedia.org/wiki/File:Samganghaengsildo_in_museum.jpg) | Salamander724 | Public domain | 판본 미상 |
| 18 | 의방유취 | [의방유취 (醫方類聚).jpg](https://commons.wikimedia.org/wiki/File:%EC%9D%98%EB%B0%A9%EC%9C%A0%EC%B7%A8_%28%E9%86%AB%E6%96%B9%E9%A1%9E%E8%81%9A%29.jpg) | 조선 정부(원저작) | Public domain | 후대 제작 |
| 19 | 대마도 정벌과 계해약조 | [日本國對馬島之圖.jpg](https://commons.wikimedia.org/wiki/File:%E6%97%A5%E6%9C%AC%E5%9C%8B%E5%B0%8D%E9%A6%AC%E5%B3%B6%E4%B9%8B%E5%9C%96.jpg) | 신숙주(원저작) | Public domain | 후대 제작 |
| 20 | 화포 개량과 신기전(총통등록) | [Korean rocket arrows.jpg](https://commons.wikimedia.org/wiki/File:Korean_rocket_arrows.jpg) | Kai Hendry | CC BY 2.0 | 현대 복원 |

### 참고 사항

- 구분은 사진 속 유물이 언제 만들어진 것인지를 나타냅니다. 세종 때 실물로 확인된 사진은 없습니다.
- 7위, 9위, 20위의 "현대 복원"은 파일 설명이나 안내판으로 확인하지 못해, 전시 상태를 보고 판단했습니다.
- 4위 사진은 커먼즈에 퍼블릭 도메인으로 표시되어 있지만, 출처인 e뮤지엄 페이지에는 공공누리 제3유형(출처표시+변경금지)으로 적혀 있습니다.
- 칠정산은 알맞은 사진을 찾지 못해 [KBS 역사추리 영상](https://youtu.be/uiCYedCV0bk?si=GW2RMtuxutwCW23y) 링크를 넣었습니다.
