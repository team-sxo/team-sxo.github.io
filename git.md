test


[Study]
- 같은 프로젝트를 수행하면 같은 브랜치를 공유해야 되나? 관계 없나?
- 브랜치를 달리한다면 작업이 완료 된 브랜치와의 병합은?
- upstream을 pull 하고나면 origin의 cloudㅇㅔ도 반영될줄 알았는데 아니네?



 https://blog.banksalad.com/tech/become-an-organization-that-deploys-1000-times-a-day/?gclid=Cj0KCQiA0fr_BRDaARIsAABw4EuvEi-bu7OlR7gIqxHwmLsV1OwdQtZ-ynT3AgXNMZnfm3qTym3hEQQaAl1NEALw_wcB


- branch 전략은 GitHubFlow
- Fork해서 branch 생성하고 작업한 뒤 push
- push한 내용을 pull request
- main에 merge됨과 동시에 deploy
- GitHub Deployments & Action
- 중간에 버전 등의 태그도 달아야 하는데?

ToDo
[GitHub Flow]
config파일을 활용해서 GitHub Flow의 모든 과정을 습득&반복한다
1. Fork -> new branch -> push-> pull request -> code review -> merge -> revert?

[GitHub Actions]
plabfootball을 테스트 서버에 올리고 모든 과정을 습득&반복 하고 세팅한다
- secret
- db연결, migrate
- revert?

- GitHub Deploy & Actions 학습
- GitHub Issues 학습
- GitHub Flow 과정 정리하기

[GitHub x Slack]
- 배포과정 공개
- slack에서 GitHub Issues에 올리기

Q
- DB 싱크와 배포
- DB 세팅하는 작업은? Django에서 migrate 했을 때 되돌릴 수 있나?
- security파일 등을 관리하는 것도 Fork, Mergeㅇㅘ의 관계 -> GitHub Secrets?
- slack과 ㅇㅕㄴ결해서 ㅂㅐ포 등 관레
