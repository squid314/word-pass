Word-Pass
=========

Super simple word-based password generator inspired by xkcd.com.

Usage
=====

    ./word-pass [count]

Selects `count` (default 4) random words from its dictionary and prints them. These words should be used as a password, a la `correct horse battery staple` or `CorrectHorseBatteryStaple`.

Diagnostic info is also printed, specifically, the number of items in the dictionary used and the approximate entropy (base 2) provided by using that many random words from the dictionary (measure of the password strength).
