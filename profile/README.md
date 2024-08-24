## BoWS - 코드스쿼드 멤버들을 위한 쿠버네티스 기반 호스팅 서비스

### ✅ 프로젝트 소개
- 간편하게, 무료로 프로젝트를 온프레미스 k8s 클러스터에 배포할 수 있는 플랫폼 서비스입니다.
- Docker Hub에서의 이미지 이름, Storage Size 등의 정보를 form 형태로 작성하여 제출합니다.
- 제출된 정보를 바탕으로 Helm command가 생성되어 k8s 클러스터에 프로젝트가 배포됩니다.
- 배포된 프로젝트의 상태를 조회할 수 있습니다.
  - 비정상 상태인 경우 그 세부 내용을 조회할 수 있습니다.

<br>

### 🏛️ 서비스 아키텍쳐
<div align=center>
<img src="../service_architecture.png" width="800"/>
</div>
 
<br>

### 🛠️ 기술 스택
#### Backend
<div>
  <img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=OpenJDK&logoColor=white">
  <img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
  <img src="https://img.shields.io/badge/Spring Security-6DB33F?style=for-the-badge&logo=Spring Security&logoColor=white">
  <img src="https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=Hibernate&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white">
 </div>


#### Infra
<div>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5.svg?style=for-the-badge&logo=Kubernetes&logoColor=white">
  <img src="https://img.shields.io/badge/Helm-0F1689.svg?style=for-the-badge&logo=Helm&logoColor=white">
  <img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white"> 
  <img src="https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white">
  <img src="https://img.shields.io/badge/Traefik Proxy-24A1C1.svg?style=for-the-badge&logo=Traefik Proxy&logoColor=white">
</div>


#### Frontend
<div>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white">
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=white">
  <img src="https://img.shields.io/badge/tailwindcss-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white">
</div>

