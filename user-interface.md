User Interface
==============

<!-- toc -->

## Main Window

![](/assets/user-interface.png)

### Diagram Area

*Diagram Area* shows the currently selected diagram.

### Sidebar

*Sidebar* is the area left containing *Working Diagrams* panel and *Toolbox*.

To show or hide *Sidebar*, press `Ctrl+1` or check (or uncheck) **View | Sidebar** in Menu Bar.

### Working Diagrams

*Working Diagrams* panel shows a list of the opened working diagram. The selected diagram is shown in the *Diagram Area*.

### Toolbox

*Toolbox* shows elements which can be created in the selected diagram.

To create an element:
1. Select an element in Toolbox
2. Mouse down on the Diagram Area and then drag as the size of the element to be created. If the element is a kind of relationship, connect two elements by drag and drop.

To show or hide *Toolbox*, press `Ctrl+5` or check (or uncheck) **View | Toolbox** in Menu Bar.

### Navigator

*Navigator* is the right area containing *Model Explorer* and *Editors*.

To show or hide *Navigator*, press `Ctrl+2` or check (or uncheck) **View | Navigator** in Menu Bar.

### Model Explorer

*Model Explorer* shows the tree structure of model elements.

You can find an element quickly by search box.

To change the order of elements:
1. Select the **Model Explorer Settings** menu in the right up corner of **Model Explorer**.
2. Select one of the sorting types
   - Sort by Added
   - Sort by Name

To show or hide stereotypes in front of element name by check of uncheck **Show Stereotype Text** in the **Model Explorer Settings** menu.

### Editors (Holder)

Editors (Holder) contains editors to edit properties of model and view elements. It includes *Style Editor*, *Property Editor*, and *Documentation Editor*.

To show or hide *Editors*, press `Ctrl+6` or check (or uncheck) **View | Editors** in Menu Bar.

### Style Editor

*Style Editor* allows to edit styles of selected view elements.


### Property Editor

*Property Editor* allows to edit properties of selected model elements.

### Documentation Editor

*Documentation Editor* allows to edit documentation property of a selected model element.

### Toolbar

*Toolbar* shows tool buttons typically provided from default or installed third-party extensions.

To show or hide *Toolbar*, press `Ctrl+3` or check (or uncheck) **View | Toolbar** in Menu Bar.

### Bottom Panel

*Bottom Panel* is a panel shown below *Diagram Area* typically provided from default or installed third-party extensions including *Find Results*, *Diagram Thumbnails*, *Validation Results*, *Markdown Editor* and etc.

### Statusbar

To show or hide *Statusbar*, press `Ctrl+4` or check (or uncheck) **View | Statusbar** in Menu Bar.


## Dialogs

### Font Dialog

Font Dialog allows to edit font style, size and color for view elements.

![](/assets/font-dialog.png)

### Color Dialog

Color Dialog allows to edit fill or line color for view elements.

![](/assets/color-dialog.png)

### Element Picker Dialog

Element Picker Dialog allows to select an model element from all model elements shown in tree structure. Checking **Do not specify** means nothing selected.

![](/assets/element-picker-dialog.png)

### Element List Picker Dialog

Element List Picker Dialog allows to select an model element from a given list of model elements. Checking **Do not specify** means nothing selected.

![](/assets/element-list-picker-dialog.png)

### Element List Editor Dialog

Element List Editor Dialog is used when user need to select a list of model elements. It allows to add or remove elements from the list and also to modify the order of elements by move up and down.

![](/assets/element-list-editor-dialog.png)

### Print Dialog

Print Dialog allows to configure how to print.

* Print Rage : Select whether all diagrams to be printed or the current diagram to be printed.
* Page Layout : Select page layout is landscape or portait.
* Page Size : Select a proper page size 
* Show Diagram Name : Select whether diagram name to be printed or not.

![](/assets/print-dialog.png)

### Preferences Dialog

Preference Dialog allows to set preferences. Left area shows preference schemas which contains a set of preference items. When you select a preference shema in the left area, then all preference items are shown. If you want to restore default settings, Select **Restore Default Settings** button in the most bottom.

![](/assets/preferences-dialog.png)

### Extension Manager Dialog

Extension Manager Dialog allows to install or uninstall extensions from Extension Registry. While **Registry** tab shows all available extensions, while **Installed** tab only shows the installed extension in local.

If you want to install an extension directly from Github URL, Select **Install From Url...** and enter the extension's url.

![](/assets/extension-manager-dialog.png)
