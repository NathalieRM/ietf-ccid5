# ietf-ccid5
IETF draft with the profile for Congestion Control Identifier 5 (CCID 5)

This is work in progress and uses "xml2rfc" v3 vocabulary. Travis has been configured to verify:

- the spelling (see the .cspell.json file if you need to add specific words to be considered correct)
- the build of the Internet drafts

Please ensure that the CI tests continue to succeed everytime you submit a pull request.

`make` is used to automate the build process and supports:

* `make` or `make default`
creates XML and TXT files
* `make xml`
creates XML file and prepped XML file for submission
* `make text`
creates TXT and XML files
* `make html`
creates HTML and XML files
* `make all`
creates XML, TXT and HTML files
* `make spell`
check spelling and returns list of unknown/incorrect words with line numbers
* `make spell_list`
generates according to `make spell` a well shaped list ready to be copied to the .cspell.json "words" list
* `make clean`
delete all generated files and remain with the Markdown file solely
* **`make full`** (used for travis)
check spelling and creates XML, TXT and HTML files

A minimal requirement list of packets to be installed based on Ubuntu "Focal Fossa" can be found in .travis.yml
