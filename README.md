# Cross
Tic Tac Toe game
first task

board = list(range(1, 10))

def draw_board():
    global board  # added to access the global board variable
    print('---------------')
    for i in range(3):
        print('|', board[0 + i * 3], '|', board[1 + i * 3], '|', board[2 + i * 3], '|')
    print('---------------')


draw_board()
