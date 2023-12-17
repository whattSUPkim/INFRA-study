# INFRA-study
## Week1
> - fastAPI로 root에 접속 시 `Hello, World!` 를 반환하는 초간단 서버를 만듭니다.
> - 초간단 서버를 Dockerfile로 컨테이너화합니다.
> - EC2(t2.micro)를 만들고 도커로 띄웁니다. 외부에서 접속이 되는지 확인합니다.
> - ECS fargate로 서버를 띄웁니다. 외부에서 접속이 되는지 확인합니다.
> - 로드밸런서는 쓰지 않습니다.
> - 구현 및 배포 디테일을 리드미에 정리해주세요. 기타 배운 개념들을 정리하셔도 좋습니다.

#### Submission
- EC2 : [13.208.51.11:7777](http://13.208.51.11:7777/)
- ECS : [15.152.142.41:7777](http://15.152.142.41:7777/)
- [관련 내용 정리](https://habitual-pint-c5d.notion.site/week1-066efcd7cb1e4ef1805d6bfd86cfdc33?pvs=4)


## Week2
[과제 디테일](https://habitual-pint-c5d.notion.site/week2-e7cb9c993a0c4086a5274bf76a83ccb8?pvs=4)
### 1
> s3 file upload 시 slack #hasan-test 채널에 `[파일명]이 S3에 업로드되었습니다!` 라고 메시지가 오도록 하는 Lambda를 구현하세요.
#### Submission
<img width="300" alt="Untitled (13)" src="https://github.com/whattSUPkim/INFRA-study/assets/83912849/cd247719-77c6-4bda-89fc-07f56fc65bb5">


### 2
> Week1에서 만든 EC2에 EFS를 연결하세요. EC2에서 S3, EFS, EBS에 아래 파일을 100번 store, 100번 load하세요. 각 스토리지별로 평균 store 시간, load 시간을 구하세요. 결과를 분석하고 그 이유를 매우 자세하게 설명해주세요.
#### Submission
<img width="600" alt="Untitled (14)" src="https://github.com/whattSUPkim/INFRA-study/assets/83912849/f30fde63-b081-44b5-8d81-dc63cd52a5e1">
