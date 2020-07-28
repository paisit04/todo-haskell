# todo-haskell

stack build --exec to-do-exe

stack build --fast --file-watch --exec to-do-exe
stack build --fast --file-watch --exec "to-do-exe view 0"

stack exec -- to-do-exe --data-path /path/to/data list

stack exec to-do-exe -- add TITLE -d DESCRIPTION -p 2 -b "2010/08/21 12:00:00"
stack exec to-do-exe -- remove 0
