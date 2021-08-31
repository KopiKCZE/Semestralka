# Semestralka
**********
Aplikace slouží jako návrh Launcheru("Spuštěcího programu") s možností klikacích tlačítek, které mění pouze
panel na pravé straně. Nedochází tak k zavírání a znovuotevírání formulářů.
Responsivní menu.
Login a Register formuláře s využitím MS Acces a SQL příkaz.
OleDb - Microsoft API pro přístup k datům.
Checkbox pro zobrazení a skrytí hesla (character replacement).
Spouštěcí tlačítko pro hru (zde použit kulečník)
**První spouštěcí formulář - Login.cs**
**********
**Designové prvky**
- BorderStyle
- Dock
- FlatStyle
- Anchor
- FlatAppearance - BorderSize
- Zakulacené okraje v "MainScreen"
*Design ("Hover over"), mění barvu po najetí myši, po kliknutí, a po změnění volby zpátky na barvu původní.
V Menu po vybrání tlačítka nástroj Panel se šířkou 1 je viditelný pouze vedle zvoleného tlačítka
Po kliknutí na tlačítko v hlavním menu např.(News) se změní pouze obsah na pravé straně.
To je dosaženo stejnou velikostí formuláře jako je velikost ¨panelChildForm¨ a kodovaním které zobrazí formulář - 
v obsahu panelu.
**********
