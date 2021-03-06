## NLM / JATS to CrossRef Deposit XML XSLT

## What is this?

This repository contains an XSLT file that will translate [NISO NLM or JATS](http://jats.nlm.nih.gov/versions.html)
to [CrossRef Deposit XML](http://help.crossref.org/deposit_schema).

## How do I use this?

Either use CrossRef's [Web Deposit Form](http://www.crossref.org/webDeposit/) to deposit NISO NLM or JATS manually
or build the XSLT into a CrossRef deposit process using JAXP or your favourite language's XML and XSLT processing library.

A commandline XSLT processor can be used for diagnositc and experimental purposes:

- http://xml.apache.org/xalan-j/commandline.html
- http://xmlsoft.org/XSLT/xsltproc.html

## Supported NLM / JATS Versions

Currently the following NLM and JATS [versions](http://jats.nlm.nih.gov/versions.html) are supported:

| Version  | Notes   |
|----------|---------|
| [NLM 2.3](http://dtd.nlm.nih.gov/2.3/) |         |
| [NLM 3.0](http://dtd.nlm.nih.gov/3.0/) |         |
| [JATS 1.0](http://jats.nlm.nih.gov/1.0/) |         |


## Translated Features

###  Bibliographic

###  Funding

###  Identifiers

## Contributing

CrossRef welcomes contributions to enhance this XSLT. Please make a pull request to contribute.
