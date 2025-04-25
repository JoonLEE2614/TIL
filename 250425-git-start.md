## 뭘 배웠는가

- Github remote -v (원격 저장소 목록 명령어) 
- origin (원격 저장소 이름)

- git remote add upstream 조직 리파지토리 주소 (https://github/org/rpas)
- (조직 주소를 끌어 오는 것)

- git fetch upstream main (git fetch upstream main에서의 **upstream**은 일반적으로 원본 저장소를 의미)
- 포크한 저장소 : origin (당신의 GitHub 저장소)
- 원본 저장소 :  upstream (다른 사람의 GitHub 저장소)

- 원본 저장소에서 파일 내려 받기 (git pull upstream main)

- 핵심 포인트
•	누가 충돌을 해결할까?:
o	충돌을 발생시킨 브랜치를 푸시한 사람이 충돌을 해결하는 것이 일반적입니다.
o	팀원 A는 최신화된 파일을 받아도 충돌 파일이 아니다. 팀원 B가 로컬에서 충돌을 해결해야 합니다.
•	팀 협업에서의 best practice:
o	각 팀원은 개별 브랜치에서 작업하고, PR을 통해 main 브랜치로 병합합니다.
o	충돌을 해결하는 사람은 변경 사항을 잘 이해하는 사람이어야 합니다.


## 뭘 배우는가

- 월요일도 Github 협업 연습


## 후기
- 힘들다 
