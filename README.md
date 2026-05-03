# 초기 파이썬 설치 방법
    cmd 관리자 권한으로 실행
    winget install python.python.3.11
    이용약관 동의 y 엔터
    python --version 3.11.x나오면 성공!
    py -m pip install pygame

# 아싸~~
    집에서 열심히 코딩을 했어요!

# 처음에 다운로드
    git cloen [주소 붙여넣기]

# 그다음에
    add commit push

# 내가 지금 작업하는 폴더가 최신이 아니라면
    git pull origin master


# 과제1. 함수 설명(주석) 달기
## runGame()
### 게임의 메인 루프를 담당하는 함수
    def runGame():
    # setup variables for the start of the game
    board = getBlankBoard()
    lastMoveDownTime = time.time()
    ```