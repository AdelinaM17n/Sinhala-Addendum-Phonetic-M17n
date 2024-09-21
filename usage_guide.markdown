# Sinhala Addendum Phonetic Input Method : Usage Guide
If you are familiar with typing "Singlish" (Romanized/Transliterated Sinhala), it shouldn't be too dificult for you to get hang of this input method.
But due to various limitations, there are slight differences in the tranliteration scheme used in this input method compared to how people would naturally transliterate (with pre-nasals, or aspirates for example)

## Vowels 
Any vowel letter at the start of a word should be inputted in its letter form, while if you type a vowel letter after a consonant, it should trigger the respective vowel diacritic.


| Input Chars   | Output Chars | Special notes                                                                                                       |
|---------------|--------------|---------------------------------------------------------------------------------------------------------------------|
| a             |  අ           |                                                                                                                     |
| aa            | ආ            | Uppercase `A` is reserved for the `æ` sound                                                                             |
| A / ae        |  ඇ           |                                                                                                                     |
| AA / Aa / aee |              |                                                                                                                     |
| i             |  ඉ           |                                                                                                                     |
| ii / I        | ඊ            |                                                                                                                     |
| u             |  උ           |                                                                                                                     |
| uu / U        | ඌ            |                                                                                                                     |
| o             |  ඔ           |                                                                                                                     |
| oo / O        | ඕ            | I assigned `oo` to be the long form of `o` instead of the long form of `u` like in colloquial usage for consistency |
| au            | ඖ            |                                                                                                                     |
| e             |  එ           |                                                                                                                     |
| ee / ee       | ඒ            | I assigned `ee` to be the long form of `e` instead of the long form of `i` like in colloquial usage for consistency |
| ai            | ඓ            |                                                                                                                     |
| Ru            | ඍ            | For inputting the diacritic associated with this letter, you need to type `ru`                                      |
| Ruu           | ඎ            | For inputting the diacritic associated with this letter, you need to type `ruu`                                     |

## Consonants
With consonants, if you are familiar with the general romanization scheme people abide by when typing romanized Sinhala, you should be most of your way there. 
But there are few ways where this differs from it, and few quirks to be aware of.
- You can input the vowel diacritics for a consonant by inputting the appropriate roman characters for the vowel (refer to the above table) after the consonant
- The inherent vowel is not assumed, you need to explicitly type it. That is to say that consonants by default will be inputted with a hal-kirima/viraama
- Pre-nasals are inputted with the format `n + [Uppercase of the pre-nasalised consonant]`
  - For example `ඳ් -> nDh`, `ඬ් -> nD`, `ඟ් -> nG`
  - ඹ් can also be inputted with `mBa`
- Aspirates can be typed in two different ways, either by inputting `H` after the consonant, or inputting uppercase letters for the consonant.
  - Inputting `H` the consonant is the prefered way, as it has no conflicts with the other mappings. The uppercase letters may trigger a pre-nasal if inputted after `n`
- Inputting `r` or `y` after a pure consonant will trigger a ligature (yansha/rakaransha), if you want to input the characters mapped to those letters without triggering a ligature, input uppercase `R` or `Y`
  - inputting `ru` or `ruu` after a pure consonant will instead input the `ru`/`ruu` vowel diacritic
  - No ligatures will be formed if the preceeding character is also `y` or `r`
    
#### Misc Ligature info
- `ක්‍ෂ‍්` can be inputted with `Ksh`
- `z` key inputs hal-kirima + ZWJ, allowing you to manually form ligatures/conjuncts
- `Z` key inputs  ZWJ + hal-kirima, allowing you to form touching letters (similar to `ක්‍ෂ‍්`)

#### Base Consonant Mappings
| Input Char | Output |
| ---------- | ------ |
| k          | ක්     |
| ch         | ච්     |
| t          | ට්     |
| th         | ත්     |
| p          | ප්     |
| g          | ග්     |
| j          | ජ්     |
| d          | ඩ්     |
| dh         | ද්     |
| b          | බ්     |
| n          | න්     |
| N          | ණ්     |
| xN         | ඤ්     |
| m          | ම්     |
| y          | ය්     |
| r          | ර්     |
| l          | ල්     |
| v / w      | ව්     |
| sh         | ෂ්     |
| Sh         | ශ්     |
| h          | හ්     |
| L          | ළ්     |
| f          | ෆ්     |

#### Aspirate Mappings
| Base Input | Output |
| ---------- | ------ |
| kH / K / C | ඛ්     |
| chH / Ch   | ඡ්     |
| tH / T     | ඨ්     |
| thH / Th   | ථ්     |
| pH / P     | ඵ්     |
| gH / G     | ඝ්     |
| jH / J     | ඣ්     |
| dH / D     | ඪ්     |
| dhH / Dh   | ධ්     |
| bH / B     | භ්     |

#### Pre-nasal mappings
| Base Input | Output |
| ---------- | ------ |
| nG         | ඟ්     |
| nD         | ඬ්     |
| nDh        | ඳ්     |
| nJ         | ඦ්     |
| mB / nB    | ඹ්     |
