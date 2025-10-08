# Smart Parking System

**Smart Parking System**은 차량의 입출차 관리, 요금 계산, 정기권 및 할인 정책 등  주차장 운영 전반을 효율적으로 관리할 수 있는 **웹 기반 통합 주차 관리 시스템**입니다.  **JSP + Servlet + JDBC** 기반의 MVC 구조로 설계되었으며,  로그인 → 입출차 → 요금 계산 → 마이페이지/관리자 페이지까지 전 과정을 직접 구현했습니다.

---

## Project Overview

- **프로젝트명**: Smart Parking System  
- **개발 인원**: 2명  
- **기간**: 2025.06.25 ~ 2025.07.11 (16일)  
- **구성**: 사용자 키오스크 + 관리자 웹 관리 페이지  

---

## Team Role

| 이름 | 담당 역할 |
|------|------------|
| **Rachel (Seojeong Yun)** | 풀스택 개발 · 마이페이지 및 사용자 기능 구현 |
| **Seong Won Park** | 풀스택 개발 · 관리자 페이지 및 대시보드 구현 |

---

## Tech Stack

- **Language / Backend**: Java, JSP, Servlet, JDBC  
- **Database**: MariaDB  
- **Frontend**: HTML, CSS, JavaScript, jQuery  
- **Tools**: IntelliJ IDEA, Apache Tomcat, DBeaver, Git  

---

## Core Features

- **차량 입출차 관리** – 입차/출차 시간 기록 및 요금 자동 계산  
- **요금 계산 + 할인 정책** – 기본/추가 요금, 정기권 할인 기능  
- **로그인 및 권한 분리** – 세션 기반 인증, 관리자 필터 적용  
- **실시간 주차 현황 조회** – 주차 중 차량 수 및 장기 주차 알림  
- **공지사항 / 마이페이지 / 관리자 대시보드** 전체 구현  
- **Git 브랜치 전략 적용 및 협업 워크플로우 정리**

---

## 요금 / 정책 로직 예시

| 항목 | 내용 |
|------|------|
| **기본 요금** | 1시간 2,000원 |
| **추가 요금** | 30분당 1,000원 |
| **장기 주차** | 24시간 이상 차량 별도 표시 |
| **할인 정책** | 정기권 소지 시 요금 면제 또는 할인 적용 |

---

## 주요 화면

<table>
  <tr>
    <td width="50%" valign="top">
      <b>회원가입</b><br/>
      <sub>사용자 정보 등록 및 로그인 연동</sub><br/><br/>
      <img alt="회원가입" src="https://github.com/user-attachments/assets/cf0ac3cb-304c-4336-966b-3d2639606b8f" width="100%"/>
    </td>
    <td width="50%" valign="top">
      <b>멤버십 관리</b><br/>
      <sub>정기권 등록 / 기간별 할인 정책 확인</sub><br/><br/>
      <img alt="멤버십 관리" src="https://github.com/user-attachments/assets/7b49ac7e-66f6-48ab-a521-84deef274f2e" width="100%"/>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b>입차 등록</b><br/>
      <sub>차량번호 입력 → 입차 시각 DB 저장</sub><br/><br/>
      <img alt="입차 등록" src="https://github.com/user-attachments/assets/0a4ca436-40e1-48de-8ccb-8b61293fbf87" width="100%"/>
    </td>
    <td width="50%" valign="top">
      <b>주차기록 조회</b><br/>
      <sub>이용 내역 및 요금 결제 정보 확인</sub><br/><br/>
      <img alt="주차기록 조회" src="https://github.com/user-attachments/assets/c7486d6b-491e-445e-bae0-25eb168faab5" width="100%"/>
    </td>
  </tr>
</table>

---

## Demo Preview

<table>
  <tr>
    <td width="100%" valign="top">
      <b>홈화면 → 페이지 이동</b><br/><br/>
      <img alt="기능 시연1" src="https://github.com/user-attachments/assets/b1da4eb3-97eb-4f53-8114-77e0cd778511" width="100%"/>
    </td>
  </tr>
  <tr>
    <td width="100%" valign="top">
      <b>로그인 → 마이페이지 이동</b><br/><br/>
      <img alt="기능 시연2" src="https://github.com/user-attachments/assets/06867204-e31a-4f3f-91a5-f86936120e9d" width="100%"/>
    </td>
  </tr>
</table>

---

## Retrospective

- Servlet 기반 **클래식 MVC 웹 구조**를 직접 설계하며 백엔드 로직 이해도 향상  
- JDBC를 통한 **SQL–Java 연동** 및 시간 계산 로직 구현 경험  
- 유지보수를 고려한 **기능별 클래스 구조화 및 유틸리티 분리**  
- 협업 중 Git 브랜치 전략을 적용하여 안정적인 팀 개발 경험  

