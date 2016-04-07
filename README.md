# MC3
A lightweight Craftingcalculator for Minecraft or any other Crafting game

This program is in beta now most features have been added.

To use this program you need an Itemfile or make a new one your self. Place a Directory called "Materialslists" in the same directory as the .exe file. Place Itemfiles in this Directory. It is recommended to call the Itemfile something like: "Vanilla_1.x.txt"

To add an Item to your Itemfile you can use the "Add new Item" Tab. Enter a Name or choose a missing Item from the dropdownmenu add an ItemID (It is recommended to use the IngameID but that is not neccessary). Add an Output quantity for example 1 peace of Wood gives 4 Planks. Add a stacksize. If the material is a Rawmaterial check the box. If it is not a raw material add anew Material or use a previus added item the quantity needed to produce 1 itteration of the recepe. Click "Add Item" to just Add the Item to the internel List. "Save List" to save the Internel list to an Itemfile. Click "Add Item Save File" to first add the Item to the list and then save the list.

To Calculate a product you have to specify all items, that the dropdown list "Name" in the "Add new Item" tab is empty.

You choose a product from the dropdownmenu and specify a quantity. After this you hit "Calculate and Save". The Materials will be calculated and put out in the Textbox and saved to "/user/documents/Minecraft Crafting Calculator/<quantity><Itemname>"


Planed features:

-Mearge Itemfiles funktion
-compare Itemfiles before mearging to prevent double entries and abort mearging when Entries with same Name or id are different.
-Change Item entries



Version History:

Beta 0.5
-Fixed Bug where the calculation did not deliver the right results
-Added File -> Save Itemfile
-Added File -> Calculate and Save
-Added Project to GitHub
