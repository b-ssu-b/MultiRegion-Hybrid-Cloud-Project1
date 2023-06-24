# MultiRegion-Hybrid-Cloud-Project1
Seoul Region &amp; Singapore Region connection

이 프로젝트는 학원의 공통 주제와 실습 목표에 알맞게 구성되었습니다.

연결의 안정성을 위해, 
Cloudformation으로는 각 리전의 온프레미스, AWS 간의 연결과 도메인 이름을 해결하고, 
TGW Peering, Global Accelerator 연결은 콘솔로 작업하였습니다. 

- 서울과 싱가폴 리전에 아키텍쳐를 각각 구축
- 각 리전에서 온프레미스와 AWS 간의 연결을 구현
- 시나리오: 서울 AWS 리전에 장애 발생 시, Global Accelerator의 기능 중 하나인 장애 조치 기능을 통해 싱가폴 AWS 리전으로 자동 전환되도록 프로젝트를 구성하였습니다

![topology1](https://github.com/b-ssu-b/MultiRegion-Hybrid-Cloud-Project1/assets/130993923/7fbe1ff5-6a6e-4721-922f-a5775a485bb1)
