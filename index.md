---
layout: lesson
root: .
---


데이터 과학(Data Science)이라는 말이 회자된지는 몇년이 되지 않았지만, 인공지능(AI)과 함께 현재 가장 많이 회자되고 있는 단어가 되었다.
앞서 [데이터 사이언스 입문](https://statkclee.github.io/yonsei/) 교육과정에서 학습한 것을 바탕으로 다양한 분야에서 다뤄지는 데이터를 가져오고, 탐색적으로 분석하고, 가설을 세우고, 모형을 제작하고 의사결정권자와 커뮤니케이션을 하거나 제품과 서비스를 만들어 배포하는 기술을 습득한다. 기본 데이터 사이언스 언어로 **R**과 **파이썬**을 함께 사용한다.
이를 통해서 4차 산업혁명의 원재료인 데이터를 가지고 사회경제적 가치가 있는 제품과 서비스를 개발할 수 있는 역량을 갖추게 되어 데이터를 자신감을 갖고 바라보게 된다.

> ## 선수과목
>
> 이번 수업에 선수과목이 필요하지만, 공개된 데이터를 바탕으로 차근차근 배워간다는 열정과 열린 마음이 중요합니다.
> [데이터 사이언스 입문](https://statkclee.github.io/yonsei/) 교육과정을 이수하지 않는 경우
> 학습량이 많을 수가 있으니 수업전에 시간을 별도로 내서 
> [데이터 사이언스 입문](https://statkclee.github.io/yonsei/) 교육과정을 충실히 학습한다.
> 여기에는 초등학생이 많이 배우는 [컴퓨터 과학 언플러그드](http://statkclee.github.io/unplugged),
> 중고생들에게 관심이 많은 파이썬 계열의 [리보그 - 프로그래밍과 문제해결](https://statkclee.github.io/code-perspectives/),
> [파이썬 거북이](http://swcarpentry.github.io/python-novice-turtles/index-kr.html), [정보과학을 위한 파이썬](https://statkclee.github.io/pythonlearn-kr/)을 
> 수업 전 읽어두면 도움이 많이 될 것이다. 또한, [소프트웨어 카펜트리 5.3](http://statkclee.github.io/swcarpentry-version-5-3-new/) 및
> 최근 있었던 [소프트웨어 카펜트리 한림대학교 워크샵](https://statkclee.github.io/2018-10-27-hallym/) 교재를 숙독하면 도움이 많이 될 수 있다.
> [데이터 사이언스 입문](https://statkclee.github.io/yonsei/)과 달리 중급 이상의 파이썬 이해가 필요하기 때문에 [모두를 위한 파이썬](https://statkclee.github.io/pythonlearn-kr/)을 선행학습해 둘 것을 권장한다.
{: .prereq}

## 인터랙티브 강의노트

- [9월05일](https://etherpad.net/p/de-2019-09-05) - 뽀개기, [열섬(heat island)](https://github.com/shd04121/heat_island_ds_yonsei)
    - [구글 docs: 09월05일](https://docs.google.com/document/d/13JxRp6Xq4lW33UGr--paF4OBi7etBsOSSDeYQm51km8)
- [9월20일](https://etherpad.net/p/de-2019-09-20) - AWS 특강
    - [구글 docs: 9월20일](https://docs.google.com/document/d/1GfpdQ0A9_d1ICFeutBO2nS6FuM0MeJ5nbCI1rgeEfaQ/edit?usp=sharing)
- [9월27일](https://docs.google.com/document/d/18XEUkLKgGpYT1UwA1-9BdWHyP4ySu3_rBzDg4fkBb5c/edit?usp=sharing)
- SK C&C 문용준 부장님 특강 (10월 11일)
    - "실제 기업에 적용되는 인공지능" &rarr; `numpy`
    - "하나는 비대면 채널에 인공지능 적용" &rarr; `pandas`
- 슬랙 채널: [Software Engineering for Data Science](https://appstat.slack.com)
- [10월25일](https://etherpad.net/p/yonsei-20191025) - 중간고사
- [11월01일](https://etherpad.net/p/yonsei-20191101)
- [11월08일](https://docs.google.com/document/d/14-t2dHqXpK1jabaDECU_vB30PsrqptZ48PLNIB3enl8/edit?usp=sharing)
- [11월15일](https://docs.google.com/document/d/1-L_KSQ1bfeehn2VeuY3jvbZW0AxTd7-AH1wkmNfSDGc/edit?usp=sharing)
- [11월22일](https://docs.google.com/document/d/1Me2FYSRH_tLD6y0GZZTf4OTZixpIexn_YFWZmV0x9Ag/edit)
- [11월29일]()
- [12월06일]()
- [12월13일]() - 기말고사

## 특강 안내

- 한림대 디지털 리터러시 특강
    - 강의자료: [글쓰기는 자동화의 시작 - 데이터 과학의 세계](https://statkclee.github.io/ds-authoring/ds-digital-literacy.html#/) 
    - 장소 및 일시: 한림대학교 임베디드 실습실 (대학본부 5층 2519호), 2019년 9월 17일 오후 4:30 ~ 6:30
- 혁신성장 일자리 위원회 기획토론회: [4차 산업혁명과 대한민국 혁신성장 활로모색](https://statkclee.github.io/ds-authoring/ds-4th-ir.html)
    -  일시 및 장소: 2019. 10. 07(월) 14:00 ~ 16:00, 국회의원회관 제8간담회실
- 2019 소프트웨어(SW) 정보교육 담당 교원 대상 연수: [데이터 과학 시대 재현가능한 글쓰기](https://statkclee.github.io/ds-authoring/ds-kofac-writing.html#/)
    -  일시 및 장소: 한국과학창의재단, 11월 9일, 대전 인터시티 호텔
- [~~로봇~~ 자동화가 빼앗는 일자리 그리고 나](https://statkclee.github.io/ds-authoring/ds-bundang-2019.html)
    -  일시 및 장소: 분당 서현 청소년 수련관, 12월 4일(수) 10:00 ~

## 프로젝트

- [11대 0](https://github.com/whoareyouwhoami/ProjectTellus): [주용우](https://github.com/whoareyouwhoami), [박지원](https://github.com/jiwon12-31/), [윤정하](https://github.com/dial0116), [정희영](https://github.com/jojo-kr/)
- [연세투어](https://github.com/yonseijaewon/yonsei-tour): [권예린](https://github.com/yerinKwon), [이재현](https://github.com/leequant761), [김성진](https://github.com/ZachKim-fromKorea), [허재원](https://github.com/yonseijaewon)
- [4달러](https://github.com/lhmlhm1111/Data_GongHak/): [이학민](https://github.com/lhmlhm1111), [최호식](https://github.com/ghos0905), [김호성](https://github.com/dsrla123), [이진원](https://github.com/jinwon1)
- [서울시 축제 대백과](https://github.com/HGmin1159/Seoul_Festival): [민형규](https://github.com/HGmin1159), [정민지](https://github.com/MINNJI), [박상우](https://github.com/glassduck), [최호경](https://github.com/dollhy)

    