# Custom Key Mapping

* This file is for custom key mapping. You can edit this file by selecting `Keymap...` from the `Edit` tab in Atom.
* The key maps below are mostly for the `emmet` package with one removed to not interfere with markdown preview

# keymap.cson
```
'atom-text-editor:not([mini])':
  'ctrl-e': 'emmet:expand-abbreviation'  
  'ctrl-shift-E': 'emmet:balance-outward'
  'ctrl-shift-0': 'emmet:balance-inward'
  'ctrl-alt-j': 'emmet:matching-pair'
  'ctrl-alt-right': 'emmet:next-edit-point'
  'ctrl-alt-left': 'emmet:prev-edit-point'
  'ctrl-shift-`': 'emmet:split-join-tag'
  'ctrl-shift-;': 'emmet:remove-tag'
  'ctrl-shift-Y': 'emmet:evaluate-math-expression'
  'alt-up': 'emmet:increment-number-by-01'
  'alt-down': 'emmet:decrement-number-by-01'
  'ctrl-up': 'emmet:increment-number-by-1'
  'ctrl-down': 'emmet:decrement-number-by-1'
  'alt-shift-up': 'emmet:increment-number-by-10'
  'alt-shift-down': 'emmet:decrement-number-by-10'
  'ctrl-shift-.': 'emmet:select-next-item'
  'ctrl-shift-,': 'emmet:select-previous-item'
  'ctrl-shift-R': 'emmet:reflect-css-value'
  'ctrl-u': 'emmet:update-image-size'
  'ctrl-\'': 'emmet:encode-decode-data-url'
  'ctrl-shift-\'': 'emmet:update-tag'
  'ctrl-alt-w': 'emmet:wrap-with-abbreviation'
  'ctrl-alt-enter': 'emmet:interactive-expand-abbreviation'
'atom-pane atom-text-editor:not([mini])':
  'ctrl-shift-/': 'emmet:toggle-comment'
'atom-pane atom-text-editor[data-grammar~="html"]:not([mini]):not(.autocomplete-active), atom-pane atom-text-editor[data-grammar~="xml"]:not([mini]):not(.autocomplete-active)':
  'enter': 'emmet:insert-formatted-line-break-only'
'atom-text-editor[data-grammar="text html basic"]:not([mini]), atom-text-editor[data-grammar~="erb"]:not([mini]), atom-text-editor[data-grammar~="jade"]:not([mini]), atom-text-editor[data-grammar~="css"]:not([mini]), atom-text-editor[data-grammar~="stylus"]:not([mini]), atom-text-editor[data-grammar~="sass"]:not([mini]), atom-text-editor[data-grammar~="scss"]:not([mini])':
  'tab': 'emmet:expand-abbreviation-with-tab'
```
