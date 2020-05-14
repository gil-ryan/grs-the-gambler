# Chess

## Piece Symbols
|Name|Symbol|Code point|HTML (decimal)|HTML     (hex)|
|:-:|:-:|:-:|:-:|:-:| 
|white chess king|♔| U+2654|&#9812;|&#x2654;|
|white chess queen|♕|U+2655| &#9813;|&#x2655;|
|white chess bishop|♗|U+2657|	&#9815;| &#x2657;|
|white chess rook |♖|U+2656 |&#9814; |&#x2656;|
|white chess knight|♘|U+2658| &#9816; |&#x2658;|
|white chess pawn |♙|U+2659 |&#9817;| &#x2659;|
|black chess king|♚|U+265A |&#9818; |&#x265A;|
|black chess queen|♛|U+265B |&#9819;|&#x265B;|
|black chess rook |♜ |U+265C|	&#9820; |&#x265C;|
|black chess bishop|♝ |U+265D|&#9821;|&#x265D;|
|black chess knight|♞|U+265E| &#9822; |&#x265E;|
|black chess pawn |♟|U+265F|&#9823;|&#x265F; |

## Key to Symbols!

| Symbol | Meaning |
|:-:|:-:|
|!| a good move|
|?| a weak move|
|!!| an excellent move|
|!?| an interesting move|
|?!| a dubious move|
|□| only move|
|N|novelty|
|⟳|lead in development|
|⨀|zugswang|
|=|equality|
|∞|unclear position w/ compensation|
|©|sacraficed material|
|⩲| white stands slighty better|
|⩱|black stands slightly better|
|±|white has serious advantage|
|∓|black has serious advantage|
|+-|white has a decisive advantage|
|-+|black has a decisive advantage|
|→| with an attack |
|↑| with initiative|
|⇆|with counterplay|
|∆|with the idea of|
|⌓|better is|
|≤|worse is|
|+|check|
|#|mate|


