# getopts-long-rs

This is the README.md file for the `'getopts-long-rs'` project.

## Overview

The 'getopts-long-rs' project is intended to provides a [Rust][rust-lang-org]
library for parsing command line options, with a feature set inspired by
[Perl][perl-org]'s [Getopt::Long][m-cpan-golong].

Currently the project is just a stub, established to hold the
['getopts-long' namespace][crates-io-golong] on [crates.io][crates-io].


----

## License

Dual licensed: GPL-2.0-or-later OR Apache-2.0

Copyright © 2020 Alan D. Salewski <ads@salewski.email>


----

## Other Rust options parsing libraries

This is not an endorsement, but if you are interested in `getopts-long-rs`,
you may be interested in one or more of the following, as well. The following
are some other libraries in the "cli options parsing" space that the
`getopts-long-rs` author is aware of. Despite some naming similarities, the
`getopts-long-rs` project is not not affiliated with these other projects:

   * `getopt`
      * https://crates.io/crates/getopt
      * https://docs.rs/getopt/latest/getopt/
      * https://github.com/dragonmaus/getopt.rs
   * `getopts`
      * https://crates.io/crates/getopts
      * https://docs.rs/getopts/latest/getopts/
      * https://github.com/rust-lang/getopts

     This one is used by `rustc`, but usage of it in new projects is
     disouraged:
      * https://github.com/rust-lang/getopts/pull/99#issuecomment-660630614
   * `pico-args`
      * https://crates.io/crates/pico-args
      * https://docs.rs/pico-args/latest/pico_args/
      * https://github.com/RazrFalcon/pico-args
   * `argh`
      * https://crates.io/crates/argh
      * https://docs.rs/argh/latest/argh/
      * https://github.com/google/argh
   * `clap`
      * https://crates.io/crates/clap
      * https://docs.rs/clap/latest/clap/
      * https://github.com/clap-rs/clap
   * `gumdrop`
      * https://crates.io/crates/gumdrop`
      * https://docs.rs/gumdrop/latest/gumdrop/
      * https://github.com/murarth/gumdrop
   * `structopt`
      * https://crates.io/crates/structopt
      * https://docs.rs/structopt/latest/structopt/
      * https://github.com/TeXitoi/structopt
   * `getopt-long`
      * https://crates.io/crates/getopt-long
      * https://docs.rs/getopt-long/latest/getopt_long/
      * https://github.com/automanyang/servant


[BUGS]:         https://github.com/salewski/getopts-long-rs/blob/master/BUGS
[COPYING]:      https://github.com/salewski/getopts-long-rs/blob/master/COPYING
[HACKING]:      https://github.com/salewski/getopts-long-rs/blob/master/HACKING
[INSTALL]:      https://github.com/salewski/getopts-long-rs/blob/master/INSTALL
[NEWS]:         https://github.com/salewski/getopts-long-rs/blob/master/NEWS

[m-cpan-golong]: https://metacpan.org/pod/Getopt::Long  "Getopt::Long  (metacpan.org)"
[perl-org]:      https://www.perl.org/                  "site: www.perl.org"

[crates-io]:        https://crates.io/                     "site: crates.io"
[crates-io-golong]: https://crates.io/crates/getopts-long  "getopts-long  (crates.io)"
[rust-lang-org]:    https://www.rust-lang.org/             "site: www.rust-lang.org"
