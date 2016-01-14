# MIT Pirahã Corpus

Version 1.0

## Overview

This corpus provides a transcription and word-by-word translation of 1149 sentences of Pirahã that were collected during fieldwork by Steve Sheldon and Dan Everett. Our goal is to provide primary linguistic data from Pirahã in a human- and machine-readable format that includes annotation of the lexicon, morphology, and syntax of the language.

See the publication "A Corpus Investigation of Syntactic Embedding in Pirahã" by Richard Futrell, Laura Stearns, Daniel L. Everett, Steven T. Piantadosi, and Edward Gibson in PLOS ONE.

This corpus is distributed under a Attribution-ShareAlike (CC BY-SA) license, allowing free modification and re-distribution of the corpus so long as derivative work is released under the same terms. You may disregard any comments in the source files to the effect that citation is limited.

## Data Sources

The majority of the texts are transcriptions of a single speaker describing an event.  Some dialogue appears at the beginning of the `Sept29amfx3` text.  `XigAbaI_almostbittenbysnake`, `Sept29amfx3`, and `panther` were recorded, transcribed, and translated by Daniel L. Everett.  All other texts were initially recorded, transcribed and translated by Steve Sheldon in the 1970s.  Some of the translations, word boundaries, and sentence boundaries have been since been edited to reflect the current best translation.  The original sentence translations have been preserved in the first of the two glosses given above each sentence, except for in `Katosbabyandthefire`, for which these first glosses reflect a 2009 translation by Daniel L. Everett.

### Dan Everett texts

These stories were originally translated by Dan Everett.

| Number | Speaker    | Date           | Transcriber   | Source file                              |
| ------ | ---------- | -------------- | ------------- | ---------------------------------------- | 
| 1 | Xaogioso (f)    | 1970s          | Steve Sheldon | `01 KATO'S BABY FALLS NEAR THE FIRE.pdf` |
| 2 | Xahoápati (m)   | c.a. 2000      | Dan Everett   | `02 XigAbaI almost bitten by snake.pdf`  |
| 3 | Kaioá (m)       | Sept. 29, 2009 | Dan Everett   | `03 Sept23AMFX3.pdf`                     |
| 4 | Xahoápati (m)   | July 28, 1980  | Dan Everett   | `04 panther.pdf`                         |


### Steve Sheldon texts

These texts were all collected in the 1970s and transcribed and originally translated by Steve Sheldon.

| Number | Speaker      | Source file                              |
| ------ | ------------ | -----------------------------------------|
| 5  | Itaibigai (f)    | `05 VISIT OF THE ANTHROPOLOGISTS.pdf`    |
| 6  | Tisahai (f)      | `06 APIBAI GOES, I STAY.pdf`             |
| 7  | Maigiphoasi (f)  | `07 BIRTH OF PE'S BABY #2.pdf`           |
| 8  | Kaboibagi (m)    | `08 CASIMIRO DREAMS.pdf`                 |
| 9  | Itaibigai (f)    | `09 DEATH OF AOGIOSO #2.pdf`             |
| 10 | Baigibohoasi (f) | `10 IOHABI, THE DOG, AND THE SNAKE.pdf`  |
| 11 | Kaboibagi (m)    | `11 ISAGUE AND THE ONCA.pdf`             |
| 12 | Tisahai (f)      | `12 ITAISOI HUNTS FOR TAPIR.pdf`         |
| 13 | Itaibigai (f)    | `13 MARTINS VISIT.pdf`                   |
| 14 | Itaibigai (f)    | `14 MIGIXISTI DIES.pdf`                  |
| 15 | Tisahai (f)      | `15 OPISI GETS A DOG.pdf`                |
| 16 | Tisahai (f)      | `16 TRIP TO SEE A PLANE.pdf`             |
| 17 | Tisahai (f)      | `17 PORTO VELHO IS BIG.pdf`              |


## Phonemic Transcription

Pirahã phonemes are /i/, /a/, /u/, /p/, /t/, /k/, /h/, /s/, /b/, /g/, and /ʔ/.  In the corpus, /ʔ/ is written `x` and /u/ is written `o`.

Pirahã vowels have phonemic tone, high or low. High tones are marked with a capitalized vowel.  These are based either on a diacritic marking in texts transcribed by Daniel L. Everett or tone 1 or tone 2 marker in texts transcribed by Steve Sheldon.

Low tones are marked with a lower case vowel.  These are based either on a lack of a diacritic marking in texts transcribed by Daniel Everett or a lack of a tone marker or a tone 3 marker in texts transcribed by Steve Sheldon.

Otherwise, the orthography is straightforward.

## Word and Sentence Boundaries

Pirahã words are given broken into morphological units, with exceptions for proper nouns, foreign words and phrases, or words whose morphological details are unknown.  Word boundaries are indicated by units which are not preceded by a dash; dashes indicate a unit is an affix.

It is possible that many of the pronouns or short nouns whose definitions are marked with `_clitic` may not be independent words, yet are labeled as such in this corpus. 

## Basic Organization of the Corpus

Each text in the corpus is preceded by three lines of hashes and information about the source of the text.

The corpus is divided into stories; stories are divided into "utterances"; and utterances are divided into sentences. Utterances correspond to the sentence breaks in Steve Sheldon's original glosses. 

