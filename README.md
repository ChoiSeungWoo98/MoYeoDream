# MoYeoDream

## Table of Contents

[ 📝 Overview](#📝-overview)  
[ 📁 Project Structure](#📁-project-structure)  
[ 🚀 Getting Started](#🚀-getting-started)  
[ 💡 Motivation](#💡-motivation)  
[ 🎬 Demo](#🎬-demo)  
[ 🌐 Deployment](#🌐-deployment)  
[ 🤝 Contributing](#🤝-contributing)  
[ ❓ Troubleshooting & FAQ](#❓-troubleshooting-&-faq)  
[ 📈 Performance](#📈-performance)  

## 📝 Overview
MoYeoDream은 스터디 및 채용 공고를 관리하고 소통할 수 있는 플랫폼입니다. 사용자는 스터디를 생성하고 참여할 수 있으며, 채용 공고를 등록하고 지원할 수 있습니다.

### Main Purpose
- 사용자가 스터디를 생성하고 관리할 수 있도록 지원합니다.
- 채용 공고를 등록하고 지원하는 기능을 제공합니다.
- 사용자 간의 소통을 위한 댓글 기능을 포함합니다.

### Key Features
- 스터디 생성 및 관리
- 채용 공고 등록 및 지원
- 댓글 기능을 통한 소통
- 사용자 프로필 관리

### Core Technology Stack
- Frontend: HTML, CSS, JavaScript, jQuery, Summernote
- Backend: Spring Boot
- Database: MySQL
- Others: MyBatis, Thymeleaf

## 📁 Project Structure
MoYeoDream
├── 📁 src
│   ├── 📁 main
│   │   ├── 📁 java
│   │   │   ├── 📁 com.project.moyeodream
│   │   │   │   ├── controller
│   │   │   │   ├── domain
│   │   │   │   ├── mapper
│   │   │   │   ├── service
│   │   │   │   └── mybatis
│   │   │   └── ...
│   │   └── 📁 resources
│   │       ├── static
│   │       ├── templates
│   │       └── application.properties
│   └── ...
└── ...

## 🚀 Getting Started

### Prerequisites

- Supported Operating Systems
  * Windows, macOS, Linux
- Required Software
  * Runtime environment: Java
  * Version requirements: Java 11
  * Package managers: Maven
- System Dependencies
  * Oracle JDBC Driver (ojdbc8)

### Installation

```bash
# Clone the repository
git clone https://github.com/ChoiSeungWoo98/MoYeoDream/.git
cd MoYeoDream

# Install required packages
mvn clean install

# Configure environments
# 환경 설정 파일을 수정하여 데이터베이스 연결 및 기타 설정을 완료합니다.
```

### Usage

```bash
# How to run
mvn spring-boot:run
```

## 💡 Motivation
이 프로젝트는 스터디와 채용 공고를 관리하는 플랫폼의 필요성을 느끼고 시작되었습니다. 사용자들이 쉽게 스터디를 찾고 참여할 수 있도록 하며, 채용 공고를 통해 구직자와 기업 간의 연결을 도모하고자 합니다.

## 🎬 Demo
![Demo Video or Screenshot](path/to/demo.mp4)

## 🌐 Deployment
- AWS, Heroku와 같은 클라우드 플랫폼에 배포 가능합니다.
- 배포 단계에서 데이터베이스 연결 및 환경 변수를 설정해야 합니다.

## 🤝 Contributing
- 기여를 원하시는 분은 이슈를 생성하거나 Pull Request를 제출해 주세요.
- 코드 스타일 및 커밋 메시지 규칙을 준수해 주세요.

## ❓ Troubleshooting & FAQ
- 자주 발생하는 문제 및 해결 방법을 여기에 기재합니다.
- 예를 들어, 데이터베이스 연결 오류 시 확인해야 할 사항 등을 안내합니다.

## 📈 Performance
- 성능 최적화 기법 및 벤치마크 결과를 여기에 기재합니다.
- 예를 들어, 데이터베이스 쿼리 최적화 방법 등을 설명합니다.
