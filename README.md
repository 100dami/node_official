### Arrow Function (화살표 함수)
> 화살표 함수 표현(arrow function expression)은 function 표현에 비해 구문이 짧고  자신의 this, arguments, super 또는 new.target을 바인딩 하지 않습니다. 화살표 함수는 항상 익명입니다. 이  함수 표현은 메소드 함수가 아닌 곳에 가장 적당합니다. 그래서 생성자로서 사용할 수 없습니다.
```js
// ES6 문법 전 함수
const func2 = function(num) { 
  for(let i = 0; i < 10; i++) { num++; }
  return num;
};
// ES6 문법 후 함수
const func2 = (num) => {					// 함수의 매개변수에 괄호 생략 가능
  for(let i = 0; i < 10; i++) { num++; }
  return num;
};
```

### Assert
> 코드를 작성할 때 우리가 기대한 방향으로 동작하도록 자동으로 검사하는 테스트들을 작성하는 것
