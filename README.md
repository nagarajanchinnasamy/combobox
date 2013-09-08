combobox
========

iwidgets 4.0.1 combobox.itk improved...

New features/fixes done:

1. added a new option -casesensitive (boolean) to enable/disable case sensitive lookup in autocompletion mode
2. improved navigation within the components of the widget - for e.g., the arrow button is excluded from tab order
3. auto-completion shows matching items progressively. For e.g. if you have {test1 test11 test111} in the list and if you press t, it first shows test1. When you complete typing test1, it shows test11... and so on.
4. pressing backspace in auto-completion mode shows matching items progressively. For e.g. if you have {test1 test11 test111} in the list and if you press backspace when test111 is selected, it first shows test11. If you press backspace again, it shows test1... and so on.
5. Del key is supported in autocompletion mode. For e.g. if you have {test1 test11 test111} in the list and if you try to create a new entry that is "test", currently it is not possible as autocompletion will always show "test1" in the entry. With the support for Del key, you can delete the trailing portion of the autocompleted text using Del key.
6. Fixed bug: Up/Down arrow keys dont work when there is only one item in the dropdown
