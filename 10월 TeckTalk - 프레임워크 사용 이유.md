# 프레임워크 사용 이유

## 프레임워크란?

소프트웨어 프레임워크(software framework)는 복잡한 문제를 해결하거나 서술하는 데에 사용되는 기본 개념으로 간단히 줄여서 프레임워크(framework)라고도 한다.

프로그램을 쉽게 만들기 위한 요소와 룰을 제공해 줌으로써 소프트웨어의 생산성과 품질을 높이는 역할을 한다.



## SSR(Server Side Rendering)

- 페이지를 이동할 때마다 서버에 새로운 페이지에 대한 요청을 하는 방식

서버에서 렌더링을 마치고, Data가 결합된 HTML파일을 내려주는 방식으로 새로운 페이지로 이동할 때마다 서버에 요청하여 페이지를 받아야 하기 때문에, 받아오는 시간동안 깜빡거리는 현상을 마주할 수 있다.



장점: 렌더링 속도가 빠르다

단점: 



## CSR(Client Side Rendering)

- 서버에 최초 요청 시에 HTML을 비롯해 CSS, Javascript 등 각종 리소스를 받아오는 방식


![CSR](https://user-images.githubusercontent.com/43808931/137118268-ba9b7b3e-b0bc-4969-a959-11195f15761b.png)