Each utterance is preceded by two English glosses (free translations).  The first is labeled with a hash and a code of two numbers, and reflects the English translation given by Steve Sheldon or Daniel L. Everett in their original translation.  The second is labeled with a hash and a code of three numbers, and reflects the current best translation, as judged by Daniel L. Everett,  Steve Sheldon, and the other authors. Clarifications are provided in square brackets in these glosses. The glosses allow simple text searching to find rough equivalents of English words and phrases (e.g. what does Pirahã use to convey meanings glossed as "and"?). 

## Numbering Scheme

Each Pirahã sentence is labeled with a unique code of three numbers, appearing on the preceding line along with its current best English translation.  The first number indicates the text in which the utterance appears.  The second number indicates the utterance's sequential placement within the text.  This second number reflects the utterance boundaries present in the original transcriptions (e.g. by Dan Everett and Steve Sheldon).  In many cases, text which was originally translated into a single utterance actually includes a group of Pirahã sentences according to our current best translations.  When this occurs, the third number indicates the order of the Pirahã sentences within this grouping.  Otherwise, the third number is simply 1.  

## Part-of-Speech Tags

Each morphological unit is in an *A/B/C* triple, where *A* is a Pirahã word, *B* is an English translation, and *C* is a part of speech tag.  For instance *kagi/basket/NN* means that the Pirahã word *kagi* is best translated into "basket", a noun (`NN`). In the English translations, the numerals 1, 2, 3 indicate first, second, and third person pronouns respectively, and underscores are used where single English words do not suffice. In cases where morphemes are judged to be affixes, only the root is labeled with a tag. 

Part-of-speech tags are assigned based on the judgment of the authors and are based on those used in the Penn Treebank. Listed below are the tags used in the Pirahã corpus, along with examples:

| Tag   | Description      | Examples (**Pirahã**/English definition) |
| ----- | ---------------- | ---------------------------------------- |
| `NN`  | Noun             | **kagi**/expected_associate  **ao**/foreigner **s**/animal_clitic **xahoa**/day **hoaI**/fire **aho**/leg **baOsai**/cloth **kopaIyai**/panther **kaxAowI**/basket |
| `NNP` | Proper noun      | **KatO**/Kato **TixohOI**/TixohOI **hoagaixoOxai**/HoagaixoOxai **isaitaOgi**/Steve **pasabIi**/Passar_Bem **XaogiosohoagI**/Xaogioso
| `PRP` | Personal pronoun | **ti**/1 **gIxa**/2 **hi**/3 **xi**/3_feminine |
| `VB`  | Verb             | **igA**/speak **xai**/do **a**/move **ait**/sleep **Op**/give_birth **apipaO**/dream |
| `JJ`  | Adjective        | **bio**/weak **AbahIo**/useless **ogI**/big **sigi**/same **itA**/hurt **bAt**/used_up |
| `JJR` | Comparative adjective | **pixAagihI**/younger |
| `IN`  | Postposition     | **higIo**/comitative **kA**/from **xiigihi**/near **xIosi**/inside |
| `RB`  | Adverb           | **aigIa**/thus **xaI**/thus **pIai**/also **gAi**/here **kaxaO**/away **IbIg**/very |
| `RP`  | Particle         | **go**/focus |
| `DT`  | Determiner       | **kapiOxiai**/another **aihi**/that_one **aIbA**/many **oogiO**/much **oOxiai**/other |
| `CD`  | Cardinal numeral | **hOi**/one_or_few |
| `WP`  | Wh-pronoun       | **aOi**/who_or_what |
| `UH`  | Interjection     | **xigIa**/okay **hai**/hmm **ko**/hey **a**/false_start |
| `FW`  | Foreign word     | **so**/only **agora**/now **quase**/almost **saiu_ai_morar**/went_to_live_there |

The tagging should be considered descriptive yet tentative. In particular, some of the part-of-speech tags used may not reflect true syntactic categories in Pirahã.  For example, several tags used appear with only one lexical item: the only comparative adjective which appears is *pixAagihI*, translated as "younger", the only cardinal numeral which appears is *hOi*, meaning "few", and the only wh-prounon is *aOi*, meaning "who" or "what".  It is possible that *hOi* may be better analyzed as a determiner and *aOi* as a noun.

## Syntactic Tags

We provide a simple shallowing parsing of the corpus in order to characterize the syntactic structure of Pirahã in a broad and theory-neutral way. This parsing was completed based on the judgment of the authors. The formatting used is `tgrep2` compatible.

| Tag        | Description |
| ---------- | ----------- |
| `Q`        | Quote       |
| `S`        | Sentence    |
| `NPsubj`   | Noun phrase, subject |
| `NPobj`    | Noun phrase, object  |
| `NPiobj`   | Noun phrase, indirect object |
| `NPloc`    | Noun phrase, locative |
| `NPvoc`    | Noun phrase, vocative |
| `NPtmp`    | Noun phrase, temporal |
| `NPtopic`* | Noun phrase, topical |
| `JJobj`    | Adjective phrase, complement |
| `V`        | Verb |
| `POS`      | Possessive phrase |
| `PP`       | Postpositional phrase |
| `PAREN`    | Parenthetical |
| `FRAG`     | Fragment |
| `*`        | Omission [see below] |

* `NPtopic` may include following modifiers to indicate what role the noun appears to play in the context of the sentence: `-subj` `-obj` `-iobj` `-loc` `-tmp`

Omissions: An asterisk is used to indicate the omission of something which seems called for by the grammar.  That is, it appears in the following cases:

1. No subject appears before the verb
2. No verb appears before the verbal affixes, or no verb appears in the sentence
3. No object appears after a possessor
4. No object appears before a postposition, such as a comitative marker


