# HomeCtrl

AutoHotkey script to remap CapsLock to Ctrl, when pressed together with another key. When pressed alone (actually, the criterium is a fast release), CapsLock acts like Escape.

(Yes, the useless CapsLock function is entirely disabled)

On Windows, this is most useful for Emacs users, but maybe there are other use cases.

Please notice that I'm still learning AutoHotkey. The basic code come from [this discussion](https://superuser.com/questions/223831/remap-a-key-depending-on-whether-it-was-pressed-alone-or-not), and this general idea come from [these](http://stevelosh.com/blog/2012/10/a-modern-space-cadet/) [three](http://brettterpstra.com/2012/12/08/a-useful-caps-lock-key/) [posts](http://batsov.com/articles/2012/12/06/emacs-tip-number-7-remap-return-to-control-in-osx/).

An earlier version of this script also tried to modify the behaviour of the `Enter` key, making it like `Enter` when pressed fast and `Ctrl` when pressed with another key, but I got a weird behaviour on Windows, so I decided to eliminate this feature.
