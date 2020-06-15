# fmQuill
FileMaker 19 web viewer integration with Quill.js

This integration allows you to create links between records. This would be useful for building a help system or wiki-like resource. It could be adapted so that links in Quill could run any type of FileMaker script.

There is a known bug that I'm trying to figure out...

If the web viewer has focus (for example if the cursor is in the editor or you click an inactive toolbar region first) when you open a card window, the web viewer reloads. This does not happen if the debugger is on. Halp!
