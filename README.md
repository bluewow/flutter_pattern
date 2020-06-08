# flutter_pattern

## provider 패턴
사용하는 이유
- 관심사의 분리 
	- UI / 데이터 등 클래스의 역활을 나눈다
- 데이터의 공유
	- 하나의 데이터를 여러페이지에서 공유하고 싶을 때
- 간결한 코드
	- bloc 에 비해 좀더 적은 코드로 클래스를 구분해서 사용할 수 있다

구조
- 생산
- 소비 (provider.of(context) or Consumer() => provider 가 더 간단하다)
- Multiprovider -> provider 가 여러개일수록 관리가 어렵다(중첩될 경우 난잡해 진다)


