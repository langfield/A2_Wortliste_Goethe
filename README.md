# Installation

You'll need a `python3` distribution installed on your machine. Unfortunately, `ki` is not tested on anything other than Debian. It may work on MacOS, and probably does not yet work on Windows.

### Dependencies

* `git`

```bash
pip install anki-ki
ki clone <collection_path>
cd collection
git submodule add https://github.com/langfield/A2_Wortliste_Goethe
git commit -m "Add submodule 'A2_Wortliste_Goethe'"
ki push
```

# Description

When I started to learn German I figured, that there is quite some material out there, but not really available in Anki. So I started to move material to Anki and enrich it there for optimized learning. This deck is basically an Anki import of the wordlist from Goethe Institute for German level A2. It includes all the vocabularies and the sentences to each vocabulary to describe the different meanings, enriched with audio from duden.de, yandex.ru and some translations from google.com. It starts with the letter A in the wordlist, the other information before that is not included in the deck.

The original A2 wordlist can be found here:
https://www.goethe.de/pro/relaunch/prf/en/Goethe-Zertifikat_A2_Wortliste.pdf

Tools

The following tools have been used beside Anki to create the deck, thanks!
duden.de to create the audio of most of the words
dict.leo.org to clarify some English translations
yandex.ru to create the audio
translate.google.com to translate the sentenses
AwesomeTTS Plugin https://ankiweb.net/shared/info/301952613
Advanced Browser https://ankiweb.net/shared/info/874215009

Known Limitations

I checked the meaning of the English translation of the vocabulary by hand, but still I am sure there will be quite some errors to be found, in case you are not sure ask a native or at least consult dict.leo.org. The translation of the sentences is only to give a feeling; I didn’t check it at all. The audio sometimes reads numbers and special characters in a wrong way, but it is quite seldom, so no big need to correct it. Sometimes there are two sentences, half-sentences or two vocabularies together and this shouldn’t be, sorry for that. Please feel free to add more corrections as time moves on. If you want to post some corrections below feel free to do so but please add the order_number from the note, then I can easily import and fix it. 

Additional Information

I wanted to create a deck where part of the sound is played automatically and part not. This was finally achieved by putting a long invisible silent sound in front of the sounds I don’t wanted to be auto-played, for example <div style="display:none">[sound:_LongSilence.mp3]</div>

# Credits

This deck was created by an anonymous author on AnkiWeb. Their content can be viewed [here](https://ankiweb.net/shared/byauthor/1386119660).

