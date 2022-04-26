1. 윈도우
node.js 설치
https://nodejs.org/ko
cmd
	node --version
	npm --version
	
mySql
https://dev.mysql.com/downloads/mysql
	windw(x86, 32-bit, MSI Installer)
		full
		execute
		standalone mySql server / classic mySql Replication
		development machine
		TCP/IP 3306
		root pw : root
		
cmd
	mysql -u root -p
	Enter password :
==================================================================
# 기본 문법
# [변수]
var > let > const(고정)

Undefined : 값이 할당되지 않음
NaN : 숫자가 아닌 것을 의미

템플릿 문자열
싱금따옴표(')나 더블따옴표(")가 아닌 백틱(`)감싸주고 변수는 ${} 감싸주면 됨
	let result = `${foo} ${foo2}`;

# [데이터 형 변환]()
JSON.stringify() ---> json,array를 문자열로 바꿀때
JSON.parse() ---> 문자열로된 json과 array를 다시 json과 array로 되돌림

# [비구조화 할당]()
- 비구조 배열
let foo = [1, 2, 3];
let [one, two, three] = foo;
console.log(one, two, three);

let foo = [1, 2, 3];
let [one, ...two] = foo;	// one은 첫 번째 요소, two는 첫 번째 요소를 제외
console.log(one, two);

- 비구조 객체
let foo = {a:1, b:null};
let {a, b, c=10} = foo;
console.log(a);	// 1
console.log(b);	// null
console.log(c);	// 10

# [화살표 함수]()
ES6부터 function(){} ---> ()=>{} 사용할 수 있음
*)화살표 함수는 return 키워드 생략 가능
function(){	// ()=>()형태로 사용 가능
	return
}
형태
const foo = ()=>{
	console.log('foo');
}
const foo = () => ('foo');
const boo = () => {return 'boo'};
==================================================================
# 개요
클라이언트 사이드 렌더링(CSR), 서버 사이드 렌더링(SSR) / 프레임워크
nuxt.js
 - vue.js 기반 서버사이드 렌더링
next.js
 - react.js 서버사이드 렌더링
CDN : Content Delivery Network 콘텐츠의 트랙픽 분산 시키는 역할









