# 설치하기

## 설치 파일을 내려 받기

AutoIt3은 아래 링크에서 다운로드받으세요.

[AutoIt3 내려받기](https://www.autoitscript.com/files/autoit3/autoit-v3-setup.exe)

다운로드 웹페이지는 [여기](https://www.autoitscript.com/site/autoit/downloads/)를 클릭하세요.

넓은마을 공개자료실이나 넓은마을 프로그래밍 동호회 자료실에서도 다운로드할 수 있습니다. 2018년 1월 현재 최신 버전은 3.3.14.2입니다.

## 설치 과정

내려받은 autoit3/autoit-v3-setup.exe 파일을 실행합니다. 잠시 기다리면 'AutoIt v3.3.14.2 Setup' 대화상자가 열립니다.

Next 버튼을 누르거나 Alt+N을 눌러서 설치를 시작합니다.

License Agreement 단계입니다. 

'I Agree' 버튼을 누르거나 Alt+A를 누르면 라이센스에 동의하고 설치가 계속됩니다.

64비트 윈도우즈의 경우 '64­bit Operating System Support...' 단계가 나옵니다. 여기에서 AutoIt와 관련된 도구들을 64비트로 설정할지 32비트로 설정할지를 선택할 수 있습니다. 기본값은 64비트입니다.

Next 버튼을 누르거나 Alt+N을 눌러서 다음을 진행합니다.

'Defaults for *.au3 What do you want to do when you double­click a *.au3 file?' 단계입니다. 윈도우 탐색기에서 .au3 파일을 더블 클릭하거나 엔터키를 누를 때 어떤 작업을 할 것인지를 선택합니다. .au3 파일을 실행할 수도 있고 AutoIt 전용 코드 편집기로 .au3 파일을 편집할 수도 있습니다. AutoIt를 배우는 입장에서는 .au3 파일을 편집하는 것이 좋습니다.

Edit the script 라디오버튼을 선택하고 Next 버튼이나 Alt+N을 눌러 다음으로 진행합니다.

'Choose Components' 단계입니다. 기본값은 Full이므로 수정할 필요가 없습니다.

Next 버튼이나 Alt+N을 눌러 다음으로 진행합니다.

'Choose Install Location' 단계입니다. 설치될 폴더를 변경할 수 있습니다만 기본값으로 두어도 무방합니다. 폴더를 변경할 경우에만 'Browse...' 버튼을 눌러서 새로운 경로를 설정하세요.

Install 버튼을 누르거나 Alt+I를 누르면 하드디스크에 AutoIt3이 설치됩니다.

잠시 기다리면 설치가 완료됩니다.

Finish  버튼을 누르거나 Flt+F를 누르면 설치 대화상자가 닫힙니다. 

축하합니다.이제부터 AutoIt3을 즐겨 주세요.

## 전용 코드 편집기 환경 설정

### 메뉴 한글화 파일 내려받기

AutoIt3에는 AutoIt SciTE 전용 코드 편집기가 있습니다. SciTE를 사용하면 좀 더 편리하게 AutoIt 프로그램을 만들 수 있습니다. 하지만 메뉴가 모두 영문입니다. 이것을 한글로 만들면 초보자들에게는 훨씬 더 편리할 것입니다. 한글 메뉴가 잘못된 경우나 누락된 경우 내용을 추가/수정할 수도 있습니다. 또 기본 설정값으로는 한글 입력에 문제가 있습니다. 이 두 가지 문제를 간단히 해결할 수 있습니다.

아래 링크에서 한글화 환경 설정 파일을 내려 받으세요.

[메뉴 한글화 환경설정 파일 내려받기](SciTE_Korean.zip)

내려받은 파일의 압축을 해제합니다. 그러면 두 개으ㅟ 파일이 나올 것입니다.

- locale.ko_KR.properties	 : 메뉴를 한글화하는 환경 파일입니다. 텍스트 파일로 수정ㄱ 가능합니다.
- SciTEGlobal.properties : SciTE의 전역 환경 설정 파일입니다.

이 두 파일을 다음 경로에 복사합니다.

- 32비트 윈도우즈 : C:\Program Files\AutoIt3\SciTE
- 64비트 윈도우즈 : C:\Program Files (x86)\AutoIt3\SciTE

이제 SciTE 메뉴가 한글로 나올 것입니다. 편집창에 한글을 입력해도 잘 나올 것입니다.

### 센스리더를 위한 단축키

NVDA 사용자는 별도의 작업이 없습니다. 그러나 센스리더 사용자라면 문장부호, 구두점과 붙어 있는 공백문자를 제대로 읽어 주지 못하기 때문에 Shift+F11 키를 눌러 주어야 합니다. 편집을 시작할 때마다 Shift+F11을 누르세요.

- Shift+F11 : 텍스트 편집 모드
- Shift+F12 : AutoIt 편집 모드

축하합니다. 이제 모든 준비를 마쳤습니다. 아래는 당장 알아야할 필요는 없습니다. 하지만 한번 읽어 두시는 것도 좋습니다.

## AutoIt의 폴더/파일 구조

AutoIt3의 설치 경로는 주로 다음과 같습니다.

C:\Program Files (x86)\AutoIt3

### 최상단 파일

- AutoIt3.exe : AutoIt3의 메인 프로그램으로 .au3 파일을 실행할 때 필요합니다.
- AutoIt3_x64.exe : 64비트 버전의 AutoIt3 메인 프로그램입니다.
- Au3Info.exe : 윈도우/컨트롤의 정보를 알려 주는 도구입니다.
- Au3Info_x64.exe : 64비트 버전의 윈도우/컨트롤 정보를 알려 주는 도구입니다.
- AU3Check.exe : AutoIt 문법 검사기 프로그램입니다.
- AutoIt.chm : AutoIt3의 도움말 파일입니다.
- Uninstall.exe : 설치 제거용 프로그램입니다.

### Aut2Exe 폴더

- Icons 폴더 : Aut2Exe에서 사용하는 아이콘 파일들이 들어 있습니다.
- Aut2Exe.exe : .au3 파일을 단독 실행 가능한 .exe 파일로 컴파일하는 도구입니다.
- Aut2Exe_x64.exe : 64비트용 컴파일러입니다.
- UPX.exe : 컴파일한 .exe 파일을 압축하는 도구입니다.

### Examples 폴더

- COM 폴더 : AutoIt에서 COM을 사용하는 예제가 들어 있습니다.
- GUI 폴더 : AutoIt에서 GUI를 만드는 예제가 들어 있습니다.
- Helpfile 폴더 : 도움말에 포함된 수많은 함수들의 예제가 들어 있습니다.

### Extras 폴더 

- AutoUpdateIt 폴더 최신 버전을 쉽게 내려받을 수 있는 스크립트가 담겨 있습니다.
- Editors 폴더 : 대중적인 텍스트 편집기에서 AutoIt 문법 강조 기능을 사용할 수 있게 하는 파일들이 들어 있습니다.
- Geshi 폴더 : Geshi 서버에서 사용하는 AutoIt 문법 강조기입니다.
- Prettify\ : 클라이언트 자바스크립트 Google Prettify의 AutoIt 문법 강조기입니다.
### Icons 폴더

- 윈도우 탐색기에서 .au3 파일을 표시하는 아이콘이 들어 잇습니다.

### Include

- 표준 헤더 파일과 사용자 정의 헤더 파일이 들어 있습니다.


### AutoItX 폴더 

- ActiveX와 COM을 지원하는 AutoIt의 dll 버전이 들어 있습니다.

### SciTE

- 이 폴더에는 AutoIt 문법 강조 기능을 가진 SciTE의 라이트 버전이 포함되어 있습니다.

참고샇항

- .au3 파일을 실행하기 위해서는 단지 AutoIt3.exe 파일이 필요합니다. .exe로 컴파일된 프로그램은 AutoIt3.exe 파일 조차 필요하지 않습니다. 
- 영문 메뉴얼의 Registry Keys 부분은 생략합니다.

[처음으로](../readme.md) | [이전으로](02-license.md) | [다음으로](../2-using/01-intend.md)