# todo-haskell

stack build --exec to-do-exe

stack build --fast --file-watch --exec to-do-exe
stack build --fast --file-watch --exec "to-do-exe view 0"

stack exec -- to-do-exe --data-path /path/to/data list
