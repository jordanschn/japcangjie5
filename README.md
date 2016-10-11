# japcangjie5
Cangjie for Japanese.

----------------
How to install:
----------------

Download and isntall RIME:
http://rime.im/

Go to %AppData%\Roaming\Rime.

Copy and paste the files from this repository into this folder.

Go to 輸入法設定.

Select 和倉頡五代.

------
Notes
------

This is an IME (Input Method Editor) to create a shape-based input method Japanese that uses Cangjie (倉頡輸入法). Although there have been shape-based inputs for Japanese in the past, many of them aren't available any more and none of them have been popular. Cangjie, however, is widely used by the Chinese community to input characters without having to know pinyin.

What do I mean by shaped-based input?

Every button on the keyboard is mapped to a "shape":
a = 日
b = 月
c = 金
etc.

To create characters, you simply decompose the shape of the character:
晶 = 日 + 日 + 日 = aaa
明 = 日 + 月 = ab

This has the benefit of forcing you to remember how to write characters, and you can write characters you know how to write, but not how to pronounce.

If you want to know more about Cangjie, you can read about it here:

https://en.wikipedia.org/wiki/Cangjie_input_method

There's a few quirks about the IME that you need to get used to:
You type 仮名 using ローマ字. Use lower case for 平仮名; upper case for 片仮名.
Use Shift + Space to type full width characters.
Use Ctrl + Space to type the Latin alphabet (alphanumeric mode).
Priority is given to 仮名. If a code can represent a 仮名, that will be first on the candidate list, then any 漢字.
You can append a ; (semicolon) to the end of a code to give priority to 漢字.

For example: 'a' + (Space) will output あ, but 'a' + ';' + (Space) will output 日. 

----------
Questions
----------

If you have any questions, feel free to email me at:
jordanschn@outlook.com
