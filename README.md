# showfunc
Search for functions in your code

This is a vim plugin, which allows for easy searching for function definitions.

## Commands

    :ShowFunc
    
Display all functions in currently edited file. Use `n` and `N` to jump back and forward between functions.

    :ShowFuncAll
    
Display all functions across open buffers. Use `:copen` to show quickfix list with a list of functions.


This plugin reuses regexes found in <https://github.com/tacahiroy/ctrlp-funky>, created by <https://github.com/tacahiroy>.
