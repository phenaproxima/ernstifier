# ernstifier

A unique code uglifier for PHP that replaces many symbols with random strings, prefixed with "ernst_".

At the moment, this only replaces variable names (except argc and argv) and function names with ernst_XXXX. Eventually I hope to add support for object-oriented code.

## Why "ernst"?
Once upon a time at an agency we had a client called Ernst and for no particular reason at all, I decided that any time he wrote code, he would name all of his variables Ernst. This became the little in-joke that could and I have wanted to write this script for a long-ass time. And finally I have.

## Does this work?
I ernsted the ernst script, and then ran it again on the original ernst script, and it ernsted it, and then that code ran too. So yes, it works. I'm usually pretty gung-ho about testing but recursive ernstification seems like a pretty good test case to me.

## Does this only work on PHP code?
Yup. If you want to port this to whatever language, you can write your own Ernstifier.

## How to use:
```
$ composer install
$ ./ernst path/to/some/php/file
```
