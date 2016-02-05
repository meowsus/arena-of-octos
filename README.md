# Arena of Octos

This is a straight copy of the source code of the Apple II/TRS-80 game [Arena of Octos](https://en.wikipedia.org/wiki/Arena_of_Octos), as published in a 1981 issue of SoftSide magazine.

My uncle, Alan Johnston, was co-creator and wrote the TRS-80 version. This was the only program he ever had published. He died in late January, 2016, so this is my homage to him.

SoftSide, the publishing company and owner of the game, has lone been out of business, so I am assuming I am not breaking any copyright laws by publishing this. If I am please get in touch and I will gladly remove the code.

## Working Example
http://meows.us/octos

## Known bugs
- cannot die, players are immortal (discovered at Level 3, error line 2610)

## Explanation of Variables

Variable | Description
---------| -----------
`AN` | Out-of-arena flag
`A$` | `INKEY$` variable
`BD(14,14)` | Board array. (Defines out-of-arena, pit, and stone positions)
`C(8,8)` | Octon array. (Contains Octon positions and status: strength, number of moves left, etc)
`CL` | Number of Octon moves left
`CX,CY` | Octon's present position
`DD` | Practice flag
`DS` | Distance from Octon to human
`DX,DY` | Difference between Octon and human positions
`F$(25)` | Fire string
`FG` | General utility flag
`G$` | Plural string
`GG` | Message variable
`HD` | Human-shielded flag
`HL` | Number of human moves left
`HM` | Number of human moves (10)
`HS` | Human strength
`HT` | "Human's turn" flag
`HX,HY` | Human's position
`I,J,K,L,M,N` | Iteration variables
`LF` | Number of Octon's left
`M$` | Message string
`MM` | Message number
`MV` | Move (1 - 4 or 6 - 9)
`NC` | Number of Octons
`NX,NY` | New location
`PX,PY` | Present location
`P$` | Player string
`RN` | Random number
`SB` | "Struck before?" flag
`WK` | Weakest Octon's strength
`X1,Y1` | Temporary X and Y locations
`X,Y` | Graphics variables
