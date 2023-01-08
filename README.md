# same-name-bulk-folder-delete-windows
 FOR /r . %c IN ("feed") DO @IF EXIST "%c" rd /s /q "%c"
