Slutprojekt
Planering av slutprojekt i programmering 2
Project - Z
Jag ska göra ett labyrintspel,där spelaren kommer vandra runt i en randomiserad labyrint för att hitta ett antal objekt som öppnar en förseglad dörr. När dörren sedan öppnas kommer den försvinna i två korta sekunder för att poppa upp på ett annat ställe.
Klasser
MazeRunner
Själva spelaren, ska kunna förflytta sig höger, vänster, upp och ner. En ficklampa följer i den riktningen spelaren kollar i (den senaste inputen av användaren)
Maze
Bestämmer hur labyrinten ska genereras.
MazeGenerator
Ärver av MonoBehaviour
Systemet för hur labyrinten genereras
MazeSprite
Ärver av MonoBehaviour
Genererar en labyrint med alla sprites, helt slumpmässigt.
Tools
Shufflar en array, vilket ger generatorn sin slumpmässighet.
Keys
För att öppna dörren, slumpade positioner
Door/End
Dörren öppnas när alla nyckelobjekt har samlats in
GoalReached
För att avsluta nivån, gå till en ny sida för att visa scoreboarden, alternativ för att fortsätta eller avsluta
MainMenu
	Spela
	Ladda spel
	Highscores
	Avsluta
DoorShuffle
	Byter position på dörren
