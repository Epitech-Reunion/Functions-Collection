```c
void info_file(char const *path);
```
    * `7`
    * Display information about a file
    * Example :
        * path = "Functions_File.md"
        * -> [NAME]: [SIZE] bytes [User]: [GROUP] [RIGHTS]
```c

void display_info_folder(char const *path);
```
    * `7`
    * Display all the files in a folder
    * Example :
        * path = "."
        * -> [NAME] [SIZE] bytes [User]: [GROUP] [RIGHTS]
        * -> [NAME] [SIZE] bytes [User]: [GROUP] [RIGHTS]
        * ...

