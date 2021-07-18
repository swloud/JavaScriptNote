자바스크립 학습 노트입니다.

2021-07-18

[Declaring variables]

var: let과 동일한 특성/ 구분을 짓기위해 const/let 존재/should be avoided in MDN code examples unless it is really needed
const: 상수(constant)/ 값이 바뀔 수 없음/ 업데이트 불가/If a variable will not be reassigned
let : 변수(variable)/ 값이 바뀔 수 있음/ 업데이트 가능

always const, sometimes let, neever var

[Naming]

CamelCasing : (ex) veryLongName -JavaScript에서 주로 사용
<->
snake_casing : (ex) very_long_name - python에서 주로 사용

[Boolean]

true/false/null--undefinded

"true"/"false" (X) : this is 'string'
null = nothing/자연적으로 발생 X/비어있다고 의도적으로 설정 : (ex) let something;
                                                                console.log(something); --> undefined 

[Array]

const Array = [1, 2, "hello", false, null, true];
const dayOfWeek= ["mon", "tue", "wed", "thu", "fri", "sat"]

//Get Item from Array
console.log(dayOfWeek[5]) --> "sat"
//Add one more day to the array
dayOfWeek.push("sun")
console.log(dayOfWeek) --> "mon", "tue", "wed", "thu", "fri", "sat", "sun"

[Objects]

const player= { 
  name:"seungwoo",
  points: 10,
  fat: true
};

console.log(play.fat); --> true
player.fat = false;  
console.log(play.fat) --> false
> constant 안의 무언가를 업데이트 가능


                                                                



