코딩 및 개발 공부를 하면서 프레임워크와 라이브러리의 명확한 차이도 모른 채, 그리고 내가 쓰는 것이 프레임워크인지 라이브러리인지도 모르고 있어서 이번 기회에 정확하게 알아보려고 글을 쓰게 되었다.

## ◎ 프레임워크

- **개발자가 구현해야 하는 애플리케이션의 전체 구조와 흐름을 미리 정의한 것**
- **뼈대나 기반 구조** → 즉, 개발자를 도와주는 기반이 되는 역할을 함
- **제어의 역전(IoC : Inversion of Control)** 개념이 적용된 대표적인 기술
    - 프레임워크에게 제어의 흐름을 넘겨 개발자가 작성하는 코드에서 신경 써야 할 부분을 줄인다
- 개발자는 프레임워크에서 제공하는 구조와 규칙을 따라야 하며, 특정한 문제를 해결하기 위한 코드를 작성함
- 개발자는 프레임워크에 따라 개발을 하며, **프레임워크가 개발을 주도**
- 소프트웨어의 특정 문제를 해결하기 위해서 상호 협력하는 클래스와 인터페이스의 집합
- 대표적인 예시로는 Django, Ruby on Rails 등이 있습니다.

<img src="https://velog.velcdn.com/images/dellojoon7/post/57fa41ec-add3-4662-9c2c-22e54d1e5322/image.png" width="30%" height="30">
                                                             <img src="https://velog.velcdn.com/images/dellojoon7/post/87795dee-c08a-418b-9021-6623b06428a0/image.png" width="30%" height="30">                                                     

### ■ 프레임워크 사용 이유

- 프로그램 유지 보수에 용이 → 기본 틀이 있기 때문에 체계적인 코드 관리가 됨
- 기본 설계 및 기능 라이브러리를 제공함 → 개발 생산성이 높아짐
- 코드에 대한 재사용성이 높다

### ■ 프레임워크의 단점

- 학습 난이도가 높다
- 기본 설계된 구조에 의해 자유로운 개발에 한계가 있다
- 제공되는 기능만큼 프로젝트 용량이 증가한다
- 사용되지 않는 기능에 대한 라이브러리가 포함될 수 있다.

---

## ◎ 라이브러리

- **특정한 기능을 수행하는 도구, 함수, 클래스, 메소드 등으로 구성된 집합체**
- 개발자는 필요한 라이브러리를 호출하여 사용할 수 있음
- 즉, 개발자는 자신의 코드에서 라이브러리를 사용
- 라이브러리는 개발자가 직접 제어할 수 있으며, 필요한 부분만 사용할 수 있다.
- 대표적인 예시로는 React, NumPy, TensorFlow, Pandas 등이 있습니다.

<img src="data:image/png;base64,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" width="30%" height="30">

<img src="https://cdn.inflearn.com/wp-content/uploads/react.png" width="30%" height="30">

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/ab/TensorFlow_logo.svg/1200px-TensorFlow_logo.svg.png" width="30%" height="30">

---

## ◎ 프레임워크와 라이브러리의 공통점

- 코드 재사용을 촉진하며 개발자가 시간을 절약하도록 도와주는 도구
- 프로그램을 쉽게 만들 수 있게 함

## ◎ 프레임워크와 라이브러리의 차이점

- 프레임워크와 라이브러리의 대표적인 차이점은 **흐름을 누가 지니고 있느냐**의 차이 (자유도)
    - 프레임워크는 전체적인 흐름을 자체적으로 갖고 있어서 프로그래머가 그 안에서 필요한 코드를 작성함
    - 라이브러리는 프로그래머가 전체적인 흐름을 갖고 있어서 라이브러리를 자신이 원하는 기능을 구현하고 싶을 때 가져가 사용함
- 프레임워크는 꼭 써야 하는 것과 지켜야 되는 룰이 있음, 반면에 라이브러리는 쓰든 안쓰든 자기 마음
- 프레임워크는 애플리케이션의 전체적인 구조를 제공하며, 라이브러리는 개발자가 필요한 기능을 호출하여 사용할 수 있습니다.

<img src="https://velog.velcdn.com/images/yong2/post/4dcb3c9a-64f5-4a11-a035-af254ab51edf/image.png" width="70%" height="30">

### ◎ 비교 표

|                          | 프레임워크 (Framework)                                       | 라이브러리 (Library)                                         |
| ------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 정의                     | 뼈대나 기반 구조, 짜여져 있는 틀                             | 단순 활용 가능한 도구들의 집합체                             |
| 상세 정의                | 소프트웨어의 특정 문제를 해결하기 위해서 상호 협력하는 클래스와 인터페이스의 집합 | 소프트웨어 개발을 위해 다른 프로그램에서 사용할 수 있는 함수, 클래스, 루틴 등의 모듈을 포함하는 컴퓨터 프로그램 및 코드의 모음 |
| 주도성이 누구에게 있느냐 | 전체적인 흐름을 프레임워크가 쥐고 있음 → 사용자가 그 안에서 필요한 코드를 짜는 구조 | 사용자가 전체적인 흐름을 만들며 라이브러리를 가져다 씀       |
| 자유도                   | 꼭 필수적인 것이 있음, 규칙 준수 필요                        | 굳이 사용 안하면 그만, 단독 사용 가능, 다른 소프트웨어에 쉽게 통합됨 |

