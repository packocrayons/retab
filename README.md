# Retab

Use tabs instead of spaces or the wrath of retab will find you.

## Usage:
    
    retab FILENAME [NEWFILE]

If no new file is provided, it will be modified in place.

## When pasting into a tabbed document

Retab will ignore any line beginning with a tab, so snippets can be pasted into an already tabbed document and retab can be run on them.

Note - however, that retab uses the first line it finds with a space as the basis, so any existing space-prepended lines will be tabbed in and used.
