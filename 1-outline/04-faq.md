# 자주하는 질문 (FAQ)

여기에 나오는 질문들은 AutoIt 포럼에서 아주 빈번하게 올라오는 질문들의 일부입니다. 더 궁금한 것들은 AutoIt 포럼을 찾아 보세요. 안타깝게도 모두 영문입니다. 아쉬운대로 [넓은마을](http://web.kbuwel.or.kr) [프로그래밍 동호회](http://web.kbuwel.or.kr/?cl=int)를 찾아 주시면 질문에 대한 답변을 성실히 찾아 보겠습니다. AutoIt 입문자들은 굳이 이 부분을 볼 필요가 없습니다. 다음으로 넘어가셔도 좋습니다. 

## 1. AutoIt에서 도스 프로그램은 어떻게 실행해야 하나요?

만약 "dir" 같은 명령을 실행하고 싶으면, 명령행 해석기(Command Interpreter)을 먼저 실행해야 합니다. 운영 체제에 따라 command.com이나 cmd.exe 같은 프로그램입니다. @ComSpec 매크로에는 이 프로그램들의 정확한 주소가 들어 있습니다. RunWait() 함수를 사용하면 도서스 명령어가 종료되기 전까지 다음 스크립트가 실행되지 않습니다. 다음은 예제입니다. 

RunWait(@ComSpec & " /c Dir C:\") 

나중에 조금씩 추가할께요.^^

[처음으로](../readme.md) | [이전으로](03-install.md) | [다음으로](../2-using/01-runningScripts.md)