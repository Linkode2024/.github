# LINKODE  
</br></br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/23049ffe-3ffe-4b61-903b-b2fb7d61a740" alt="Project Image" width="600">
</p>

</br>

</br>

---  
</br>

## 👨‍💻 Contributors
<div align="center">

| GitHub Username | 이름          | 역할             |
|-----------------|---------------|------------------|
| [@jsilver01](https://github.com/jsilver01) | **JUNGEUN**  | Backend Developer  |
| [@Mouon](https://github.com/Mouon)        | **Mouon**    | Backend Developer  |
| [@ssilver01](https://github.com/ssilver01) | **JungSoEun**| Frontend Developer |

</div>
</br></br></br></br>
  
---  
</br>

# 💻 Tech. stack
</br>
<p align="center">
  <img width="790" alt="image" src="https://github.com/user-attachments/assets/95d351fc-1bcb-4b6e-a055-004534f0d208">
</p>
</br></br>
  
## Frontend  

### Stack
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=white"><img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white"><img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white"><img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white"><img src="https://img.shields.io/badge/Typescript-3178C6?style=flat-square&logo=Typescript&logoColor=white"/>


### Architecture  
<p align="center">
  <img src="https://github.com/user-attachments/assets/aa9b6f5c-c553-4212-8df4-3c3c5d720d67" alt="Frontend Architecture" width="300">
</p>

</br></br></br></br></br></br></br>

## Backend - API Server

### Stack
<img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"/><img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=Spring&logoColor=white"/><img src="https://img.shields.io/badge/Spring Security-6DB33F?style=for-the-badge&logo=Spring Security&logoColor=white"><img src="https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white"><img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white"><img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=Redis&logoColor=white"><img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/><img src="https://img.shields.io/badge/aws-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/><img src="https://img.shields.io/badge/GitHub Actions-2088FF?style=for-the-badge&logo=GitHub Actions&logoColor=white"><img src="https://img.shields.io/badge/Amazon%20EC2-FF9900?style=for-the-badge&logo=Amazon%20EC2&logoColor=white"><img src="https://img.shields.io/badge/Amazon%20S3-569A31?style=for-the-badge&logo=Amazon%20S3&logoColor=white">

### Architecture  
<p align="center">
  <img src="https://github.com/user-attachments/assets/9464c9fa-fdf4-4951-aaad-8d1a9beb7d28" alt="Backend API Architecture" width="800">
</p>

</br></br></br>

## Backend - Media Server

### Stack
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white"><img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white">

### Architecture
<p align="center">
  <img src="https://github.com/user-attachments/assets/5e5ce7ea-20df-4967-8640-70940d9af38b" alt="Media Server Architecture" width="400">
</p>


  
## 🎯 프로젝트 진행 상황
- **2024.07**  
  LINKODE 프로젝트의 개발이 본격적으로 시작되었습니다. SrpingBoot기반의 서버와 React, Electron기반의 프론트엔드의 스팩으로 개발 중입니다.
  
- **2024.08** 
   실시간 기능을 제외한 구현이 마무리 중에 있습니다. 프론트엔트는 GUI구현을 완료하였고, 백엔드는 비즈니스 로직을 담당하는 API 서버구현을 마쳤습니다.
    
- **2024.09**  
  LINKODE는 기존 모놀리식 설계의 한계를 느껴 실시간 기능과 나머지 비즈니스 로직을 분리하여 **MSA(마이크로서비스 아키텍처)** 로 구축중에 있습니다.
  기존의 비즈니스 로직을 처리하는 **API 서버** (Spring Boot)로 부터 실시간 통신을 담당하는 **미디어 서버** 기능을 분리중에 있습니다.
  실시간 통신을 담당하는 **미디어 서버**는 Node.js 기반으로 구현하였으며, 비동기 처리와 싱글 스레드 환경 덕분에 실시간 기능에 적합하다고 판단했습니다.  


