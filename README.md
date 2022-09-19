# SearchBlog
카카오API를 사용한 블로그 검색 화면 만들기


## [사용한 기술]

- Kingfisher  URL -> Image
- RxSwift
- RXCocoa
- DisposeBag
- kakao API


Bind
Merge
asSignal - emit


## [Point]  

 **bind()**  

        새로 생성되는 값을 넘겨줄 때 간편하게 사용하는 용도 


attribute()  : VIew의 속성

layout ()    : SanpKit을 사용한 view의 auto layout Setting

PublishRelay : Error Code를 반환하지않고 UI의 Event에 특화되어있다.

- Subject 와 Relay 차이

        ~Subject는 .completed, .error의 이벤트가 발생하면 subscribe가 종료되는 반면,

          ~Relay는 .completed, .error를 발생하지 않고 Dispose되기 전까지 계속 작동하기 때문에 UI Event에서 사용하기 적절합니다.

- Binder 
프로퍼티에 접근하기 위해 확장할 때 사용되는 RxSwift 에서 정의한 타입
[ ] Reactive https://zeddios.tistory.com/1250
