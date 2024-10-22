Easy

```c
char *word_to_upper(char *str);
```
    * `7`
    * Put all the words in uppercase
    * Example \:
        * str \= \"Hello, World !\"
        * \-\> \"HELLO, WORLD !\"
```c
char *word_to_lower(char *str);
```
    * `7`
    * Put all the words in lowercase
    * Example \:
        * str \= \"Hello, World !\"
        * \-\> \"hello, world !\"
```c
char *str_to_capital(char *str);
```
    * `7`
    * Put the first letter of each word in uppercase
    * Example \:
        * str \= \"hello, world !\"
        * \-\> \"Hello, World !\"

Medium

```c
char *insert_string(char *dest, char const *to_insert, int index);
```
    * `7`
    * Insert `to_insert` at the `index` given in the `dest`
    * Example \:
        * dest \= \"Hello \!\"
        * to\_insert \= \"\, World\"
        * index \= 4
        * \-\> \"Hello\, World \!\"
```c
char *replace_char(char *str, char to_replace, char replace_by);
```
    * `7`
    * Replace all `to_replace` by `replace_by` in `str`
    * Example \:
        * str \= \"Hello, World !\"
        * to\_replace \= \',\'
        * replace\_by \= \'.\'
        * \-\> \"Hello. World !\"


Hard

```c
int **tab_to_int(char const **array);
```
    * `7`
    * Take a string and return a table of
    * Example \:
        * str \= ["4", "8", "15", "16", "23", "42"]
        * \-\> [4, 8, 15, 16, 23, 42, NULL]
 
