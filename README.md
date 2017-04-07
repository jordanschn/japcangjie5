# 和文倉頡 (japcangjie5)
Cangjie for Japanese.

----------------
How to install:
----------------

Download and install RIME:
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

Every button on the keyboard is mapped to a "shape": <br/>
a = 日 <br/>
b = 月 <br/>
c = 金 <br/>
etc.

To create characters, you simply decompose the shape of the character: <br/>
晶 = 日 + 日 + 日 = aaa <br/>
明 = 日 + 月 = ab 

This has the benefit of forcing you to remember how to write characters, and you can write characters you know how to write, but not how to pronounce.

If you want to know more about Cangjie, you can read about it here:

https://en.wikipedia.org/wiki/Cangjie_input_method

There's a few quirks about the IME that you need to get used to:

You type 仮名 using ローマ字. Use lower case for 平仮名; upper case for 片仮名. <br/>
Use Shift + Space to type full width characters. <br/>
Use Ctrl + Space to type the Latin alphabet (英数 mode). Pressing Ctrl + Space again will return you to 文字 mode. <br/>
Priority is given to 仮名. If a code can represent a 仮名, that will be first on the candidate list, then any 漢字. <br/>
You can add a ; (semicolon) to the beginning of a code to give priority to 漢字. <br/>
For example: 'a' + (Space) will output あ, but ';' + 'a' + (Space) will output 日. <br/>

Press = or + to type '々' （同の字点）. <br/>
Press / to type '・' (中黒). <br/>
Press , to type '、' (読点). <br/>
Press . to type '。' (句点). <br/>


----------
Thanks
----------

Thanks to Iotem (https://github.com/lotem) for his work on the schema and dict to output kana, which I have edited to use in this project.
Also a big thanks to the RIME team (https://github.com/rime).

----------
Questions
----------

If you have any questions, feel free to email me at:
jordanschn@outlook.com
