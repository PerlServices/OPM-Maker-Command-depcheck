[![Kwalitee status](https://cpants.cpanauthors.org/dist/OPM-Maker-Command-depcheck.png)](https://cpants.cpanauthors.org/dist/OPM-Maker-Command-depcheck)
[![GitHub issues](https://img.shields.io/github/issues/perlservices/OPM-Maker-Command-depcheck.svg)](https://github.com/perlservices/OPM-Maker-Command-depcheck/issues)
[![CPAN Cover Status](https://cpancoverbadge.perl-services.de/OPM-Maker-Command-depcheck-1.0.1)](https://cpancoverbadge.perl-services.de/OPM-Maker-Command-depcheck-1.0.1)
[![Cpan license](https://img.shields.io/cpan/l/OPM-Maker-Command-depcheck.svg)](https://metacpan.org/release/OPM-Maker-Command-depcheck)

# NAME

OPM::Maker::Command::depcheck - Check if ticketsystem addon dependencies are installed (works for ((OTRS)) Community Edition, Znuny and OTOBO)

# VERSION

version 1.0.1



# Development

The distribution is contained in a Git repository, so simply clone the
repository

```
$ git clone git://github.com/perlservices/OPM-Maker-Command-depcheck.git
```

and change into the newly-created directory.

```
$ cd OPM-Maker-Command-depcheck
```

The project uses [`Dist::Zilla`](https://metacpan.org/pod/Dist::Zilla) to
build the distribution, hence this will need to be installed before
continuing:

```
$ cpanm Dist::Zilla
```

To install the required prequisite packages, run the following set of
commands:

```
$ dzil authordeps --missing | cpanm
$ dzil listdeps --author --missing | cpanm
```

The distribution can be tested like so:

```
$ dzil test
```

To run the full set of tests (including author and release-process tests),
add the `--author` and `--release` options:

```
$ dzil test --author --release
```

# AUTHOR

Renee Baecker <reneeb@cpan.org>

# COPYRIGHT AND LICENSE

This software is Copyright (c) 2023 by Renee Baecker.

This is free software, licensed under:

```
The Artistic License 2.0 (GPL Compatible)
```
