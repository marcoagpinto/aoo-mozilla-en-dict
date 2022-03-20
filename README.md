## aoo-mozilla-en-dict

### English Dictionaries Project

For many years, maintainance of dictionaries for open source software has lapsed.

It will be great to continue people's work – improve existing dictionaries or create new ones.

The greatest issues are: 

* most of these dictionaries are obfuscated – coded for only certain software to access the wordlists
* decoded (clear text) versions are difficult to obtain, because original developers are long gone.

In some cases, we will have to start with a long ago, last known clear text version.

Maintaining a dictionary can be difficult, but it's important for current and future generations.

Dictionaries here are the most recent versions. This repository makes it easier for developers to find all in one place and take the `.AFF` and `.DIC` files to use them in projects with proofing — or spellchecking — functionalities.

I (Marco Pinto) only maintain `en_GB`. Kevin Atkinson maintains `en_AU`, `en_US` and `en_CA` – please contact him directly for these: <https://github.com/en-wl/wordlist>, <http://wordlist.aspell.net/> and <https://sourceforge.net/projects/wordlist/files/Hunspell>. Dwayne Bailey maintains `en_ZA`: <http://translate.org.za/>.

I try to release updates monthly for Mozilla, every two months for LibreOffice (LO) and Apache OpenOffice (AOO). When a new version of AOO is to be released, there is no dictionary update for it to avoid notifying people to update after installing the latest AOO. Thus, a release is skipped for AOO.

<B>`en_GB_speller_for_Mozilla+AOO+LO_2013+.txt`</B> above provides a changelog.

The Proofing Tool™ GUI (PTG) site <https://proofingtoolgui.org> includes: 

* notes of the most recent releases for Mozilla Firefox and Thunderbird, SeaMonkey, LO, AOO and BlueGriffon
* a list of projects that use `en_GB`/PTG.

Each GitHub folder includes:

* `.AFF` + `.DIC` + `README` + `WORDLIST`.  
  
#### WORDLIST licences

* `en_AU` (Kevin Atkinson) — BSD/MIT-Like;
* `en_CA` (Kevin Atkinson) — BSD/MIT-Like;
* `en_GB` (Marco A.G.Pinto) — LGPL;
* `en_US` (Kevin Atkinson) — BSD/MIT-Like;
* `en_ZA` (Dwayne Bailey) — LGPL.   

#### Suggesting words

First, check the `wordlist⋯.txt` file at <https://github.com/marcoagpinto/aoo-mozilla-en-dict/tree/master/en_GB%20(Marco%20Pinto)>. If the word is not there, then check <B>`en_GB_speller_for_Mozilla+AOO+LO_2013+.txt`</B> above. 

If <B>not</B> found, then:

* open an issue or e-mail Marco Pinto <B>`<marcoagpinto AT sapo.pt>`</B> with the suggested words.

#### Projects that use `en_GB`/PTG

If you know of use by any project that is not [already listed](https://proofingtoolgui.org/where.html), please let me know.
