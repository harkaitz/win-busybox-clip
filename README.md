COMPATIVILITY SCRIPTS - COLLECTION 1
====================================

Compativility wrapper collection.

## Help

clip-copy

    Usage: clip-copy < TEXT > TEXT
    
    Read from the standard input and put it in the clipboard.
    
    Supports: clip.exe (windows) xclip (Xorg).

clip-template

    Usage: clip-template TEXT
    
    This program first prints the TEXT removing the first and last
    lines. This text should contain some numerated fields in the
    following form: (NN)[FIELD]
    
    The program asks for input interactively, then it searches it
    in the text and if found places it in the clipboard.

create-shortcut

    Usage: create-shortcut [OPTS...] PROGRAM ARGS...
    
    Create shortcut in "/usr/share/applications" (GNU/Linux) and
    desktop (MS Windows).
    
        -n NAME       : Shortcut name.
        -m COMMENT    : Add comment.
        -c X-Category : Set category (GNU/Linux). 
        -t            : Open terminal (GNU/Linux).
    
    TODO: Icon.

## Collaborating

For making bug reports, feature requests and donations visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)
