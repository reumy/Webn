## this
```
<input type="button" onclick="
  if(this.value === 'night'){...}
  ...
">
```
> 이때 this는 input 태그를 인식
```
<input type="button" onclick="nightDayHandler()">

function nightDayHandler(){
  if(this.value === 'night'){...} 
  ...
}
```
> 이때 this는 전역객체 window를 인식

- 해결
```
<input type="button" onclick="nightDayHandler(this)">

function nightDayHandler(self){
  if(self.value === 'night'){...} 
  ...
}
```
