# ChessEngineV1
All move generation, game implementation, graphics, and GUI was made by me and therefore
this engine is a bit slow and weak as far as engines go.

The engine simply uses the Minimax algorithm to search the space of possible moves and counter moves.
ELO on chess.com is only about 800 (unless you let it think for long periods of time)
Can search 3-5 moves deep in about one second.

Known bugs and shortcomings:
1. En-passant captures were not implemented in this version
2. Somes cases where the undo move function fails to de-premote pieces correctly
3. No under promoting option
4. Various draws (like 5-move repetition, 50 move rule, etc) are not implemented

All of these could probably be fixed with a bit of work, but with other libraries like
chess.js available I was not too motivated to improve my implemetation of the game of chess.
My interest was more on the development of the chess engine anyway.

Test My Engine at https://scott-poole.github.io/ChessEngineV1/chessEngine.html
