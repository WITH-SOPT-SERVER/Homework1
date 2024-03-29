# Homework1
1차 과제 가이드라인

## 과제 개요
1차 세미나에서 배운 내용을 바탕으로 라우팅 구현을 구현하는 실습을 진행한다.

## 과제 목표
localhost:3000/api/cafe
localhost:3000/api/blog
localhost:3000/api/news
localhost:3000/api/news/like
위 라우팅을 구현 하는 것이 두번째 과제입니다.

Browser에서 각각의 URL에 접속했을 때 각각의 페이지가 나타나면 성공입니다.

## 힌트
라우팅을 위해서 폴더를 구성하는 방법에는 여러가지가 있습니다.

※ 파일만 생성하였으며 코드는 추가하지 않았습니다.

1. [routers-sample-1](./routes-sample-1)
2. [routers-sample-2](./routes-sample-2)
3. [routers-sample-3](./routes-sample-3) (like 기능을 news.js 에서 구현)
4. [routers-sample-4](./routes-sample-4)
5. [routers-sample-5](./routes-sample-5)

1번에 가까울 수록 세분화를 적용한 모습을 보여줍니다. 또한 위 방법외에도 다양한 방법으로 구현할 수 있습니다.
어떤 것이 항상 좋다는 정답은 없습니다.
각각의 방법에 어떠한 장단점이 있을지 고민하고 이야기하면 좋을 것 같습니다.

※ 1 ~ 5번은 과제하기 막막하신 경우 참고하시라도 가이드로 만든 파일입니다! 본인만의 방법으로 만드셔도 되며 1 ~ 5번 중에서 하나를 골라서 만드셔도 됩니다!

> 예를 들면 
> 1. 확장성: 새로운 기능을 유연하게 추가할 수 있는지 
> 2. 가독성: 찾고자 하는 코드를 빠르게 찾을 수 있는지
>
> 위 기준으로 바라본다면
4,5번의 경우 하나의 폴더 밑에 수많은 파일이 생기기 때문에 가동성에서 떨어질 수 있습니다.
또한 확장성에 측면에서 현재 like는 news에 관한 코드이지만 blog에도 like가 생긴다면 기존에 있던 파일을 likeNews, likeBlog등으로 나눠야 한는 문제가 생길 수 있습니다. 이러한 측면에서 단점이 있다는 것을 생각해 볼 수 있습니다.