```HTML
==Chessboard using Unicode symbols==
{| style="text-align:center;border-spacing:0pt;font-family:'Arial Unicode MS'; border-collapse:collapse; border-color: black; border-style: solid; border-width: 0pt 0pt 0pt 0pt"
|-
| style="width:12pt" | 8
| style="width:24pt; height:24pt; border-collapse:collapse; border-color: black; border-style: solid; border-width: 1pt 0pt 0pt 1pt" | <span style="font-size:150%;">♜</span>
| style="width:24pt; height:24pt; border-collapse:collapse; border-color: black; border-style: solid; border-width: 1pt 0pt 0pt 0pt" bgcolor="silver" | <span style="font-size:150%;">♞</span>
| style="width:24pt; height:24pt; border-collapse:collapse; border-color: black; border-style: solid; border-width: 1pt 0pt 0pt 0pt" | <span style="font-size:150%;">♝</span>
| style="width:24pt; height:24pt; border-collapse:collapse; border-color: black; border-style: solid; border-width: 1pt 0pt 0pt 0pt" bgcolor="silver" | <span style="font-size:150%;">♛</span>
| style="width:24pt; height:24pt; border-collapse:collapse; border-color: black; border-style: solid; border-width: 1pt 0pt 0pt 0pt" | <span style="font-size:150%;">♚</span>
| style="width:24pt; height:24pt; border-collapse:collapse; border-color: black; border-style: solid; border-width: 1pt 0pt 0pt 0pt" bgcolor="silver" | <span style="font-size:150%;">♝</span>
| style="width:24pt; height:24pt; border-collapse:collapse; border-color: black; border-style: solid; border-width: 1pt 0pt 0pt 0pt" | <span style="font-size:150%;">♞</span>
| style="width:24pt; height:24pt; border-collapse:collapse; border-color: black; border-style: solid; border-width: 1pt 1pt 0pt 0pt" bgcolor="silver" | <span style="font-size:150%;">♜</span>
|-
| style="width:12pt" | 7
| style="width:24pt; height:24pt; border-collapse:collapse; border-color: black; border-style: solid; border-width: 0pt 0pt 0pt 1pt" bgcolor="silver" | <span style="font-size:150%;">♟</span>
| style="width:24pt; height:24pt;" | <span style="font-size:150%;">♟</span>
| style="width:24pt; height:24pt;" bgcolor="silver" | <span style="font-size:150%;">♟</span>
| style="width:24pt; height:24pt;" | <span style="font-size:150%;">♟</span>
| style="width:24pt; height:24pt;" bgcolor="silver" | <span style="font-size:150%;">♟</span>
| style="width:24pt; height:24pt;" | <span style="font-size:150%;">♟</span>
| style="width:24pt; height:24pt;" bgcolor="silver" | <span style="font-size:150%;">♟</span>
| style="width:24pt; height:24pt; border-collapse:collapse; border-color: black; border-style: solid; border-width: 0pt 1pt 0pt 0pt" | <span style="font-size:150%;">♟</span>
|-
| style="width:12pt" | 6
| style="width:24pt; height:24pt; border-collapse:collapse; border-color: black; border-style: solid; border-width: 0pt 0pt 0pt 1pt" | <span style="font-size:150%;"><br></span>
| style="width:24pt; height:24pt;" bgcolor="silver" | 
| style="width:24pt; height:24pt;" | 
| style="width:24pt; height:24pt;" bgcolor="silver" | 
| style="width:24pt; height:24pt;" | 
| style="width:24pt; height:24pt;" bgcolor="silver" | 
| style="width:24pt; height:24pt;" | 
| style="width:24pt; height:24pt; border-collapse:collapse; border-color: black; border-style: solid; border-width: 0pt 1pt 0pt 0pt" bgcolor="silver" | 
|-
| style="width:12pt" | 5
| style="width:24pt; height:24pt; border-collapse:collapse; border-color: black; border-style: solid; border-width: 0pt 0pt 0pt 1pt" bgcolor="silver" | <span style="font-size:150%;"><br></span>
| style="width:24pt; height:24pt;" | 
| style="width:24pt; height:24pt;" bgcolor="silver"| 
| style="width:24pt; height:24pt;" | 
| style="width:24pt; height:24pt;" bgcolor="silver"| 
| style="width:24pt; height:24pt;" | 
| style="width:24pt; height:24pt;" bgcolor="silver" | 
| style="width:24pt; height:24pt; border-collapse:collapse; border-color: black; border-style: solid; border-width: 0pt 1pt 0pt 0pt" | 
|-
| style="width:12pt" | 4
| style="width:24pt; height:24pt; border-collapse:collapse; border-color: black; border-style: solid; border-width: 0pt 0pt 0pt 1pt" | <span style="font-size:150%;"><br></span>
| style="width:24pt; height:24pt;" bgcolor="silver" | 
| style="width:24pt; height:24pt;" | 
| style="width:24pt; height:24pt;" bgcolor="silver" | 
| style="width:24pt; height:24pt;" | 
| style="width:24pt; height:24pt;" bgcolor="silver" | 
| style="width:24pt; height:24pt;" | 
| style="width:24pt; height:24pt; border-collapse:collapse; border-color: black; border-style: solid; border-width: 0pt 1pt 0pt 0pt" bgcolor="silver" | 
|-
| style="width:12pt" | 3
| style="width:24pt; height:24pt; border-collapse:collapse; border-color: black; border-style: solid; border-width: 0pt 0pt 0pt 1pt" bgcolor="silver" | <span style="font-size:150%;"><br></span>
| style="width:24pt; height:24pt;" | 
| style="width:24pt; height:24pt;" bgcolor="silver"| 
| style="width:24pt; height:24pt;" | 
| style="width:24pt; height:24pt;" bgcolor="silver"| 
| style="width:24pt; height:24pt;" | 
| style="width:24pt; height:24pt;" bgcolor="silver"| 
| style="width:24pt; height:24pt; border-collapse:collapse; border-color: black; border-style: solid; border-width: 0pt 1pt 0pt 0pt" | 
|-
| style="width:12pt" | 2
| style="width:24pt; height:24pt; border-collapse:collapse; border-color: black; border-style: solid; border-width: 0pt 0pt 0pt 1pt" | <span style="font-size:150%;">♙</span>
| style="width:24pt; height:24pt;" bgcolor="silver" | <span style="font-size:150%;">♙</span>
| style="width:24pt; height:24pt;" | <span style="font-size:150%;">♙</span>
| style="width:24pt; height:24pt;" bgcolor="silver" | <span style="font-size:150%;">♙</span>
| style="width:24pt; height:24pt;" | <span style="font-size:150%;">♙</span>
| style="width:24pt; height:24pt;" bgcolor="silver" | <span style="font-size:150%;">♙</span>
| style="width:24pt; height:24pt;" | <span style="font-size:150%;">♙</span>
| style="width:24pt; height:24pt; border-collapse:collapse; border-color: black; border-style: solid; border-width: 0pt 1pt 0pt 0pt" bgcolor="silver" | <span style="font-size:150%;">♙</span>
|-
| style="width:12pt" | 1
| style="width:24pt; height:24pt; border-collapse:collapse; border-color: black; border-style: solid; border-width: 0pt 0pt 1pt 1pt" bgcolor="silver" | <span style="font-size:150%;">♖</span>
| style="width:24pt; height:24pt; border-collapse:collapse; border-color: black; border-style: solid; border-width: 0pt 0pt 1pt 0pt" | <span style="font-size:150%;">♘</span>
| style="width:24pt; height:24pt; border-collapse:collapse; border-color: black; border-style: solid; border-width: 0pt 0pt 1pt 0pt" bgcolor="silver" | <span style="font-size:150%;">♗</span>
| style="width:24pt; height:24pt; border-collapse:collapse; border-color: black; border-style: solid; border-width: 0pt 0pt 1pt 0pt" | <span style="font-size:150%;">♕</span>
| style="width:24pt; height:24pt; border-collapse:collapse; border-color: black; border-style: solid; border-width: 0pt 0pt 1pt 0pt" bgcolor="silver" | <span style="font-size:150%;">♔</span>
| style="width:24pt; height:24pt; border-collapse:collapse; border-color: black; border-style: solid; border-width: 0pt 0pt 1pt 0pt" | <span style="font-size:150%;">♗</span>
| style="width:24pt; height:24pt; border-collapse:collapse; border-color: black; border-style: solid; border-width: 0pt 0pt 1pt 0pt" bgcolor="silver" | <span style="font-size:150%;">♘</span>
| style="width:24pt; height:24pt; border-collapse:collapse; border-color: black; border-style: solid; border-width: 0pt 1pt 1pt 0pt" | <span style="font-size:150%;">♖</span>
|-
| 
| a
| b
| c
| d
| e
| f
| g
| h
|}
```