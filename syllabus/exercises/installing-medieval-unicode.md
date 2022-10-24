# Installing Medieval Unicode

Our word _alphabet_ comes from the names of the first two letters of the Greek alphabet (alpha + beta). In Latin, the alphabet was called an _abecedarium_ (A, Be, Ce, D -arium) from the names of the first four letters in the Latin alphabet. Transcribing medieval documents however requires us to recognize many more characters than the twenty-six letters used in modern English.

Transcribing by hand means that you can approximate unfamiliar characters while you are working through a draft transcription. A digital transcription that retains the characters/ glyphs of the original text, however, is more difficult, as you will need to use a special characters atypical in modern usage/ typical keyboard set up. Two decades ago, there was not an option to use non-standard Latin characters on your computer, but in the past decade we have seen considerable advances in establishing standards for a wider range of characters (in the Latin alphabet, but also in Runic and non-Western alphabets). We will access these characters in [**unicode**](https://en.wikipedia.org/wiki/Unicode\_input). We can thank a small group of dedicated scholars who founded the Medieval Unicode Font Initiative ([MUFI](https://folk.uib.no/hnooh/mufi/)), which has set out to make a diverse range of manuscript characters reproducible digitally.

To get a sense of what unicode is, take a look at this resource, [Decode Unicode](http://decodeunicode.org/).

Setting up your computer to use unicode and have access to historical fonts takes a few steps, but is straightforward. To use unicode for medieval scripts, however, is a bit more arcane; you might feel like you're a codebreaker trying to crack the Enigma device. As part of this process, we'll put together a list of the most typical characters you'll use in transcribing your folios.

For this exercise, it pays to have a standard word processor that easily allows you to choose what font you want to use. While students at Carleton, you all can use Microsoft Word at no charge, so in the interest of standardization, I encourage you all to [download a free copy](https://carleton.ca/its/ms-offer-students/) if it is not already set up on your computer.

To use medieval characters in your transcriptions, consult the the [online MUFI Code Chart](https://mufi.info/m.php?p=muficodechart) and install a suitable font (instructions below). Like Capelli's guide to medieval abbreviations (which you will be introduced to soon), these allow you to choose specific characters to match what you see on the page. Before you can use them, however, you will need to get set up to use unicode.

### Setting up Unicode to run on your machine <a href="#setting-up-unicode-to-run-on-your-machine." id="setting-up-unicode-to-run-on-your-machine."></a>

1. Set up your device to use unicode. On my Mac, I first enabled Unicode Hex Input in System Preferences -> Keyboard -> Input Sources. The wikipedia article on [unicode](https://en.wikipedia.org/wiki/Unicode\_input) outlines how to enable unicode on different platforms.&#x20;

{% hint style="info" %}
You can key unicode hex input directly into any application in Mac OS X. I’ll explain how, assuming that you are using default keyboard settings.&#x20;

First, I’ll briefly review how to produce an accented letter in a western language: In the normal, default U.S. or Canadian English situation, holding _option_ down while tapping certain keys (e or i or u, for example) remembers an accent (such as ´ or ˆ or ¨ respectively) but makes no mark. The immediately following keystroke (typically a vowel) produces an accented letter (providing the particular letter keyed is capable of taking the particular accent).&#x20;

Perhaps you know the Unicode code point for a particular character, such as U+03B1 for Greek lowercase alpha (α). The _Unicode Hex Input_ method allows keying such a code directly. First, make sure that Unicode Hex Input is enabled. Under the Apple menu (at the left of the menu bar), choose System Preferences…, then choose Keyboard. Make sure there’s a check in the box to the left of “Show Keyboard & Character Viewers in menu bar”: This will display a flag (or flag-like) icon near the right-hand end of your menubar. Then choose Input Sources… to access the preferences for Language & Text. Near the bottom of the (long) scrolling list, place a check next to Unicode Hex Input, and at the bottom right, make sure there's a check next to “Show Input menu in menu bar.” Close the System Preferences window. Now, return to the application you're interested in, and look at the right end of the menu bar for a flag. Pull down that menu; Unicode Hex Input will now be one of the choices.&#x20;

Choosing the Unicode Hex Input method alters the behaviour of the “option” key. To place U+03B1 into your document, hold down the option key and – while holding it down – tap the four keys 0, 3, b, and 1 in sequence. On pressing the last of the four, the character α appears; you can then release the option key. To return to the normal option-key behaviour, access the “flag” menu and choose your usual input method.&#x20;

With default keyboard settings, you can now switch input methods by holding Command (⌘), tapping the spacebar one or more times until the desired method is selected, then releasing the Command key.
{% endhint %}

1. Download a font that will allow you to use medieval unicode features (a much wider base of characters than one normally uses) from [options](https://folk.uib.no/hnooh/mufi/fonts/index.html) suggested by MUFI. I would suggest you download and install the [Andron](https://folk.uib.no/hnooh/mufi/fonts/Andron/AND\_SCR\_WEB\_3.0.zip) font, but [Junicode](http://junicode.sourceforge.net/) and [Titus](http://titus.fkidg1.uni-frankfurt.de/unicode/tituut.asp) also work well.
2. It should be as easy as double clicking on the file(s) to add them to a Mac or Windows computer. If you are using Linux, in takes a few more [steps](https://askubuntu.com/questions/3697/how-do-i-install-fonts).
3. Open up a word processor and after selecting the font you have installed, attempt to type some medieval characters, many of which can't be reproduced in markdown (and thus can't be shown here).
4. With the option key held down, type EEC5. This should input a small ligature ct (i.e. a c and t together linked by a little curvy pen flourish).
5. You should see something that looks like "đ" (a small letter d with cross stroke), if you hold down the option key and type "0111".
6. Looking through the two MUFI code books you have downloaded, look for and try out other characters. Not all characters will be the same as indicated in the codebook (some fonts like Junicode, were completed before the most recent standards were set).

### Working with MUFI unicode <a href="#working-with-mufi-unicode" id="working-with-mufi-unicode"></a>

1. By this class, you should already have started a handwritten transcription of your folio. Your goal now is to write out at least 10 lines as an abbreviated text using the now available (to you) unicode characters. Go!
2. Assign a number to each line of your text and transcribe the words/ characters line by line. It will take some time to find matching character in the unicode codebooks, but it will help you discern what is going on.
3. Post the completed file in your folder on Teams as a Word document (.docx) or .pdf, named "LastName-MsX-UnicodeTranscription" (where LastName is replaced by your last name, and MsX is replaced the name and number of your folio – e.g. Ottawa CU ARC ms. f. x).
