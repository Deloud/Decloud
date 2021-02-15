# Deloud

클라우드 기반 모듈화된 서비스의 DevOps 개선 방안 연구 (모듈화된 MSA간의 API 규약 자동화 검증 방안 마련)

### Purpose

기업에서 추진중인 클라우드 플랫폼은 개발 생산성, 복잡도 감소, 유연한 배포 등을 위해 서비스간 느슨한 결합, 단일 목적에 중점을 둔 MSA 구조로 개발된다. MSA의 각 서비스는 Contract Test를 기반으로 하지 않고 상호 독립적이고 짧은 주기로 배포되기 때문에 한 서비스의 변경이 전체 서비스에 영향을 줄 수 있는 위험이 있다. 따라서, 배포/운영에서 위험요소의 최소화를 위해서는 MSA의 각 서비스간 API 규약이 잘 지켜졌는지를 CI 단계에서 미리 확인하는 것이 안전하다.

---

### About

클라우드 플랫폼의 DevOps에서 CI 파이프라인 환경에 Contract Test 자동화 기술을 구축/개발하여 서비스 안전성 확보에 대하여 검증하고 이를 통해 클라우드 기반 서비스를 운영할 수 있도록 효율적이고 안정적인 DevOps 구성 방안을 연구하여 Contract Test 기반이 적용된 DevOps 체계 구성도를 개발하고자 한다. 

- Contract Test
<img src="https://user-images.githubusercontent.com/43091713/107845373-4aec3380-6e1e-11eb-968b-cb434e42dc81.png" width="50%">

- 체계도 
<img src="https://user-images.githubusercontent.com/43091713/107845428-9c94be00-6e1e-11eb-83f5-538448fa8578.png" width="50%">

---

### Using Technology 

* Spring Boot & Cloud
* Docker
* Kubernetes
* Jenkins
* Maven - Pact

---

### Member

Spring Boot API | Contract Test | Jenkins K8s 
----- | ----- | ---- |
[김지원](https://github.com/kl529)|[이정인](http://github.com/zungin) & [정은지](https://github.com/JeongEunJi1127)| [김두호](https://github.com/Source-SC) & [권승주](https://github.com/BenKwon)
