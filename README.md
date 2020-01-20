Lakota XKB Layout

This is like the standard QWERTY layout except:

* the numbers 4-8 are replaced with `áéíóú` (vowels with acute accents)
* the letter `q` is replaced with `ǧ` (g with caron)
* the letter `r` is replaced with `š` (g with caron)
* the letter `f` is replaced with `ŋ` (eng)
* the letter `j` is replaced with `ȟ` (h with caron)
* the apostrophe/quote key is replaced with `’` (glottal stop encoded as right single quotation mark)
* the letter `x` is replaced with `ž` (z with caron)
* the letter `c` is replaced with `č` (c with caron)
* the slash/question mark key is replaced with a combining acute character (IE it will add an acute accent to the preceding letter)
* The right Alt key is replaced with ISO_Group_Latch.  It can be pressed to make the next key ignore these mappings and use a standard QWERTY layout, or held down for multiple letters.

To switch to this layout, `cd` into this directory and run `xkbcomp -I. deseret.xkb $DISPLAY`.  To switch back to a standard qwerty layout, run `setxkbmap -model pc104`.

I personally don't know anything about the Lakota language or writing system, but I made this layout because I saw someone request it.  So I can't really vouch for it's utility for its purpose.
