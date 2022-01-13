# Input method for Marathi with ibus-m17n

A simpler [ibus-m17n](https://launchpad.net/ubuntu/+source/ibus-m17n) input method for Marathi. It is based on mr-itrans.mim with modifictions inspired by the [Harvard-Kyoto convention](http://en.wikipedia.org/wiki/Harvard-Kyoto). It is also suitable for Sanskrit and Hindi (see examples below).

Installation -
  ```bash
  sudo apt-get install ibus-m17n
  git clone https://github.com/mtikekar/marathi_im
  sudo cp marathi_im/mr-simple.mim /usr/share/m17n/
  ```

Usage - Choose "Marathi - simple (m17n)" as the ibus input method. 

Read the `consonant`, `independent` and `dependent` sections in `mr-simple.mim` to see what is available. Some examples are given below as a quick reference.

Expected output | Key presses
----------------|-------------
बाळ                        | `baaLa, bAla`
पक्षी                        | `paxii, paxI`
तऱ्हा                        | `tar.haa`
वाऱ्यावर                     | `vaar.yaavara`
अनिवार्य                    | `anivaarya`
टॉम                         | `TOma`
प्लॅन                        | `plEna`
ज्ञान                         | `jJaana`
अर्हति                       | `arhati`
अङ्ग                         | `aGga`
पञ्च                         | `paJca`
पाण्डवं                      | `paaNDavaM`
कृष्णः                        | `kRSNaH`
मातॄणाम्                    | `maatRRNaam`
कॢप्ति                        | `kLRpti`
शिव                        | `shiva`
॥ श्री ॥                    | `\|\| shrii \|\|`
ॐ                          | `AUM, OM`
सोऽहम्                     | `so$ham`
ड़र                          | `D.ara`
चाँद                        | `caaCda`
