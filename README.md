ANAGRAM
=======

## Anagrams Detection

An **anagram** is a type of word play, the result of rearranging the letters of a word or phrase to produce a new word or phrase, using all the original letters and symbols exactly once (except whitespace).

For example, "admirer" can be rearranged into "married", "AstroNomers" to "no more stars" (you can see that we ignore capital letters in this task).

In the following task you should implement a function `isAnagram($string1, $string2)` that returns `TRUE` if two input strings form anagrams of each other, otherwise `FALSE`. Also, return `FALSE` in a case of invalid inputs. It's allowed to use as many additional functions and structures as needed.


You can put your code directly to the form, or give us GitHub link or any other downloadable URL.


Installation
------------

Download or clone repository:

    $ git clone https://github.com/vukanac/game-anagram.git

Install required libraries:

    $ composer install


Example of use
--------------

    $string1 = 'AstroNomers';
    $string2 = 'no more stars';

    $game = new \Game\Anagram();
    $wordIsAnagram = $game->isAnagram($string1, $string2)

    if ($wordIsAnagram) {
        echo "The word `$string2` is an anagram of the word `$string1`
    } else {
        echo "The word `$string2` is not an anagram of the word `$string1`
    }

