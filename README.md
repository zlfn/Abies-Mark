# 🌲Abies-Mark
**어비스 마크** : Abies는 전나무의 학명입니다.

## 개요
어비스마크는 나무위키와 오픈나무에서 사용하는 **나무마크**와 호환되면서, 블로그나 게시글 작성에 특화되도록 만든 마크업 언어입니다.  
본 레포지토리에는 어비스마크의 명세와 Rust로 작성된 어비스 마크 -> HTML 변환 코드와 에디터가 작성될 예정입니다.  
어비스마크는 아래의 지향점을 가지고 개발됩니다. 
1. **나무마크와 호환**될 것. 그러나 **완벽할 필요는 없다.**  
  어비스마크는 나무마크와의 호환성을 지향하나 HTML-마크다운과 달리 나무마크의 슈퍼셋으로써 개발되지는 않습니다.  
  나무위키 등지에서 **주로 사용하는 문법** 위주로 호환되며, 사용이 드문 고급 문법들은 수동으로 변환하여야 합니다.  
  어비스마크는 나무마크의 대체제가 아닌, 나무마크가 위키 외의 다른 곳에서 쓰일 수 있도록 개조한 문법임에 유의합니다.  
2. **사용이 편할 것,** 때로는 **배우기 어렵더라도...**  
  나무마크는 마크다운보다 훨씬 기능이 많고, 그만큼 깊이 들어가면 갈수록 문법이 복잡해집니다. 나무위키의 표를 보면... 사람의 눈으로는 도저히 알아볼 수 없어요. 숙달된 위키니트들은 나무마크로 작성된 표를 뇌장 렌더링 엔진으로 렌더링 가능하겠지만, 블로그같은 일상적인 작업에서 편의성이 떨어지는건 사실입니다. 따라서 이를 해결 하기위한 특수 중괄호 문법 등을 제공합니다. 물론 쓰기는 편해도 배우기는 어려워집니다. 과감히 희생합시다.
  
완성할 수 있을 진 모르겠지만 시작해보죠.

## 문법
* [기본 문법](Basic.md)
* [중괄호 문법](Brace.md)

