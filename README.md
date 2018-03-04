# global.js
`global` 객체가 없는 웹 브라우저 환경에서 무려 *`global` 객체를 생성해주는* 엄청난 JavaScript 라이브러리입니다.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

```html
<script>
	global.bestFood = 'Chicken'; // 오류 발생!
</script>
```

```html
<script src="global.js"></script>
<script>
	global.bestFood = 'Chicken'; // 잘 작동한다! 그런데 배가 고프다...
</script>
```

## 사용 방법
```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title>global.js</title>
		<script src="global.js"></script>
		<script>
			global.bestFood = 'Chicken';
			console.log(bestFood);
		</script>
	</head>
	<body>
		...
	</body>
</html>
```

## 라이센스
[MIT](LICENSE)

## 작성자
[Young Jae Sim](https://github.com/Hanul)
