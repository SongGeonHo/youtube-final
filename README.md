

### 유투브 프로젝트 

![스크린샷 2025-02-19 154245](https://github.com/user-attachments/assets/875b6cef-bc3a-4231-bd21-27256d7d8bc0)
![스크린샷 2025-02-19 154309](https://github.com/user-attachments/assets/b3c0f03d-8c3b-40e2-b830-4715076a417e)

**개요**

- **기간**: 총 4주 (2024.12.30 ~ 2025.01.06)
- **팀 구성**: 개인 미니 프로젝트 
- **기술 스택**: HTML,CSS(TailWind),JavaScript,React 
  
**구현 기능**

- 컴포넌트 구성 요소 분리(api,components,context,pages)하여 유지 보수 용이하게 만듬 
- google youtube API Iframe을 활용하여 DetailPage 출력 
- YouTube API 요청 소요를 줄이기 위해 로컬 또는 자체 서버에 가짜 데이터를 저장하여 활용(API 의존성 줄이며 디버깅) 
- 백엔드와의 연결이 정상적으로 이루어지는지 확인하기 위해 실제 API 대신 목(Mock) 데이터를 사용함.

**특이사항**
    
- **문제 해결 및 의사결정 능력**
    
    투두 리스트에서 배운 리액트 훅들을 분리하여 사용함으로서 코드 가독성과 유지보수 용이성 확보 
    
    API 요청 리소스가 한정적인 문제 발생 -> 목 데이터를 통해서 한정적인 상황에서 테스트 완료

    백엔드 기능의 부재로 인해서 연결할 방법 고민하다가 목 데이터를 사용하여 해결 
    
   Iframe API에서 HTTP/HTTPS 버전 사이의 보안으로 인한 API 오류 발생 
   src={`http://www.youtube.com/embed/${video.id}`}  HTTPS로 변경하여 호환성 해결 
    
- **기술 학습 및 사후 관리 역량**
    
   쇼핑몰 프로젝트를 통해서 숙지한 사용법을 다시 공부할 것이며, Firebase의 realtimeDB와 API 연동 예정 
    
   
    

**참고 링크**

- **GitHub**: [https://(링크는 밖으로 노출)]
- **Portfolio**: [https://(링크는 밖으로 노출)]
- **Blog**: [https://(링크는 밖으로 노출)]
</aside>