---

## ◎ 프레임워크의 종류 및 예시

- **Django** : 웹 개발을 위한 프레임워크
    - 웹 애플리케이션의 구조와 규칙을 정의하고, 개발자는 그 구조와 규칙에 따라 개발을 진행함
    - Django는 웹 프로젝트의 기본적인 요소를 제공하며, 데이터베이스 관리, URL 라우팅, 세션 관리, 폼 처리 등 다양한 기능을 내장하고 있음
- **Vue.js** : 프론트엔드 웹 개발을 위한 프레임워크
    - 웹 애플리케이션의 전반적인 구조와 데이터 흐름을 정의하고, 개발자가 이에 따라 UI 컴포넌트를 작성하도록 도와줌
    - 반응형 UI를 구현하기 위한 데이터 바인딩, 컴포넌트 기반 아키텍처, 라우팅, 상태 관리 등 다양한 기능을 제공
- **Spring** : Java 기반의 웹 프레임워크
    - DI, AOP, JDBC, MVC 등 다양한 기능을 제공
- **Spring Boot** : Spring과 비슷한 기술 스택을 가진 프레임 워크
    - 애플리케이션의 기본 구조와 설정 파일들을 미리 정의하고 있어, 개발자가 애플리케이션을 빠르게 구축 가능
    - 내장형 서버를 사용하여 개발자가 애플리케이션을 쉽게 실행하고 배포할 수 있도록 함
    - 내장형 톰캣이 있어 별도의 톰캣을 설정할 필요가 없음
    - AutoConfigurator
- **ruby on rails** : Ruby 기반의 웹 프레임워크
    - MVC 아키텍처, 데이터베이스 관리, 라우팅, 세션 관리 등 다양한 기능을 제공
- **Next.js** : React를 기반으로 한 프레임워크
    - 서버사이드 렌더링(SSR), 정적 사이트 생성(Static Site Generation), 클라이언트 사이드 라우팅 등 다양한 기능을 제공
    - React를 사용하는 웹 개발자들이 보다 쉽게 웹 애플리케이션을 구현할 수 있도록 돕는다.
    - Next.js는 애플리케이션의 구조와 규칙을 미리 정의하여 개발자가 이를 따르도록 유도하므로, 프레임워크의 특징을 가지고 있음
- **Nuxt.js** : Vue.js 프레임워크 기반의 프로젝트 구성 도구 → 엄밀히 말하면 라이브러리나 프레임워크 둘 다에 해당하지 않음, 하지만 프레임워크에 가까운 개념
- **Angular** : 프론트엔드 웹 개발을 위한 프레임워크
    - 웹 애플리케이션의 전체적인 구조와 규칙을 정의하며, 개발자가 이에 따라 컴포넌트를 작성하도록 유도함
    - Angular는 자바스크립트 라이브러리를 포함하고 있지만, 프레임워크에서 제공하는 다양한 기능들(의존성 주입, 컴포넌트 기반 아키텍처, 템플릿, 라우팅 등)을 이용하여 전체적인 웹 애플리케이션의 구조를 정의하므로, 프레임워크에 더 가까운 개념
- **Express.js** : node.js에서 가장 많이 사용되는 웹 프레임워크
    - 웹 애플리케이션과 API를 구축하기 위한 기능을 제공
- **Flutter** : 모바일 애플리케이션 개발을 위한 프레임워크, Dart 언어 사용
    - 구글에서 개발한 UI 프레임워크로, iOS와 Android 플랫폼 모두에서 네이티브 앱과 유사한 성능과 외형을 제공
    - 위젯(widget)을 기반으로한 컴포넌트 아키텍처, 애니메이션, 머티리얼 디자인, 다국어 지원, 상태 관리 등 다양한 기능을 제공
- **React Native** : 모바일 애플리케이션 개발을 위한 프레임워크
    - React Native는 Facebook에서 개발한 프레임워크
    - iOS와 Android 플랫폼에서 네이티브 앱과 유사한 성능과 외형을 제공
    - React와 비슷한 구조와 개발 방법을 사용하며, JavaScript를 이용하여 모바일 앱을 구현 가능
- **Ionic** : HTML, CSS, JavaScript를 기반으로 하는 모바일 애플리케이션 개발 프레임워크
    - Angular를 기반으로 하며, iOS와 Android 애플리케이션 개발을 위한 다양한 기능을 제공
- **Xamarin** : C# 언어를 기반으로 하는 모바일 애플리케이션 개발 프레임워크
- **Flask** : 파이썬으로 작성된 경량 웹 프레임워크
    - Flask는 마이크로(micro) 웹 프레임워크로 분류되며, 웹 애플리케이션 개발을 위한 핵심 기능만 제공
    - 모듈화된 구조로 이루어져 있어, 다른 라이브러리와 연동하여 사용하기 쉽다
