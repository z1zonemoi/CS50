# CS50

1. 2022.08.01 책에 있는 내용이 글로 읽기에는 벅차서 페어분이 소개해주신 강의를 들으면서 읽어가면 더 좋을 것 같아서 듣게 되었다.

2. 2022.08.03 오늘 들은 강의는 전에 책에서 봤던 ASCII코드와 유니코드에 대한 강의였고, 컴퓨터의 0과 1로 문자 표현 부터 ios의 기쁨의 눈물 이모지와 색상, 동영상을 표현하는 방식에 대한 설명이었다. RGB로 표현하는게 숫자로 이뤄진다는 점과 동영상이 사진의 모음인데 이것을 표현하기 위해 얼마나 많은 0과1이 필요한지 또 평상시 그냥 사용했던 이모지를 숫자로 나타내는 방식을 알고나니 기술이 엄청 발전한거구나 새삼 깨달았다.

3. 2022.08.05 오늘 강의 주제는 algorithm이었다. 알고리즘은 단순히 문제를 풀기위한 규칙들의 순서적 나열이며, 정확성과 효율성 두 가지 측면을 고려해서 작성해야한다. 이때 Pseudo Code를 작성하면 컴퓨터가 수행해야하는 일을 절차적으로 파악할 수 있게 도와준다. 강의 중에 책을 찢으셨는데 매우 인상적이었다.ㅋㅋ

4. 2022.08.07 오늘은 스크래치 기본편을 들었다. 스크래치는 스크래치블록을 통해 입력이 블록을 거쳐 출력되는 모습을 구현한 웹사이트이다. 알고리즘을 직접 짜보면서 눈으로 확인하는데 재밌었다.

5. 2022.08.08 오늘은 스크래치 심화편을 들었다. 이번에는 애니매이션의 효과를 내는 원리와, 조건문, 변수에 대한 내용이었고 마지막에 게임을 지원자를 받아서 진행하는걸 봤는데 재밌었다ㅋㅋㅋ 나도 케이크,,,

6. 2022.08.09 오늘 강의는 c언어 기초에 대해서 알려주셨다. 우리가 흔히 말하는 c언어, 자바,...의 언어들은 소스코드이고, 이를 컴퓨터가 이해할 수 있는 머신코드(0과1)로 바꿔야 하는데 이것을 해주는 프로그램이 컴파일러이고, 그 중 clang에 대해 알려주셨다. 그리고 샌드박스를 사용해 c언어 간단실습을 했다. #include <stdio.h> int main(void){printf("Hello world\n");} 라는 간단한 코드였고 옛날에 교양으로 배웠던 내용도 간간히 생각났다. stdio.h는 printf함수에 접근할 수 있도록 하는 것인데 저거 studio로 많이 쳐서ㅋㅋㅋㅋㅋ주의해야 했던 기억이랑 ; 적어주는거!!ㅋㅋㅋ

7. 2022.08.10 오늘은 문자열에 대해서 알아봤다. c언어에서는 변수를 선언할때 변수에 들어가는 값이 어떤 타입인지를 적어야한다. 샌드박스를 통해 실습했는데 터미널에서 make string 명령어를 사용하여 주어진 파일 안의 string 문자열 형식과 함수에 대해 코드를 컴파일 하고 실행하는걸 좀 더 간편히 할 수 있었다. 그리고 문자열을 받기 위해서 %s를 붙여 인자를 받아준다 이 때 s는 string의 s이다. 이렇게 사용하는 이유는 어떤 종류의 인자를 받는지 알려주기 위해서이다. c언어는 오래된 저수준의 언어라 내가 지금 배우고 있는 js와는 다르게 타입을 꼭 써주는등 규칙같은게 엄격한 느낌이 들었다. 그에 비하면 js는 굉장히 유연해보인다.

8. 2022.08.11 오늘 강의는 조건문과 루프!! 이 부분은 js와 크게 다른 건 없다. 가장 크게 다른 건 정수를 다루는 변수를 선언할 때 int 를 붙여 나타낸다는 점?? 그것말고는 while이나 for문으로 루프를 만드는 것과 무한루프를 만들지 않도록 조건을 잘 붙여줘야한다는 것을 알게됐다. 오늘은 굉장히 익숙한 내용이어서 무난했던 것 같다.

9. 2022.08.12 오늘 강의는 자료형,형식지정자,연산자에 대한 강의였다. %.2f를 사용하면 소수점 2번째 자리까지만 나타낼 수 있다. float가 필요한 이유는 소수점 표현이고, int가 있는데 long이라는 정수 데이터를 나타내는 데이터 타입을 쓰는 이유는 int는 40억까지 셀 수 있는 자료형이라 좀 더 큰 정수를 표현하기 위해서 long을 사용한다. char은 문자 하나를 표현하는 데이터 타입 연산자와 주석처리는 js와 거의 동일한 것 같다. 강의 중간에 python같은 경우는 ||을 or로 써도 된다고 하셔서 신기하다고 생각됐다.

