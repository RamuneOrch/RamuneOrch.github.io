## 사용된 라이브러리

react-router-dom
recoil

## react useState

useState는 리액트의 훅 중 하나로써, 상태를 업데이트 할 때 사용되는 기능이다.
기본적으로 let [변수, 함수] = useState() 상태로 쓰이는데 배열안의 함수가 호출이되면 useState의 인자로 들어간 값이 변수에 저장되면 렌더링이 된다.

## react useEffect

위의 useState와 비슷하게 호출이되면 렌더링이 된다는 점은 똑같지만 useEffect는 화면이 처음 렌더링이 될 때 실행이 된다.
useEffect(함수, 변수) 의 형태로 쓰이는데 함수에 변수의 값이 비어있을때 한번만 호출이 된다.
