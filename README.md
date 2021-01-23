# SpringWebFlux-V3

## WebFlux와 R2DBC와 Processor(Emiiter)결합해보기

참고 : https://projectreactor.io/docs/core/release/reference/

- repository를 이용해서 transaction을 발동시킬 때는 꼭 response응답을 위해 return을 해줘야 한다.
- return 하지 않으면 트랜잭션 발동이 안됨.
- sse 연결이 종료될 때 onCancel 콜백 메서드를 이용해서 꼭 blockLast() 라고 스트림이 끝났다고 알려줘야 함

![img](https://github.com/codingspecialist/SpringWebFlux-V3/blob/master/preview/1.jpg)

![img](https://github.com/codingspecialist/SpringWebFlux-V3/blob/master/preview/2.jpg)

![img](https://github.com/codingspecialist/SpringWebFlux-V3/blob/master/preview/3.jpg)

![img](https://github.com/codingspecialist/SpringWebFlux-V3/blob/master/preview/4.jpg)

![img](https://github.com/codingspecialist/SpringWebFlux-V3/blob/master/preview/5.jpg)
add1
