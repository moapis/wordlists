# wordlists
A collection of wordlists, usefull for testdata generation. It aims to complement our [testdata](https://github.com/moapis/testdata) tool, but is kept in a separate repository for copyright demarcation and keeping it separate from code development.

On Debian, the lists are generated using hunspell's `unmunch` command:

````
unmunch /usr/share/hunspell/en_US.dic /usr/share/hunspell/en_US.aff > en_US.txt
````

The actual location of dictionaries might be different on other distributions.

## Copyright

Hunspell dictionaries are [hosted](https://cgit.freedesktop.org/libreoffice/dictionaries/tree/) / developed as part of the LibreOffice project under a range of [licenses](https://www.libreoffice.org/about-us/licenses). This repository is probably a "derived" work and is therefore licensed under the most restrictive of them: GNU/GPLv2.

Refer to below links for upstream copyright holders:

- en_US: https://cgit.freedesktop.org/libreoffice/dictionaries/tree/en/README_en_US.txt
- ro_RO: https://cgit.freedesktop.org/libreoffice/dictionaries/tree/ro/README_EN.txt
