# Crate removal procedure

*status 2019-06-13: this document is incomplete and unvetted. We anticipate to be receiving guidelines from Mozilla Legal in the near future. If this notice is still here on 2019-09-13, please file an issue on this repo to ping for updated status.*

If we get a DMCA takedown notice, here's what needs to happen:

## Remove relevant version(s) and/or entire crates from crates.io

TODO specific instructions

## Remove entire crates from docs.rs

The docs.rs application supports deleting all the documentation ever published
of a crate, by running a CLI command. The people who currently have permissions
to access the server and run it are:

* docs.rs Team:
  * [@QuietMisdreavus](https://github.com/QuietMisdreavus)
  * [@pietroalbini](https://github.com/pietroalbini)
  * [@onur](https://github.com/onur)
  * [@jyn514](https://github.com/jyn514)
* Infrastructure Team:
  * [@Mark-Simulacrum](https://github.com/Mark-Simulacrum)
* People with elevated 1password access

You can find the documentation on how to run the command [here][docsrs-howto].

[docsrs-howto]: https://forge.rust-lang.org/infra/docs/docs-rs.html#removing-a-crate-from-the-website
