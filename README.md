# SheetWright 1.0.3

SheetWright is an offline, system agnostic, sheet builder and character sheet. 

## SheetWright App vs. SheetWright Sheet
When you download this project, the HTML files called "Sheetwright Vx.x.x" is the SheetWright App. The app is used to build templates, and then export that template as a SheetWright Sheet. This outputted sheet can blank, partially or fully filled in, or have default values.

The SheetWright Sheet is what should be sent to players. This is a lighter file, and doesn't inherently allow for editing format. However, the contents of the sheets can be fully edited by a player. If a player wants to create a custom format for their sheet, they can open it using the SheetWright App, and make the required changes. When they export, the new character sheet will maintain their previous contents (As long as the widgets weren't deleted), and match the new format.

## Using a SheetWright Sheet In Browser
Sheetwright can be used in (probably) any browser by simply opening it using the browser of your choice. When you open a sheet in the browser, there is a "Connect File..." button in the top corner. Click this button and find the same sheet you just opened and select it. The button will now be replaced with a green text box displaying the name of the file. This should only be required once per browser per sheet, and is a requirement due to browser security settings. Changes will be automatically saved and pushed, so changes can be viewed live if you have it open in multiple ways at once.

## Using a SheetWright Sheet In Obisdian
SheetWright was built to be used in Obsidian, and has many features that are Obsidian specific. In order to use a SheetWright sheet to its full capability, use the following steps:
1. Move the SheetWright Sheet into your vault
2. In Obisidan Settings, go to Files and links. Under the Links header, click on "Show all file types". Your sheet should now be visible in your vault.
3. In Community Plugins, search for and install HTML Reader by Nuthrash. Open the HTML Reader settings and change "Operating Mode" to "Unrestricted Mode". This mode allows for the scripts in the Sheetwright Sheet to operate while open in Obisdian. DO NOT open untrusted HTML files in Obsidian, as they may be dangerous to your system.

## Updating a SheetWright Sheet
I fully expect (and am currently working on) additional versions of SheetWright that will fix bugs, improve speed, provide QOL, and additional features. If you want an existing SheetWright sheet to be updated to the latest version, all you need to do is open it in the SheetWright App and reexport it. It will automatically update the code and keep your contents.
