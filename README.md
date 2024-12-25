# Chess-AI-Challenge

Checkmate Moves: The bot evaluates each legal move and checks if it results in an immediate checkmate. Such moves are executed to conclude the game decisively.

Captures: If no checkmate move is available, the bot looks for moves that capture an opponent's piece, aiming to maximize material advantage.

Pawn Promotions to Queen: If a pawn can be promoted to a queen, the bot prioritizes this powerful upgrade to strengthen its position on the board.

Random Moves: When no critical moves are found, the bot selects a random legal move to continue the game.

The bot uses the board's current state, represented as a FEN (Forsyth-Edwards Notation) string, to evaluate the game position and generate moves.