- **Laravel** : PHP 언어를 기반으로 하는 웹 프레임워크
- **ASP.NET** : C# 언어를 기반으로 하는 웹 프레임워크
- **Pytorch** : 파이썬 기반의 딥 러닝 프레임워크로, Facebook에서 개발

---

## ◎ 라이브러리의 종류 및 예시

- **React** : UI 컴포넌트 라이브러리, Facebook에서 개발한 자바스크립트 라이브러리
    - 사용자 인터페이스를 작성하는 데 필요한 도구와 기능을 제공
    - React는 가상 DOM(Virtual DOM)과 성능 최적화, 컴포넌트 기반 아키텍쳐, 이벤트 처리, 데이터 상태 관리 등 다양한 기능을 제공하며, 이를 사용하여 개발자가 자신만의 웹 애플리케이션을 구현할 수 있도록 돕습니다.
    - React 자체는 애플리케이션의 구조나 규칙을 강제하지 않으므로, 프레임워크와는 차이가 있다.
    - 초기에는 자바스크립트 라이브러리로 소개 되었지만, 이후 발전과 함께 프론트엔드 프레임워크로 인식되고 있음, 하지만 엄밀한 정의로는 프레임워크보다 라이브러리에 가까움
- **jQuery** : 자바스크립트 라이브러리
    - HTML 문서 탐색과 조작, 이벤트 처리, 애니메이션 등 다양한 기능을 제공
    - 자바스크립트 라이브러리 중 가장 유명
    - jQuery는 웹 애플리케이션의 전체적인 구조나 규칙을 정의하지 않으므로, 프레임워크와는 차이가 있음
- **MUI** : 프론트엔드 웹 개발을 위한 UI 라이브러리
    - Material Design 기반으로 디자인된 다양한 UI 컴포넌트를 제공
    - React, Angular, Vue 등 다양한 프레임워크와 함께 사용할 수 있으며, 각 프레임워크에 맞게 컴포넌트를 작성하고 있음
- **Bootstrap** : HTML, CSS, JavaScript를 이용한 프론트엔드 라이브러리
    - 반응형 웹 디자인을 쉽게 구현 가능
- **Redux** : React와 함께 사용되는 상태 관리 라이브러리
    - 애플리케이션의 전체 상태를 관리하고 업데이트하는 기능을 제공
- **Vuex** : Vue.js와 함께 사용되는 상태 관리 라이브러리
    - 애플리케이션의 전체 상태를 관리하고 업데이트하는 기능을 제공
- **NumPy** : 파이썬에서 과학, 수학 및 공학 계산을 위한 핵심 라이브러리 중 하나
    - 대규모 다차원 배열과 행렬 연산에 대한 기능을 제공하며, 이를 이용하여 벡터 및 행렬 연산 등 다양한 수치 계산을 수행
    - 과학 및 공학 계산에서 가장 많이 사용되는 파이썬 패키지 중 하나이며, 파이썬을 이용한 데이터 분석 및 머신 러닝 분야에서도 널리 사용
- **Pandas** : 파이썬에서 데이터 분석을 위한 라이브러리
    - 데이터를 다루기 쉽도록 고안된 라이브러리로, 데이터를 불러오고 조작하는 기능을 제공
- node.js에서 npm으로 설치한 모듈들

- **TensorFlow** : 구글에서 개발한 오픈소스 머신러닝 프레임워크 → 딥러닝 및 머신 러닝을 위한 라이브러리와 프레임워크로 구분 (둘다 해당됨, 중간쯤 위치)
    - TensorFlow는 딥 러닝 및 머신러닝 작업을 위한 라이브러리로 사용할 수 있으며, NumPy와 유사한 API를 제공하여 다양한 수치 계산 작업을 수행할 수 있음
    - TensorFlow는 딥 러닝 모델의 구성, 학습 및 배포를 위한 프레임워크로 사용할 수 있습니다. TensorFlow는 다양한 도구들을 제공하여 모델의 구성 및 학습, 모델의 배포 및 서빙 등을 쉽게 처리할 수 있음

---

## ◎ 런타임

- 프로그래밍 언어가 실행될 때 필요한 실행 환경을 제공하는 것
- 프레임워크와 라이브러리는 런타임에서 사용되는 개발 도구
- 자바스크립트 런타임은 브라우저나 node.js와 같이, 자바스크립트 코드를 실행하기 위한 실행 환경을 제공
- **자바스크립트 런타임**: 브라우저에서 동작하는 JavaScript, 서버 사이드에서 동작하는 node.js 등이 있습니다.
- **자바 런타임**: 자바 언어를 위한 런타임으로, JVM(Java Virtual Machine) 위에서 동작합니다.
- **파이썬 런타임**: 파이썬 언어를 위한 런타임으로, CPython, Jython, IronPython 등 다양한 종류가 있습니다.
- **루비 런타임**: 루비 언어를 위한 런타임으로, Ruby MRI, JRuby, Rubinius 등 다양한 종류가 있습니다.
- **고(Go) 런타임**: Go 언어를 위한 런타임으로, Go 컴파일러와 함께 Go 프로그램을 실행할 수 있습니다.