# 3DMP -  Homework no. 3
<img src="https://github.com/Burdun/3DMP/blob/main/Homework/Homework%233/Pawn.png" height=170.3><img src="https://github.com/Burdun/3DMP/blob/main/Homework/Homework%233/Knight.png" height=170.3><img src="https://github.com/Burdun/3DMP/blob/main/Homework/Homework%233/Bishop.png" height=170.3><img src="https://github.com/Burdun/3DMP/blob/main/Homework/Homework%233/Rook.png" height=170.3><img src="https://github.com/Burdun/3DMP/blob/main/Homework/Homework%233/Queen.png" height=170.3><img src="https://github.com/Burdun/3DMP/blob/main/Homework/Homework%233/King.png" height=170.3>
---------------------------------------------------------------------------------------------
<img src="https://github.com/Burdun/3DMP/blob/main/Homework/Homework%233/Board.png" height=197.31><img src="https://github.com/Burdun/3DMP/blob/main/Homework/Homework%233/Chessboard.png" height=197.31>
----------------------------------------------------------------------------------------------------
### Tasks:
1. Turn on capture history.
2. Import an SVG (link [here](https://drive.google.com/drive/folders/1hP3PDJ7wgEmkW3Iuby4fesoqEDkGd0BF)) and design a chess pieces set: 
   - 1 pawn;
   - 1 knight;
   - 1 bishop;
   - 1 rook;
   - 1 queen;
   - 1 king.
3. Use the SVG sketch to revolve the pieces: 
   - You need to take care when designing the knight. Only the base should be revolved. Find another solution for the horse part e.g.: extrusion, fillet etc.;
   - When designing the bishop, revolve the part that doesn’t have the slit and then add the slit.

| <img src="https://github.com/Burdun/3DMP/blob/main/readme_resources/Fig%233.1.png" height=290 title="Fig. 3.1 - Recap: How to revolve"> |
| :--------------------------------: |
| *Fig. 3.1 - Recap: How to revolve* |

4. When using revolve, you need two things, the profile and the axis:
   - For the profile you will use half of the chess piece (Fig. 3.1 dark blue part);
   - For the axis you will use a line (Fig. 3.1 the red line) that cuts the piece in half;
   - You need to add this line by yourself, editing the SVG sketch using constraints (don’t add it using a new sketch, it needs to be in the same sketch for the revolve to work).
5. Use a circular pattern to add details on the top, neck and base of the pieces.
6. The SVG is a little bit stylized. The chess pieces contain smaller parts that are not connected. For the full grade, you need to find a way to make each chess piece only one body.

<table>
    <tbody>
        <tr>
            <td rowspan align="center" valign="center">Like this:</td>
            <td rowspan align="center" valign="center">Not like this:</td>
        </tr>
        <tr>
            <td align="center" valign="center"><img src="https://github.com/Burdun/3DMP/blob/main/readme_resources/Fig%233.2.1.png" align="center" height=290 title="Fig#3.2.1"></td>
            <td align="center" valign="center"><img src="https://github.com/Burdun/3DMP/blob/main/readme_resources/Fig%233.2.2.png" align="center" height=290 title="Fig#3.2.2"/></td>
        </tr>
        <tr>
            <td colspan=2 align="center" valign="center"><i>Fig. 3.2 - Each piece needs to be one single body</i></td>
        </tr>      
    </tbody>
</table>

7. Slice all the pieces in PrusaSlicer. 
8. (BONUS) Make the board as well. Multiply the pieces and align them on the board. Add appearance (videos about appearance can be found in the [course](https://www.youtube.com/playlist?list=PLFglUCrrcNc8-yT_D4yHQ1Xn0mK7rZQo1)).
