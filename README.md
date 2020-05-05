# today-i-learned
what i learned and practice

## Course Information
The tarining course name is "How to prepare a big data and visualize it using Open API".
the course is organized by Samsung Multicampus and sponsored by Korea government,
for 7 months (i.e. 149 days and 1184 hours) in Yeuksamdong Seoul.



## operator

`.` 		멤버연산자

`++` `--` `+` `-` `!` `~` `(타입명)` 		단항연산자

`*` `/` `%` 			산술이항연산자

`+` `-` 				산술이항연산자

`==` `!=` `>` `<` `>=` `<=` `instanceof` 		연산결과가 boolean인 이항연산자

`>>` `>>>` `<<` 		쉬프트연산자

`&` `|` `^` 			비트별&, 비트별or, 비트별xor

`&&` 

`||`

`항1? 항2 : 항3`		조건연산자, 3항연산자

`=` `+=` `-=` `*=` `/=` 	대입연산자




## 변수의 타입

| 자료형  | 저장 가능한 값의 범위                                        | 크기 (bit) | 크기 (byte) |
| ------- | ------------------------------------------------------------ | ---------- | ----------- |
| boolean | false, true                                                  | 8          | 1           |
| char    | '\u0000' ~ '\uffff' (0~ 2의16승-1, 0~65535)                  | 16         | 2           |
| byte    | -128 ~ 127 (-2의7승 ~ 2의7승-1)                              | 8          | 1           |
| short   | -32768 ~ 32767 (-2의15승 ~ 2의15승-1)                        | 16         | 2           |
| int     | -2,147,483,648 ~ 2,147,438,647 (-2의31승 ~ 2의31승-1, 약 +-20억) | 32         | 4           |
| long    | (-2의63승 ~ 2의63승-1)                                       | 64         | 8           |
| float   |                                                              |            |             |
| double  |                                                              |            |             |

출처: Java의 정석 표2-4 기본형의 크기와 범위



## 자동형변환 규칙

이항연산에서 JAVA는 두 항의 타입이 서로 다를 때 하나로 일치시켜 연산된다. 이때 정수에서 실수로, 사이즈 적은 타입에서 큰 타입으로 자동변환된다.

특별히, 산술이항연산 (i.e. `*` , `/` ,  `%` , `+` , `-` )에서는 int 미만은 모두 int로 형변환하여 연산된다.



| operating case  | retult type |
| --------------- | ----------- |
| int `+` int     | int         |
| long `+` long   | long        |
| float `+` float | float       |
| int `+` double  | double      |
| int `+` char    | int         |
| int `+` long    | long        |
| long `+` float  | float       |
| char `+` char   | **int**     |
| byte `+` byte   | **int**     |









## 진법

진법 표기 : 
8진수 0o1342  
16진수 0xFF45  


