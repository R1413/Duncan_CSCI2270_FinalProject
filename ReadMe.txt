[COOL GAME TITLE]

Project Summary

    This program is a spin off of the traditional Chess; however, rather than taking place on a simple 8x8 board it takes place on an 8x8x8 board, IT'S IN THREE DIMENSIONS. Many of the game pieces are slightly altered so that they can move along the new dimension. There are also two additional pieces (yet to be named) that are able to move in slightly more complicated ways than the altered pieces. Have fun!


How to Run

    To run the code one must first download the main.cpp file, the chessBoard.h file, and the chessBoard.cpp file. Once this is completed One should place the files into a project, or somehow run them all together.
    The program will run through each players turn. Onceyou select play, you are offered the choices of either printing the board, or moving a piece. If print board is chosen, the program will print out the location of all pieces for both teams. If play is chosen, a list of all your available pieces is displayed with an index number next to each. Select an index number and hit enter. 
    Once this is completed, the program displays locations that one can move the piece to, or locations the piece can attack, if an enemy piece is at a diagonal location. One must then enter one of the locations in a xyz format. No commas or spaces. The program will then move the piece and switch to the other players turn.


Dependencies

    Need just the basic codeblocks, or really any C++ program to run


System Requirements

    This program has been designed on Windows but can be run on other operating systems, provided it is with a C++ program


Group Members

Raymond Duncan(R1413) and Robert Tyrell-Ead(roty7961)


Contributors

[People]


Open issues/bugs

If you attempt to move a piece it does not always work correctly. Sometimes it displays the wrong locations to move to.
      For example: On player 2's first turn, if one selects the piece at location (0,5,1) it offers locations (0,4,5)(0,5,4)(1,5,5). These are all incorrect, as this means the piece is technically moving 3 or 4 spaces. It should offer like (0,5,0)(0,4,1)
Also, after the on the second move of the same piece, the program offers the location the piece is at to move a piece, which it should'nt. 
      For example: If player 1 chooses to move piece (0,0,1) to location (0,1,0), then choose to move that piece again, the program offers (0,1,0) as a move location. Shouldn't do this.   *Note, this (0,1,0) is not supposed to be where this piece can move. That is too far
  
