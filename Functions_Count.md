Easy
```c
int count_vowels(char const *str);
```
    * Count the number of vowels in a string.
    * Example :
        * str = "Hello, World !"
        * -> 3

```c
int count_consonants(char const *str);
```
    * Count the number of consonants in a string.
    * Example :
        * str = "Hello, World !"
        * -> 7

```c
int count_digits(char const *str);
```
    * Count the number of digits in a string.
    * Example :
        * str = "Hello, World !"
        * -> 0
        * str = "Hello, World ! 123"
        * -> 3
```c
int count_alpha(char const *str);
```
    * Count the number of alphabetical characters in a string.
    * Example :
        * str = "Hello, World !"
        * -> 10
        * str = "Hello, World ! 123"
        * -> 10


Medium

```c
int count_occurences(char const *str, char const *to_find);
```
    * Count the number of occurences of a substring in a string.
    * Example :
        * str = "Hello, World !"
        * to_find = "o"
        * -> 2
```c
int count_word(char const *str);
```
    * Count the number of words contained in a string
    * Example \:
        * str \= \"My name is Marvin\.\"
        * \-\> 4
        * str \= \"My\_name\_is\_Marvin\.\"
        * \-\> 1
```c
int count_vowel_tab(char const **array);
```
    * Take a string and return the total number of vowels in all the substrings.
    * Example :
        * array = ["Hello", "World"]
        * -> 3
```c
int count_digit_tab(char const **array);
```
    * Take a string and return the total number of digits in all the substrings.
    * Example :
        * array = ["Hello", "World", "123"]
        * -> 3

```cpp
int all_tab_len(char const **array);
```
    * `1`
    * Take a string and return the total number of chars in all the substrings\.
    * Example \:
        * array \= \[\"Hello\"\, \"World\"\]
        * \-\> 10

Hard

```c
int count_letter_tab(char const **array, char const *to_find);
```
    * Take a string and return the total number of a specific letter in all the substrings.
    * Example :
        * array = ["Hello", "World"]
        * to_find = "o"
        * -> 2
        * array = ["Hello", "World"]
        * to_find = "le"
        * -> 4

```c
int count_advanced(char const *str, int (*fcmp)(char));
```
    * `1`
    * Count the number of characters in a string that match the function pointer\.
    * Example \:
        * str \= \"Hello\, World !\"
        * fcmp \= is\_digit
        * \-\> 0
        * str \= \"Hello\, World ! 123\"
        * fcmp \= is\_digit
        * \-\> 3
```c
