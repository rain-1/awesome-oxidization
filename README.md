# awesome-oxidization

Components being replaced with rust versions.

You can edit this page to make it better!

## Software

Software that's already been, or in the progress of oxidation.

* Mozilla [Firefox](https://wiki.mozilla.org/Oxidation) Oxidation.
* librsvg - [Announcement](https://mail.gnome.org/archives/desktop-devel-list/2017-January/msg00001.html) and [slides](https://people.gnome.org/~federico/blog/docs/fmq-porting-c-to-rust.pdf) & [librsvg is almost rustified](https://people.gnome.org/~federico/blog/librsvg-is-almost-rustified.html)
* minimp3 blog - https://wiki.alopex.li/PortingCToRust
* rpm-ostree - https://www.reddit.com/r/rust/comments/9exvfv/rpmostree_20188_now_hard_requires_rust/
* A python standard library function - https://tech.blue-yonder.com/oxidizing-python-speeding-up-urlquoting-by-using-rust/
* A linux kernel module - (https://github.com/tsgates/rust.ko)
* A FreeBSD kernel module - https://github.com/johalun/echo
* [fastmod](https://github.com/facebookincubator/fastmod), a rust reimplementation of codemod refactoring tool
* [deno](https://github.com/denoland/deno) - a typescript implementation for running typescript outside the browser.
* [coreutils](https://github.com/uutils/coreutils), cross-platform Rust rewrite of the GNU coreutils
* [swc](https://github.com/swc-project/swc) - a babel (something to do with javascript?) replacement.
* [remacs](https://github.com/Wilfred/remacs) - a rusty version of emacs

### Cryptography Software

The following conglomerate are components working together to replace openssl with rust implementations. Ring contains a little unsafe but the rest is pure rust with no unsafe blocks.

* https://github.com/briansmith/ring
* https://github.com/briansmith/webpki
* https://github.com/ctz/webpki-roots
* https://github.com/ctz/sct.rs
* https://github.com/ctz/rustls/
* [mesalink.io](https://mesalink.io/): https://github.com/mesalock-linux/mesalink


GPG reimplementation:

* https://sequoia-pgp.org/

## Plans

Software where there are plans to do it, but it hasn't been done yet.

* mercurial - [OxidationPlan](https://www.mercurial-scm.org/wiki/OxidationPlan) + [mononoke](https://github.com/facebookexperimental/mononoke) a implementation of mercurial server in rust.
* gstreamer plugins - [writing gstreamer plugins in rust](https://coaxion.net/blog/2016/05/writing-gstreamer-plugins-and-elements-in-rust/)
* network device drivers - [Writing Network Drivers in Rust](https://www.net.in.tum.de/fileadmin/bibtex/publications/theses/2018-ixy-rust.pdf), [How to write PCIe drivers in Rust, go, C#, Swift, Haskell, and OCaml @ CCC](https://www.youtube.com/watch?v=aSuRyLBrXgI)

## Tools

Tools that help automate the process.

* https://github.com/jameysharp/corrode
* https://github.com/immunant/c2rust
* https://gitlab.com/citrus-rs/citrus
