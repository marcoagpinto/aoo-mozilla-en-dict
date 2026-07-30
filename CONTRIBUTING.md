# Contributing

Contributions, corrections, and feedback are welcome and help keep the dictionaries accurate, comprehensive, and up to date.

---

## Suggesting Words and Corrections

Please verify the wordlist (`.txt` file) within the latest dictionary release before submitting suggestions.

If a word is absent or incorrect, you may either:

* [Open an issue on GitHub](https://github.com/marcoagpinto/aoo-mozilla-en-dict)
* E-mail Marco Pinto directly: `marcoagpinto @ sapo.pt`

User feedback is critical for continually enhancing dictionary accuracy. Report incorrectly categorised words, such as U.S. English words appearing in `en_GB`, with reputable dictionary references.

Corrections, missing words, and general suggestions should include supporting documentation to make their evaluation and possible inclusion easier.

Please pay special attention to words ending in **-ise** and **-ize**, as conversions may occasionally lead to inadvertent omissions. Feedback helps valid entries to be restored as exceptions.

To check words that may have been incorrectly removed from specific **-ise** or **-ize** variants, consult the complete wordlists for both forms in the respective **ise+ize** folder in this GitHub repository. This ensures that the complete set of entries for both variants is reviewed.

Significant improvements have been made to the `.AFF` file, particularly to address problems with U.S. English verb forms ending in **r**, such as:

```text
color → colored
```

Previously, some forms could be generated incorrectly, such as:

```text
colorred
```

Although extensive efforts have been made to correct these problems, please report any remaining errors.

---

## Inclusion Rules

Words should normally meet the following criteria before being added:

* Words must appear in at least two authoritative sources, such as Oxford and Collins.
* Proper nouns are exempt from the requirement to appear in two dictionary sources, but sufficient evidence of their spelling and established use should still be provided.
* Archaic terms may be included when they do not conflict with modern words or contemporary usage.
* U.S. spellings and vocabulary may be retained in the British dictionary when they have been widely adopted in British English, such as **movie**, and are validated by trusted sources.

The dictionaries originated partly from U.S.-based wordlists. This historical origin explains why some U.S. words may still be present in dictionaries for other English varieties.

When reporting a word that appears to belong to the wrong regional dictionary, please provide reliable evidence supporting its removal, retention, or reassignment.

Suitable sources include:

* Oxford dictionaries;
* Collins Dictionary;
* Cambridge Dictionary;
* Merriam-Webster;
* recognised regional dictionaries;
* reputable corpora;
* official institutional sources;
* printed dictionaries and other established reference works.

Wiktionary and Wikipedia may be useful for preliminary research, but they should be used with caution and, whenever possible, supported by a more authoritative source.

---

## Contributors

Many people have provided valuable feedback, word submissions, corrections, and practical suggestions over the years — too many to list individually.

Special thanks are due to:

* **Cyberknight** — Submitted numerous scientific terms during the project's early years and helped create a legacy British dictionary extension for older versions of Mozilla applications. Although Marco is no longer in contact with him, his contributions remain a valued part of the project's history.

* **Babelfish (Peter C.)** — Regularly contributed words and provided practical suggestions that helped refine, correct, and expand the dictionary.

* **Peter C. (not Babelfish)** — Consistently advocated for a British dictionary using **-ise** spelling. His feedback contributed to the adoption and expansion of **-ise** forms in the default British dictionary.

These wordlists aim to provide broad and reliable coverage of contemporary English across the Commonwealth and North America while preserving appropriate regional spelling and vocabulary.

The original `.AFF` file was created by David Bartlett and Andrew Brown using MySpell rules and was distributed under the LGPL. Its purpose was to provide accurate morphological and affix handling rather than to minimise file size.

Marco has continued to revise and expand the affix rules since 2013.
