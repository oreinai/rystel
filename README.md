#_Rystel_ Design Doc 1.10

##Table of Contents 
-Synopsis
-Pitch
-Software/Hardware Specs

-The Main View
--Puzzle Board
--Pieces

-Function
--Interactable pieces
--Text Edit
--Holding pictures
--Animations (Future iterations)
--Font
--“Hero” Piece
--“Goals” Piece
--“Roadblocks” Piece
--“Encourage Me” Piece
-“Reminders” Piece

-Credits

Concept art

##Disclaimer: Everything in this document is subject to change.

If something doesn’t match up with how your design is turning out, let the rest of the team know by commenting and the document can be updated.

##Synopsis

###The Pitch

Rystel is a goal tracking app in the shape of a puzzle board with selectable “piece” that you can customize to track your life, goals, heroes, impediments, and anything else in your life you want to solve.

###Software/Hardware

Rystel will be made in JavaScript, HTML/CSS, PouchDB, React, ect. 

###The Main View

Rystel is a 2D puzzle board with a top down view. The plane is flat and shows the full board.

Each selectable piece will have definitive boards and colors. Text or a picture will displayed within the piece itself. The text may scroll in future iteration if more than a few items exist on the list.

###Puzzle Board

The Puzzle Board will act as the housing structure that holds the main menu and the pieces that track all text/pictures.

The puzzle board will be brown in color and give off the appearance that the pieces fit into a box.

###Pieces

The pieces will act as the receptacle for the text and pictures. Each with a differing shape, color, and layout. Text or a picture will fill the tile and be clearly visible.

###Function

1. Interactable Pieces
When the app starts the puzzle board will appear with all of the current puzzle pieces aligned from Hero, current goals, road-blocks, and “be mindfulls” in a clockwise position with a reminder piece in the center. Each piece on the board will take its own shape. These pieces are set in this order by default but can be altered.

###Text Edit

When a piece is selected, the tile will highlight and expand. The text inside will become editable along with featuring a scroll incase there are a number of items that are going to be listed.

###Holding Pictures

The “Hero” piece will contain either text or a picture depending on the user. The picture will display normally in a smaller format to fit into the tile. When selected the piece expand to show a bigger size of the picture along with a field for text. The intent for the text is so that the user can write why they selected this person.

###Animations

To be added in future builds.

###Font

The font of choice for the app is Calibri.

###“Hero” Piece

The Hero tile piece revolves around the users current “hero”, “idol”, “role model”, ect. The tile piece operations consists of showing a picture or phrase that the user looks to for guidance on top of the dormant top puzzle piece. When activated, the picture and tile piece take focus and expand to reveal a text fields. The field allows the user to input information as to why they chose the hero they did.

Components:

Picture field
Editable text field

###“Current Goals” Piece

The Goals tile will appear on the right hand side of the application and focus on achievements the user wishes to accomplish. The tile operation will consist of a soft transition between the words “Goals” and the list made within the tile’s text field on the tile piece itself. Once activated, the tile will expand in a similar fashion as the “Hero” tile piece. The pane opens to a list that can be changed. Once the list is visible, the user would then be able to create, edit, deleted, and re-list their goals/data as they see fit.

Components:

Script to display “Goal” and saved list within the text field in the pane itself
Editable text field
Editable list field

###“Roadblocks” Piece

The Roadblocks tile will appear on the bottom puzzle piece on the board. The tile is smaller than the rest and will focus on what present a challenge to the use. The tile will softly display the words “Roadblock” and rotate, one by one, the impediments the user has listed within the tile itself. When activated, the Roadblock’s window takes focus and present a similar format to the “Heroes” and “Goals” panes.

Components:

Script to display “Roadblocks” and saved list item within the text field in the pane itself
Editable text field
Editable list field

###“Be Mindfuls” Piece

The Roadblocks tile will appear on the bottom puzzle piece on the board. The tile is smaller than the rest and will focus on what present a challenge to the use. The tile will softly display the words “Be Mindfuls” and rotate, one by one, the reminders the user has listed within the tile itself. When activated, the "Be Mindfuls" window takes focus and present a similar format to the “Heroes” and “Goals” panes.

Components:

Script to display “Be Mindfuls” and saved list item within the text field in the pane itself
Editable text field
Editable list field

##Credits

Michael Blackard: Director/Producer/Designer

Zachary Fullerton:	Programmer/Designer

##Concept Art
