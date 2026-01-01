aoo-mozilla-en-dict
===================

![Project Logo](assets/logo_2025+.png)

**IN JANUARY 2026, MARCO BEGAN MAINTAINING ALTERNATIVE VERSIONS OF THE U.S., CANADIAN, AND AUSTRALIAN DICTIONARIES.**  
**THE en_US, en_CA, AND en_AU DICTIONARIES PROVIDED HERE ARE ALTERNATIVES TO THE CORRESPONDING UPSTREAM DICTIONARIES.**  
**The U.S., Canadian, and Australian dictionaries MAY differ slightly in coverage for some region-specific terms.**

**IN MARCH 2025, THE DEFAULT BRITISH AND SOUTH AFRICAN DICTIONARIES BECAME -ISE.**  
**For specific -ise/-ize variants, some verbs and words MAY be missing or included differently.**


**PLEASE READ THE FOLLOWING BEFORE DOWNLOADING**  
**LIBREOFFICE EXTENSION V2026.01.01+:**  
https://bugs.documentfoundation.org/show_bug.cgi?id=167649#c19  
**This extension is maintained independently and is not part of LibreOffice core.**

---

## Introduction and Scope

For many years, active maintenance of dictionaries for open-source software has been neglected. Continuing this important work involves improving existing dictionaries and creating new ones where necessary.

A significant challenge is that most dictionaries are obfuscated — encoded in formats accessible only by specific software — with the original developers no longer available to provide plaintext versions. Consequently, we sometimes must revert to the last available clean-text versions to resume development.

Maintaining, updating, and enhancing dictionaries is a complex yet vital task, ensuring ongoing accuracy and usefulness for present and future users.

This repository contains the latest available versions of dictionaries, facilitating easy use by developers for proofing or spellchecking applications (`.AFF` and `.DIC` file formats).

I, **Marco Pinto**, actively maintain all five primary variants of English dictionaries:

- **British English** (`en_GB`)
- **South African English** (`en_ZA`)
- **American English** (`en_US`) (alt) *(it took me one year of careful preparation before the initial U.S. release — it was quite a challenging task.)*
- **Canadian English** (`en_CA`) (alt)
- **Australian English** (`en_AU`) (alt)

Kevin Atkinson maintains independent versions of `en_GB`, `en_US`, `en_CA`, and `en_AU`, which have been valuable points of comparison during the development and evaluation of these dictionaries. For more details, see:

- [Kevin Atkinson's GitHub](https://github.com/en-wl/wordlist)  
- [Kevin Atkinson's Website](http://wordlist.aspell.net)

Dwayne Bailey previously maintained the `en_ZA` dictionary but has since ceased maintenance. His website, associated with the South African government, is no longer operational, and previous contact methods are inactive.

---

## Release Cycle

Regular dictionary updates are released three times per year — on the **first day of January, May, and September**.

Each release enters a feature freeze approximately one week before publication, allowing time to prepare release notes, update websites, and finalise packaging. Maintaining five dictionaries simultaneously requires careful coordination to ensure accuracy and stability.

**Note:**  
Since late 2025, the AOO Extensions website has been read-only, so updates and downloads can no longer be provided there. For this reason, only a LibreOffice (LO) extension is now released, which can also be installed and used in Apache OpenOffice (AOO).

The AOO and LO extensions contain the same wordlist; they previously differed only in naming and update URLs. With the AOO site read-only, the LO extension is now the only maintained version for both LO and AOO. For more details, see [this LibreOffice bug report](https://bugs.documentfoundation.org/show_bug.cgi?id=148250).

A changelog for dictionary updates is available in `2025+_Release_notes.txt`.

Recent updates for Mozilla, BlueGriffon, and LO are documented on the [Proofing Tool GUI website](https://proofingtoolgui.org).

---

## Repository Folder Structure

Each dictionary folder on GitHub includes:

- `.AFF` file (Hunspell affix rules)
- `.DIC` file (dictionary entries)
- `README` file (`.txt` format)
- `WORDLIST` file (`.txt` format)
- Compressed (zipped) folder files

---

## Licence

All dictionaries maintained by Marco Pinto are licensed under the [LGPL (Lesser General Public Licence)](https://www.gnu.org/licenses/lgpl-3.0.en.html).

---

## Suggesting Words and Corrections

Please verify the wordlist (`.txt` file) within the latest dictionary release before submitting suggestions.

If a word is absent or incorrect, you may either:

- [Open an issue on GitHub](https://github.com/marcoagpinto/aoo-mozilla-en-dict)  
- E-mail Marco Pinto directly: `marcoagpinto @ sapo.pt`

User feedback is critical for continually enhancing dictionary accuracy. Report incorrectly categorised words (e.g., U.S. English appearing in `en_GB`) with reputable dictionary references. Corrections, missing words, and general suggestions should include supportive documentation for easier evaluation and inclusion.

Please pay special attention to words ending with “**ise**” and “**ize**”, as conversions sometimes lead to inadvertent omissions. Feedback helps reinstate valid entries as exceptions.

To check words that may have been incorrectly removed in specific “**-ise**” / “**-ize**” variants, consult the full wordlists of both forms in the respective **ise+ize** folder above in this GitHub repository. This ensures you are reviewing the complete set of entries for both variants.

Significant enhancements to the `.AFF` file have been made, particularly addressing issues with U.S. English verb derivations ending in “**r**” (e.g., “**color**” → “**colored**”, previously incorrectly listed as “**colorred**”). While extensive efforts have been made to correct these, please report any remaining errors.

---

## Plans for 2027 and Beyond

> **Update (completed ahead of schedule):**  
> Two key goals planned for 2027 were successfully completed earlier:..
> - ✅ Merged the GB dictionary into the ZA dictionary  
> - ✅ Aligned all five dictionaries to the GB versioning format for consistency  

These items are therefore already in place prior to the V5 transition timeline.  


Starting in 2027, all dictionaries will move to the **fifth generation (V5)** — a major upgrade designed to make them faster, cleaner, and easier to maintain.  

### Key Changes in V5
1. **No more PFX flags**  
   - Prefix (**PFX**) flags will be removed from `.DIC` files.  
   - This simplifies file structure, reduces complexity, and speeds up decoding.

2. ~~**One version number for all**~~ ✅ *(completed early)*  
   - All dictionary locales will share the same versioning system.  
   - Makes it easier for developers and users to track updates across different English variants.

3. **Smaller, more efficient dictionaries**  
   - Merging and reorganising word flags will cut down on duplicates.  
   - This reduces file size and improves consistency.

4. ~~**Merging en_GB into en_ZA**~~ ✅ *(completed early)*  
   - The British English (`en_GB`) wordlist will be merged into the South African English (`en_ZA`) dictionary.  
   - This will create a larger and more complete South African dictionary, benefiting both locales.

### Why This Matters
These improvements will:
- Make the dictionaries easier to maintain for years to come.  
- Reduce the chance of errors during updates.  
- Improve performance for software using these dictionaries.

**Community feedback will be essential** during this transition. Any unexpected issues or missing words should be reported quickly so they can be fixed before the new system becomes the standard.

---

#### ⚠ NOTICE:
<B>I have been publicly criticised for my GB dictionary, even in front of other developers.
They only point out flaws instead of suggesting new words or corrections.

There are millions of words, and I can't manage them all alone.

This project is very serious.
I spend hundreds of EUR yearly on web hosting, domains, and a premium Oxford Dictionaries account so that everyone can enjoy quality work for free.

I am a disabled person and open-source is almost all I have left in life.</B>
