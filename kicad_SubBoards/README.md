This uses the *SamacSys* footprint for the Alpha switch available via
the Mouser web site and directly from
[Component Search Engine](https://componentsearchengine.com/search?term=SR2612F-0112-21R0B-D8-N)


Using the Library
-----------------

First create a path name for the SamacSys Library:

1. In the main KiCad window, select `Preferences>Configure Paths`

2. Click the `+` sign and add a path called `KICAD_SAMACSYS_LIBS` and pointing to wherever the directory is containing the `SamacSys_Parts.lib` file.

3. Click OK

Next, configure the symbol library:

1. In the main KiCad window, select `Preferences>Manage Symbol Libraries`
2. Click the `+` sign and add a new library:

- `Nickname` = `SamacSys`
- `Library Path` = `${KICAD_SAMACSYS_LIBS}/SamacSys_Parts.kicad_sym`
- `Description` = `SamacSys Symbols`

and click `OK`.

Finally, configure the footprints library:

1. In the main KiCad window, select `Preferences>Manage Footprint Libraries`
2. Click the `+` sign and add a new library:

- `Nickname` = `SamacSys`
- `Library Path` = `${KICAD_SAMACSYS_LIBS}/SamacSys_Parts.pretty`
- `Description` = `SamacSys Footprints`

and click `OK`.

