# 깃 사용하기!

## 깃이란?

프로그램의 버전관리 도구. 
Github는, 여러 제작자가 'HUB'를 이용하여 프로그램의 버전을 온라인으로 관리하는 것이다.

## 깃을 사용하는 이유

1. 버전관리가 용이하다.
  - 깃의 존재 이유이기도 한 이 내용은, 프로그램을 개발하는 동안 여러가지 기능들을 순차적으로 추가하며 버전 업데이트를 수행해 나가는데, 이때 각 버전별 프로그램의 코드 접근이 Git을 사용하지 않을때보다 월등히 좋아진다.
  
2. 각 기능의 테스트가 용이해진다. (Branch/Master)
  - 기능을 추가해 나갈때 기존의 잘 되던 코드를 건드는 것 보다, 임시로 프로젝트를 하나 더 만들어 테스트를 해나가는 것이 코드의 변형을 막는데 훨씬 유용하다. 이 기능을 '나뭇가지(branch)'라고 하며 표현하는데, 여러 개발자는 이런 브랜치를 만들어 임시 프로젝트에 기능들을 추가한 뒤, 테스트가 완료되어 안정화 된 버전을 마스터 (총괄 프로젝트) 에 '병합(Merge)'하여 안정적이게 기능을 추가할 수 있다. 아래의 그림으로 이해하자.
<img src="https://www.google.co.kr/imgres?imgurl=https%3A%2F%2Fwac-cdn.atlassian.com%2Fdam%2Fjcr%3A83323200-3c57-4c29-9b7e-e67e98745427%2FBranch-1.png%3FcdnVersion%3Dkv&imgrefurl=https%3A%2F%2Fwww.atlassian.com%2Fgit%2Ftutorials%2Fusing-branches%2Fgit-merge&docid=q17XjHjtVmZTWM&tbnid=rkFOPDIeQu2RjM%3A&vet=10ahUKEwjP1caCjt3aAhWJmJQKHaWhCpgQMwg3KAAwAA..i&w=800&h=458&bih=947&biw=944&q=git%20branch&ved=0ahUKEwjP1caCjt3aAhWJmJQKHaWhCpgQMwg3KAAwAA&iact=mrc&uact=8"/>

3.
