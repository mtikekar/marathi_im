# Input method for Marathi with ibus-m17n

A simpler [ibus-m17n](https://launchpad.net/ubuntu/+source/ibus-m17n) input method for Marathi. It is based on mr-itrans.mim with modifictions inspired by the [Harvard-Kyoto convention](http://en.wikipedia.org/wiki/Harvard-Kyoto). It is also suitable for Sanskrit and Hindi (see examples below).

## Installation

On KDE + Arch-based distro:

```bash
git clone https://github.com/mtikekar/marathi_im
mkdir -p ~/.m17n.d/icons
cp marathi_im/mr-simple.mim ~/.m17n.d
cp marathi_im/icons/mr-simple.png ~/.m17n.d/icons/
sudo pacman -S fcitx5-configtool fcitx5-m17n
```

In KDE System Settings, search for "Virtual Keyboard" and select "Fcitx 5". Then,
search for "Input Method" in System Settings and click on "Add Input Method" and
find "simple (M17n)" under "Marathi". Between these two steps, you may need to
restart KDE by logging out and logging back in.

On Gnome and others, IBus can be used instead of Fcitx5 with the `ibus-m17n` package.
The `~/.m17n.d` folder should work with IBus too.

## Examples

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
