# FOR BEGINNERS

### VIM으로 가장 기본적인 문서 편집만을 하고 싶다면
세 가지를 알아야 합니다.
* [모드 전환 방법](#모드-전환-방법)
* [VIM을 종료하는 방법](#VIM을-종료하는-방법)
* [저장하는 방법](#저장하는-방법)

#### 모드 전환 방법
* 화면의 최하단을 봅니다. `NORMAL`이라 되어 있으면 `NORMAL`모드이고, `INSERT`라 되어 있으면 `INSERT`모드입니다.

>`NORMAL`모드일 때에는 아직 마음껏 타이핑을 하지 않도록 합니다. 커서가 여기저기 점프하고 글자가 삭제될 수 있습니다.<br>
>`INSERT`모드가 되면 평범한 워드 프로세서처럼 사용할 수 있습니다.

* `NORMAL`모드일 때 `i`를 누르면 `INSERT`모드로 바뀝니다.
* `INSERT`모드일 때 `<ESC>`를 누르면 `NORMAL`모드로 돌아갑니다.

>여러 가지 모드 전환 방법이 있지만 일단 위의 두 키만 기억해 두도록 합니다.

#### VIM을 종료하는 방법
>VIM 사용법을 모르는 사람이 우연히 VIM을 실행하여 종료하지 못하는 경우가 있습니다.

* VIM은 `NORMAL`모드에서만 종료할 수 있습니다.
* `INSERT`모드라면 `<ESC>`키를 누르면 `NORMAL`모드로 전환할 수 있습니다.
* `NORMAL`모드라면 아래의 표에 나와 있는 방법을 참고하여 VIM을 종료하도록 합니다.

| 키    | 설명                                                                                                  |
| ----  | :----------------------------------------------                                                       |
| `:q`  | VIM을 종료합니다. 편집중이던 파일이 있으면 저장하지 않았음을 알려주며 종료되지 않습니다.              |
| `:q!` | VIM을 강제로 종료합니다.                                                                              |
| `:wq` | 편집중인 파일을 저장하고 VIM을 종료합니다.                                                            |
| `:x`  | 편집중인 파일을 저장하고 VIM을 종료합니다. 단, 파일 내용이 변경되지 않았을 경우 저장 없이 종료합니다. |
| `ZZ`  | 편집중인 파일을 저장하고 VIM을 종료합니다. (대문자 Z를 두 번 연속으로 누릅니다.)                      |

#### 저장하는 방법
* VIM은 `NORMAL`모드에서만 저장할 수 있습니다.
1. `<ESC>`키를 입력하여 `INSERT`모드에서 `NORMAL`모드로 전환합니다.
1. `:w`를 입력하면 편집중이던 파일이 저장됩니다.
1. `:w filename`을 입력하면 filename 으로 saveas 할 수 있습니다(다른이름으로 저장).

>위의 것들만 알아두면 가장 기본적인 편집을 하는 데에는 문제가 없습니다.