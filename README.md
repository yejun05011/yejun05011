<div align="center">

# 김예준 · Yejun Kim

**Backend Developer · Java & Spring**

기능 구현부터 API 연동과 검증까지, 서비스가 실제로 동작하는 흐름을 만듭니다.

[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:dpwnsl0501@hufs.ac.kr)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://instagram.com/yejuneeei)

</div>

---

### About

한국외국어대학교 정보통신공학과 · LG CNS AM INSPIRE CAMP 6기

- Java와 Spring을 중심으로 백엔드를 개발합니다.
- 서비스 간 API 계약과 트랜잭션 경계를 고민하고, 실패 상황까지 검증합니다.
- 구현 과정의 의사결정과 문제 해결을 기록합니다.

### 🛠 Tech Stack

**Backend**

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring_Data_JPA-59666C?style=flat-square&logo=hibernate&logoColor=white)
![JDBC](https://img.shields.io/badge/JDBC-2563EB?style=flat-square&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white)

**Database & Integration**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![H2](https://img.shields.io/badge/H2-09476B?style=flat-square&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![OpenFeign](https://img.shields.io/badge/OpenFeign-6DB33F?style=flat-square&logoColor=white)
![Spring AI](https://img.shields.io/badge/Spring_AI-6DB33F?style=flat-square&logo=spring&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=flat-square&logo=intellijidea&logoColor=white)

**Also used**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white)

### 📊 GitHub Stats

<p align="center">
  <a href="https://github.com/yejun05011">
    <img height="175" alt="Yejun's GitHub Stats" src="https://github-stats-extended.vercel.app/api?username=yejun05011&show_icons=true&hide_border=false&border_color=e2e8f0&border_radius=12&title_color=2563eb&icon_color=2563eb&text_color=475569&bg_color=ffffff" />
  </a>
  <a href="https://github.com/yejun05011?tab=repositories">
    <img height="175" alt="Most Used Languages" src="https://github-stats-extended.vercel.app/api/top-langs/?username=yejun05011&layout=compact&langs_count=6&hide_border=false&border_color=e2e8f0&border_radius=12&title_color=2563eb&text_color=475569&bg_color=ffffff" />
  </a>
</p>

### 🚀 Selected Projects

#### 01 · [ICE Studyroom](https://github.com/ICE-STUDYRES/ice-studyroom)

한국외국어대학교 정보통신공학과 스터디룸 예약 시스템입니다. **랭킹과 이벤트 기반 알림 기능**의 백엔드 개발에 참여했습니다.

- Redis ZSET을 활용한 월간·학기·연간 랭킹 조회 API를 구현했습니다.
- 동점자를 상위 점수로 인식하던 문제를 수정하여 공동 순위 상황의 점수 차이를 정확히 계산하도록 개선했습니다.
- Kafka 랭킹 이벤트를 받아 웹 알림을 DB에 저장하고, 이벤트 ID 생성과 랭킹 응답 변환 책임을 분리했습니다.

[랭킹 조회 #620](https://github.com/ICE-STUDYRES/ice-studyroom/pull/620) · [공동 순위 수정 #667](https://github.com/ICE-STUDYRES/ice-studyroom/pull/667) · [웹 알림 저장 #669](https://github.com/ICE-STUDYRES/ice-studyroom/pull/669)

#### 02 · [VitaCheck](https://github.com/VitaCheck/vitacheck-be)

영양제 분석·추천과 섭취 관리를 지원하는 팀 프로젝트입니다. **복용 루틴·섭취 기록·찜하기 API**를 담당했습니다.

- 복용 루틴의 등록·수정·삭제와 사용자 정의 영양제 루틴을 구현했습니다.
- 날짜별 섭취 여부 조회와 토글 처리를 개선하고, 사용자 정의 루틴 삭제 시 소유자를 확인하도록 구성했습니다.
- 찜한 성분 목록 조회 API를 구현하고, 프론트 연동을 위한 날짜·섭취 상태의 Swagger 명세를 보완했습니다.

[사용자 정의 루틴 #187](https://github.com/VitaCheck/vitacheck-be/pull/187) · [섭취 상태·날짜 수정 #157](https://github.com/VitaCheck/vitacheck-be/pull/157) · [성분 찜 목록 #142](https://github.com/VitaCheck/vitacheck-be/pull/142)

#### 03 · [HYEJA · 청년 주거 정책 추천 서비스](https://github.com/LGCNS-AM06-Project2-TEAM5/hyeja-msa)

기존 서비스를 마이크로서비스로 전환한 팀 프로젝트입니다. **Policy 서비스 이관과 내부 API, 관심 등록 연동 및 통합 검증**을 담당했습니다.

- 정책 수집·동기화, OpenAI 정책 분석과 정책 조회 기능을 이관했습니다.
- 추천·관심 등록을 위한 내부 API 계약을 조율하고 구현했습니다. 정책 후보와 대상 지역은 일괄 조회하여 **2개 SQL로 조회**하도록 구성했습니다.
- 원격 정책 조회와 로컬 저장의 트랜잭션 경계를 분리하고, 스냅샷·관심 등록의 동시 롤백과 통신 실패 처리를 검증했습니다.
- 정책 저장 트랜잭션에 팀원이 구현한 이벤트 발행기를 연결하고, 실제 Kafka·API·화면의 통합 흐름을 검증했습니다.

[후보 조회 API #57](https://github.com/LGCNS-AM06-Project2-TEAM5/hyeja-msa/pull/57) · [관심 등록 연동 #92](https://github.com/LGCNS-AM06-Project2-TEAM5/hyeja-msa/pull/92) · [통합 검증 #123](https://github.com/LGCNS-AM06-Project2-TEAM5/hyeja-msa/pull/123)


### 📁 Others

<details>
<summary><strong>NEURON · 부트캠프 LMS 개선</strong></summary>

#### [NEURON · 부트캠프 LMS 개선](https://github.com/LGCNS6thHackathon/backend)

LG CNS AM INSPIRE CAMP 6기 해커톤 팀 프로젝트입니다. **출결·소명 권한 정리, 학생 캘린더 API와 검증**을 담당했습니다.

- 기존 출결·소명 관리 API의 권한을 ADMIN으로 통일하고, 본인 기록과 다른 학생의 기록에 대한 접근을 구분했습니다.
- 교육일정·본인 출결·최근 소명 상태·요청 가능한 정정 상태를 반환하는 월별 캘린더 API를 구현했습니다.
- 출결 수정 시 시간 필드의 생략과 명시적 null을 구분하여 기존 입퇴실 시각이 사라지는 문제를 수정했습니다.
- H2 통합 테스트와 격리된 MariaDB 환경의 실제 HTTP 요청으로 권한·소명 처리·시간 보존을 검증하고 API 연동 계약을 문서화했습니다.

[학생 캘린더 #12](https://github.com/LGCNS6thHackathon/backend/pull/12) · [입퇴실 시간 보존 #15](https://github.com/LGCNS6thHackathon/backend/pull/15) · [MariaDB 검증 #16](https://github.com/LGCNS6thHackathon/backend/pull/16)


</details>

- [ScholarBee](https://github.com/yejun05011/ScholarBee) — 캡스톤 디자인 프로젝트
- [Sporty](https://github.com/livelykitten/inspire_6th_mini_1_sporty) — 공공 체육시설 기반 운동 매칭 서비스