10. 2022.08.13 오늘은 중첩루프와 사용자 정의 함수에 관련된 내용이었다. c 언어는 좌에서 우로 위에서 아래로 읽기 때문에 함수를 만들고 그 함수를 호출을 해야한다면 함수가 호출되기 전에 먼저 선언되어야한다. 하지만 프로토타입이라고 함수의 이름과 매개변수만 적은 코드를 윗쪽에 올려두고 세미콜론을 찍으면 눈속임?ㅋㅋ을 할 수 있어서 추상화를 하기 용이해진다. 중첩루프는 쉽게 말해 행과 열을 떠올리면 된다. 사용자 정의 함수는 사용자가 입력을 한 변수에 의해 출력 값이 함수 안의 식을 거쳐 나오는 것인데 이러한 사용자 정의 함수를 사용하면 장점이 코드의 재사용과, 유지보수에 유리함 즉 효율성이 좋아진다.

11. 2022.08.14 오늘은 메모리에 대한 수업이었다. 컴퓨터는 RAM이라는 물리적 저장장치를 포함하고, 우리가 작성한 프로그램은 구동 중 RAM에 저장되는데 이 때 RAM은 유한한 크기의 비트만 저장할 수 있기 때문에 그 유한한 비트를 넘어가면 오버플로우가 발생하게 된다. 이러한 문제는 실생활 속에서는 Y2K문제와 보잉 787에서 발생되었고, 이 문제를 해결하기 위해 많은 비용을 지불하게 됐다. 지금과 달리 옛날에는 메모리가 아주 값비싸서 설계 시 더 효율적이고 문제가 생기지 않는 방법을 위해 고군분투 했을 것 같다. 이와 관련된 문제를 어떻게 하면 좋을지 고민해보자라는 주제가 있었고, 메모리 사용에 대해 효율적으로 코드를 설계한다라고 생각했고, 다른 사람들의 의견 중에 오버플로우가 되기 전에 자동 초기화를 한다는 글도 봤는데 좋은 방법인 것 같아서 기록한다.

12. 2022.08.15 오늘은 컴파일이 주제였다. 컴파일링의 네가지 단계는 전처리,컴파일링,어셈블링,링킹이 있고, '전처리'에서는 #으로 시작되는 C소스 코드는 전처리기에 실질적 컴파일이 이뤄지기 전에 다른 파일의 내용을 포함시키라는 등을 알려준다. '컴파일'은 전처리한 소스 코드 생성 후 어셈블리라는 c언어보다 저수준의 언어로 변환시킨다 '어셈블'은은 어셈블리 코드를 오브젝트 코드로 변환 0과1로 바꿔주는 작업을 한다. 컴파일 되어야 할 파일이 여러개라면 다음 단계인 '링크'로 넘어가 여러개의 오브젝트 코드 파일을 실행가능한 하나의 오브젝트 코드 파일로 합쳐주고 이 단계들을 거치면 최종적으로 실행 가능한 파일이 완성된다!! 컴파일을 하는데 어셈블리 코드라는 과정을 한 번 더 거친다는 것이 신기했다 그동안 입력 컴파일 출력으로 생각하고 있어서 바로 0과1로 바꿀줄 알았는데 새롭게 알게된 내용이었다.

13. 2022.08.16 오늘 내용은 디버깅이었다. 버그는 코드에 들어있는 오류다. 디버깅(debugging)이라는 작업으로 버그를 식별하고 고친다. 프로그램은 일반적으로 빠른 속도로 연산을 수행하기 때문에 눈으로 실행과정을 직접 알아보고 싶다면 중지점을 사용하여 디버깅을 하면 된다. 콘솔에서도 이렇게 디버거를 넣고 하나씩 단계를 확인하면서 알고리즘을 풀었던 기억이 났다ㅋㅋㅋ 반복문등에서 매우 유용했다. 다른 방법으로는 이 강의에서 help50과 printf로 문제를 찾아가는 방법이 있었다. js로 비유하면 printf는 console.log()와 비슷한 것 같다.

