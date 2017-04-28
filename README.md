# Tool-cmd
Tool cmd shortcut documetation

## atom related
### Enable tab completion for JSX with Emmet in Atom
  emmet and language-babel packages already installed in Atom.
  Open the keymap.cson file by clicking on Atom -> Keymap… in the menu bar.
  add following
  'atom-text-editor[data-grammar~="jsx"]:not([mini])':
  'tab': 'emmet:expand-abbreviation-with-tab'
