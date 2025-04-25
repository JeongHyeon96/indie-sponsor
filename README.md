# 🌟 **Indie Sponsor 프로젝트**

**Indie Sponsor**는 5명의 팀이 협업하여 개발한 후원 플랫폼입니다. 이 프로젝트는 **Java**의 **Spring Framework**를 사용하여 개발되었으며, **MVC 패턴**을 기반으로 구현되었습니다. 후원자와 인디 개발자들을 연결해주는 시스템을 목표로 하여, 후원자들이 자신이 원하는 인디 개발자에게 후원할 수 있는 기능을 제공합니다.

## 🚀 **프로젝트 개요**

Indie Sponsor는 **후원자**가 **인디 개발자**에게 후원하고, **인디 개발자**는 후원받은 금액으로 자신의 프로젝트를 더욱 발전시키는 형태의 후원 플랫폼입니다. 사용자는 각자의 역할에 맞춰 로그인 후 후원하거나, 프로젝트를 홍보할 수 있는 기능을 제공합니다.


## ⚙️ **기술 스택**

- **Back-end**: 
  - **Java** (Spring Framework)
  - **Spring Boot**
  - **Spring MVC** (MVC 패턴)
  - **Spring Security** (인증 및 권한 관리)

- **Database**: 
  - **MySQL**

- **Front-end**:
  - **HTML5/CSS3** (반응형 웹 디자인)
  - **JavaScript** (AJAX)

- **Version Control**: 
  - **Git/GitHub**

- **DevOps**:
  - **Docker** (컨테이너화)

## 🚀 **주요 기능**

- **회원가입/로그인**: 후원자와 인디 개발자 역할에 맞는 회원 가입 및 로그인
- **후원 시스템**: 후원자가 인디 개발자에게 후원을 할 수 있는 기능
- **프로젝트 관리**: 인디 개발자가 자신의 프로젝트를 등록하고 후원자에게 홍보
- **후원 내역 관리**: 후원자와 인디 개발자 모두 후원 내역을 확인할 수 있는 기능
- **관리자 페이지**: 관리자용 페이지에서 시스템을 관리할 수 있는 기능 (후원자, 개발자 관리)

## 📂 **프로젝트 구조**

src/
├── main/
│   ├── java/
│   │   ├── com/
│   │   │   ├── indiesponsor/
│   │   │   │   ├── controller/         # 요청을 처리하는 컨트롤러
│   │   │   │   ├── service/            # 비즈니스 로직
│   │   │   │   ├── repository/         # 데이터베이스 연동
│   │   │   │   ├── model/              # 데이터 모델
│   │   │   │   └── config/             # 설정 파일 (Spring Security, DB 설정 등)
│   ├── resources/
│   │   ├── templates/                   # Thymeleaf 템플릿
│   │   ├── static/                      # CSS, JavaScript, 이미지 파일
│   │   └── application.properties      # Spring 설정 파일 (DB 연결, 포트 등)
└── test/
    ├── java/
        ├── com/
            ├── indiesponsor/            # 테스트 케이스




## 💻 **실행 방법**

```bash
# 프로젝트 클론
git clone https://github.com/JeongHyeon96/indie-sponsor.git

# 의존성 설치
mvn clean install

# 애플리케이션 실행
mvn spring-boot:run

🔗 연관 링크
GitHub 레포지토리: Indie Sponsor GitHub 레포지토리

📈 학습 목표 및 성과
Spring Framework를 사용한 MVC 패턴 이해 및 실습

Spring Security를 통한 인증 및 권한 관리 구현

MySQL 데이터베이스를 사용한 데이터 모델 설계 및 CRUD 연습

팀 협업을 통한 프로젝트 진행 및 GitHub를 이용한 버전 관리 실습

📝 개선할 점
결제 시스템 연동: 현재 후원은 모의 데이터로 진행되므로 실제 결제 시스템을 연동할 예정

반응형 디자인 개선: 다양한 기기에서의 접근을 위한 UI 개선

알림 시스템 추가: 후원자와 인디 개발자에게 이메일 알림 기능 추가
