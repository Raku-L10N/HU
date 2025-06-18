[![Actions Status](https://github.com/Raku-L10N/HU/actions/workflows/linux.yml/badge.svg)](https://github.com/Raku-L10N/HU/actions) [![Actions Status](https://github.com/Raku-L10N/HU/actions/workflows/macos.yml/badge.svg)](https://github.com/Raku-L10N/HU/actions) [![Actions Status](https://github.com/Raku-L10N/HU/actions/workflows/windows.yml/badge.svg)](https://github.com/Raku-L10N/HU/actions)

NAME
====

L10N::HU - Hungarian localization of Raku

SYNOPSIS
========

    $ hunku -e 'mond "Helló Világ"'
    Helló Világ

```raku
use L10N::HU;
mond "Helló Világ";
```

DESCRIPTION
===========

The `L10N::HU` distribution contains the logic to provide a Hungarian localization of the Raku Programming Language. It installs a `hunku` executable that will automatically activate the Hungarian localization. And it allows one to use the Hungarian localization in selected programs with a `use L10N::HU` statement.

AUTHORS
=======

Polgár Márton (Martin Burger)

COPYRIGHT AND LICENSE
=====================

Copyright 2023, 2025 Raku Localization Team

This library is free software; you can redistribute it and/or modify it under the Artistic License 2.0.

