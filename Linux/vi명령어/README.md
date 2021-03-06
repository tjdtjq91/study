### VIM / VI 명령어 정리

1. 명령 모드에서 입력 모드로 전환하는 명령어

| 명령어 | 설명 |
| :------------- | :------------- |
| i | 현재 커서의 위치부터 입력       |
| I | 현재 커서 줄의 맨 앞에서부터 입력 (shift + i) |
| a | 현재 커서의 위치 다음 칸부터 입력 |
| A | 현재 커서 줄의 맨 마지막부터 입력 (shift + a) |
| o | 현재 커서의 다음 줄에 입력 |
| O | 현재 커서의 이전 줄에 입력 (shift + o) |
| s | 현재 커서 위치의 한 글자를 지우고 입력 |
| S | 현재 커서의 한 줄을 지우고 입력 (shift + s) |

2. 커서 이동 명령어

| 명령어 | 설명 |
| :------------- | :------------- |
| h | 커서를 왼쪽으로 한 칸 이동 |
| k | 커서를 위로 한 칸 이동 |
| j | 커서를 아래로 한 칸 이동 |
| l | 커서를 오른쪽으로 한 칸 이동 |
| Ctrl + f | 다음 화면으로 이동(page down과 같은 의미) |
| Ctrl + b | 이전 화면으로 이동(page up과 같은 의미) |
| ^ | 현재 행의 처음으로 이동 (Home과 같은 의미) |
| $ | 현재 행의 마지막으로 이동(End와 같은 의미)  |
| gg | 제일 첫 행으로 이동 |
| G | 제일 끝 행으로 이동(shift + g) |
| 숫자G | 해당 숫자의 행으로 이동 |
| :숫자 enter | 해당 숫자의 행으로 이동 |

3. 삭제, 복사, 붙여넣기 명령어

| 명령어 | 설명 |
| :------------- | :------------- |
| x | 현재 커서가 위치한 글자 삭제 |
| X | 현재 커서가 위치한 앞 글자 삭제(BackSpace와 같은 의미, shift+x) |
| dd | 현재 커서의 행 삭제 |
| 숫자dd | 현재 커서부터 숫자만큼의 행 삭제 |
| yy | 현재 커서가 있는 행을 복사 |
| 숫자yy | 현재 커서부터 숫자만큼의 행을 복사 |
| p | 복사한 내용을 현재 행 이후에 붙여넣기 |
| P | 복사한 내용을 현재 행 이전에 붙여 넣기(shift + p) |

4. 문자열 찾기

| 명령어 | 설명 |
| :------------- | :------------- |
| /문자열 | 해당 문자열을 찾음(현재 커서 이후로) |
| n | 찾은 문자 중에서 다음 문자로 이동 |
| N | n과 같으며 역방향으로 이동 |
