# clipboard2bib

Small bash utility to update clipboard from text containing DOI, arXiv ID or PubMed ID into a BibTex citation.

A desktop notification is sent to the user as soon as the process finishes. Supports Linux and MacOS only.

## Requirements

* [doi2bib](https://github.com/mseri/doi2bib)

## Usage

Simply call the script - no arguments are expected:

```bash
clipboard2doi
```

Assign a keyboard shortcut to it in order to have it available system-wide (e.g., with **Automator** on MacOS).

**Note:** On Wayland desktop environments, make sure to also have [wl-clipboard](https://github.com/bugaevc/wl-clipboard) installed to use with a keybind.

___

:heart: Thanks go to **[@mseri](https://github.com/mseri)** for maintaining [doi2bib](https://github.com/mseri/doi2bib) and to **[@davidagraf](https://github.com/davidagraf)** for maintaing [doi2bib2](https://github.com/davidagraf/doi2bib2) (see [website](https://www.doi2bib.org/)).