14. 2022.08.17 오늘은 코드 정리에 대한 강의였다. 실습을 cs50 샌드박스로 하기 때문에 여기서 알려준 방법은 1. check50으로 코드가 잘 작동하는지 2. style50으로 코드가 심미적으로 괜찮은 코드인지 3. 고무오리에게 코드가 왜 잘 안짜지는지 약간 생각의자 + 걱정인형ㅋㅋ 이렇게 소개 시켜줬다. 그리고 강의 속 수강생들에게는 오리를 가져가도 좋다고 했다. 나도 오리 가져가고 싶다ㅋㅋㅋ 현실에 적용하려면 1. console.log나 debugger를 사용하여 코드가 잘 작동하는지 확인하거나 test를 위해 모카를 사용하는 등으로 적용하면 될 것 같고 2. 클린코드를 의미하는 듯 하다 리팩토링을 거쳐 클린코드를 만들도록 노력하거나 심미적인 부분에서 vscode에서는 prettier확장팩이나 정렬을 위한 단축키를 사용하면 도움이 될 것 같다. 3. 고무오리는 사실 이 강의를 듣기 전부터 강아지 인형이 있었다. 아직 그 인형을 보면서 고민해본적은 없지만 나중에 코드 짜면서 고민이 생기거나 생각할 일이 많으면 한 번 시도해보는걸로...

15. 2022.08.18 오늘은 메모리와 배열에 대한 학습을 했다. 각 데이터 타입마다 정해진 용량(예를 들면 char은 1바이트)이 있고, 컴퓨터 안에 RAM이라는 물리적 칩이 메모리의 역할을 하여 저장을 한다. 배열은 들어올 값의 갯수를 예측하기 어려울 때 혹은 여러 값들을 관리하기에 유용하게 사용할 수 있다. 오늘은 배열에 들어올 값을 정해두고 한정된 여러개의 값들을 정리하는 걸 배웠다. c언어에서 배열은 arr[n] n 부분에 들어올 값의 갯수를 적어주고 arr[0],...,arr[n-1]까지 적을 수 있고, 할당 시 arr[0] = 1 이렇게 적어주면 된다.

16. 2022.08.19 오늘은 배열과 루프, 전역 변수를 사용하여 좀 더 동적인 코드로 변환하는 강의를 들었다. c언어에서 숫자의 계산은 int/int=int가 나오므로 소수점을 고려한다면 float/float로 해주고 원하는 소수점 자리수 만큼 .nf를 해주면 된다. 루프 안에 사용자로부터 값을 입력 받는 함수를 작성한다면 값의 갯수에 상관 없이 값을 입력 받을 수 있다.

17. 2022.08.20 문자열의 배열에 대해서 학습하였다. 강의에서 문자열은 메모리에 문자 자료형 데이터들의 배열이라고 알려주고, 직접 인덱스를 통해 배열을 확인하는 시간을 가졌다. 이 때 형식 지정자는 문자 자료형을 출력하는 것이기 때문에 %s 대신 %c를 사용하였고, 문자열이 끝날 때 ₩n을 사용해주었다. 이 이유에 대해 생각해보자라는 글이 있어서 적어보자면 내 생각에는 각 문자열을 구분하기 위해 ₩n을 사용하는 것 같다. 그리고 댓글을 봤는데 나랑 비슷한 생각을 하신 분들이 대다수였다.

18. 2022.08.21 문자열의 활용에 대한 학습을 했다. 문자열의 길이를 구하는 함수와 그 함수를 이용하여 문자열에 있는 문자 하나 하나를 돌면서 다시 출력해보는 과정을 알려주었고, 이를 활용해 문자 하나 하나를 돌면서 소문자이면 대문자로 바꿔주는 과정도 배웠다. 소문자를 대문자로 변환해주는 함수도 있었고, 아스키 코드라는 점을 이용하여 모든 대문자와 소문자가 32 차이가 나고, 소문자 -32를 하면 대문자 변환이 된다는 것도 배웠다. 강의 중간에 키보드에 이런 대문자 처리하는 기능을 누르면 -32를 하여 대문자로 변환해준다고 하셨는데 평상 시 많이 쓰던 대소문자 변환이 이런 과정이었구나를 알게됐다.

19. 2022.08.22 오늘 강의는 명령행 인자에 대한 강의였다. c언어에서 main 함수에 받는 인자로 void가 아닌 명령행 인자인 argc, argv를 받을 수 있다. argc는 받을 인자의 수이고 argv는 받은 인자를 배열안에 넣는 명령행 메모리 목록이다. 이때 argc는 2개 이상일 때를 조건으로 걸어야 인자를 받았다고 하는 이유가 아무 인자를 넣지 않아도 argc 즉 argv[0]값은 파일명이 되기 때문에 다른 인자를 넣었다는 걸 argc 2개이상으로 처리하는 것이다. 이번 생각해보기는 명령행 인자를 사용했을 때 프로그램 확장성에 어떤 도움이 되는지 예시를 드는 것이었다. 코드가 간결해지는 것 외에는 잘 떠오르지 않았는데 다른 사람의 의견을 보니 코드 간결화랑, 프로그램 내부가 중도에 노출되더라도 인자로 사용된 데이터를 보호할 수 있다라는 의견도 있었다.
