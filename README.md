# Config my Atom Text Editor
Script to have ready my favorite editor

## Packages to install:
	apm install todo-show color-picker emmet minimap atom-beautify linter jshint atom-jade linter-jade jade-autocompile jade-beautify file-icons highlight-selected minimap-highlight-selected autoclose-html atom-alignment uglify angularjs javascript-snippets angularjs-styleguide-snippets css-snippets jade-snippets jquery-snippets

## Ignored Names:
	.git, .hg, .svn, .idea, .DS_Store, ._*, Thumbs.db, .codekit-cache, bower_components, node_modules	

## Project Home:
	C:\apps\

## Add to keymap.cson (Emmet and Markdown issue):
	'.editor:not(.mini)':
	  'ctrl-shift-M': 'markdown-preview:toggle'
