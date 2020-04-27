# Coptic CS2UTF-8 Converter
Coptic unicode conversion
## Brief outline of typing Coptic before computers
Coptic was first typed in the 19th century, then by the 20th century coptic language typewriters started to emerge for academic purposes. Coptic typerwriters followed QWERTY standard, applying it to Coptic possibly for ease of use. Also, there were not statistical analysis to the frequency of use of each letter done _aka a coptic equivalent of QWERTY_. This tradition of applying QWERTY values to Coptic keyboard
## Coptic language on computers
### Transliteration
The first form that appeared was transliteration based on orthography, which was letter by letter specific. This appeared circa 1992. This is an example of alphabet in Copt-Net transliteration  `a, B, 5 , d, E, e, Z, H, 8, I, K, ^, M, N, 3, O, n, P, C, T, Y, Q, X, +, W, y, q, J, 2, G, 6, t`; example of text: `taCnI 'NPEM'NXHMI OYaCnI 'NanaC TE NIPEM'NXHMI AYCaGI 'MMOC`
[Copt-Net](http://www.coptic.net/CopticWeb/Contributions/Anonymous%20-%20CopticAlphabet.html)
###  First generation fonts
#### Non-standardised fonts
The first generation of fonts were essentially Coptic letters based on English language. The computer receives this as English language, but the font displayed was Coptic. This created a problem with word processors that attempt auto-correct based on English language standards. Also, they were not standardised so, if one does not have this specific font. The whole text appears as English language.
##### Problems with non standardised fonts
1. The main problem rose from the lack of a unified keyboard mapping due to different goals on making keyboard mappings, some had the intention of using it in ecclesiastical purposes, others to write manuscripts, others to scan manuscripts.
Moving a document from a font to another font requires enormous effort in working with macros etc.
2. Incapability of reading and destruction of documents sometimes is inevitable
A typist has to learn a new keystroke system with every new font he installs. No professional typists in the field.
3. To preserve a document one has to make it a picture file (*.jpeg) which is impractical for production scale and handling.
4. Lack of distribution of Coptic software, and fonts render thinking about Coptic as a PC hostile font.
Problems developing advanced applications using such technologies such as XML, saving text to databases.
Lack of communication among font makers, and lack of observation of each font. Lack of unity results in more separation, leading to disastrous font development.
### Coptic Standard fonts
A Standard has been decided on and a sample Coptic Font has been produced.
Using the Coptic Standard Font Standard arrangement, one can type all Coptic Letters (including letters in Achmimic Dialect) in almost a totally pronunciation based system that facilitates both typing & education. Also, all types of djinkims Bohairic, Sahidic, Achmimmic could be written. Arabic numerals, simple mathematical marks & modern punctuations are present.  Ecclesiastical common abbreviations are present on Alt keys. Coptic Church project created a converter to help the converssion from non-standardised fonts to standardised ones. _credits_ [CopticChurch.net](http://copticchurch.net/coptic_fonts/)
#### Problems with Coptic Standard fonts 
1. Coptic standard (CS) fonts only standardised keyboard mapping, they still relied on having the exact font to display coptic correctly 
2. CS fonts work on top of English language encoding, which would not work on Markdown, text files, social media platforms
3. Word processors handle CS fonts as English and hence auto-correct is set to English language
### Coptic Unicode
When UTF-8 emerged and Coptic blocked appeared all previous attempts became redundant.
### This project CS2UTF-8
This is an HTML converter from Coptic Standard fonts to Coptic Unicode encoding. One can paste text in CS font on the left panel of the HTML file, press convert, the converted text appears on the right panel. The outcome could be copied and pasted on the document/webpage one intends to use on. _Credits_ The HTML code was created by [Hosam Adeeb Nashed](hosadeeb@gmail.com)
