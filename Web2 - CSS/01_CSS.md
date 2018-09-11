# CSS
- 해당하는 정보의 이름을 정확히 알아야 스스로 원하는 정보를 

알아낼 수 있음
```
a { color : red };
```
- selector : 선택자 ( a )
- declaration : 선언, 효과 ( color : red )
- property : 속성 ( color )
- value : 값 ( red )

## CSS 코드의 재사용
- 중복을 제거하고 가독성을 높이고 유지보수에 용이함
```
<link rel="stylesheet" href="style.css">
```
- `캐싱 : 저장해 놓는 것`
> 내 컴퓨터에 미리 저장해놓아 네트워크를 쓰지않게 되어 속도가 높아지고 사용량이 적어짐

### 박스모델
- block과 inline은 display 속성의 기본값이며, 변경이 가능함
- display : block, inline, none

#### block(block level element)
- 화면 전체를 씀

#### inline(inline element)
- 자기 자신의 컨텐츠 만큼만 씀

#### 기능이 없는 무색무취의 태그
- div : block
- span : inline

