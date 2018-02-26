# Deeper Blue
- Chess game written in Ruby
- <a href='https://github.com/jifarooq/DeeperBlue/blob/master/game.rb'>Features<a/> include tracking points, pieces captured, and a timer
- Implements deep dup method of <a href='https://github.com/jifarooq/DeeperBlue/blob/master/board.rb'>board</a> to prevent player from moving into check
- Uses classical inheritance with bishop, queen and rook inheriting from <a href="https://github.com/jifarooq/DeeperBlue/blob/master/pieces/sliding_piece.rb">sliding piece</a> class
- Board FLIPS when it is your turn

## To play
 - Clone this repo
 - Navigate to the DeeperBlue folder from the command line
 - Run `ruby game.rb`