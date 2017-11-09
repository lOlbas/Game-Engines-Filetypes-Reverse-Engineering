# Game Engines Filetypes Reverse Engineering

A work-in-progress repository containing templating and reading scripts along with file examples of different filetypes used within game engines.

##

### Contents:

* [Engines](#engines)
* [Filetypes](#filetypes)
* [Templates code-style](#templates-code-style)

##

### Engines

List of engines (or companies if engine name is unknown) which files are to be explored.

* [Gameloft](#gameloft-engine)
* ...

##

### Filetypes

List of filetypes which are either already known, at parsing stage or planned to get parsed.

Status legend:

* ![#00FF00](https://placehold.it/15/00FF00/?text=+) Known type
* ![#FFBB00](https://placehold.it/15/FFBB00/?text=+) File can be parsed but some fields are unknown
* ![#FFFF00](https://placehold.it/15/FFFF00/?text=+) Parsing in-progress
* ![#FF0000](https://placehold.it/15/FF0000/?text=+) Filetype is planned for future

#### Gameloft Engine

<table>
  <tr>
    <th>Extension</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><img src="https://placehold.it/15/FF0000/?text=+" /> .bar</td>
    <td></td>
  </tr>
  <tr>
  <td><img src="https://placehold.it/15/FFFF00/?text=+" /> <span class="">.bdae</span></td>
  <td>3D model including mesh, materials, textures, nodes, bones, SFX, animations.<br><i>Different games or game versions can use different file version.</i></td>
  </tr>
  <tr>
    <td><img src="https://placehold.it/15/FF0000/?text=+" /> .beff</td>
    <td>Visual effects that can be attached to .bdae nodes.</td>
  </tr>
  <tr>
    <td><img src="https://placehold.it/15/FF0000/?text=+" /> .bin</td>
    <td></td>
  </tr>
  <tr>
    <td><img src="https://placehold.it/15/FF0000/?text=+" /> .dat</td>
    <td></td>
  </tr>
  <tr>
    <td><img src="https://placehold.it/15/FF0000/?text=+" /> .ikp</td>
    <td></td>
  </tr>
  <tr>
    <td><img src="https://placehold.it/15/FFBB00/?text=+" /> .itm</td>
    <td>Contains data about different .bdae models placed on a terrain chunk. Implicitly bound with .trn by game world position.</td>
  </tr>
  <tr>
    <td><img src="https://placehold.it/15/FF0000/?text=+" /> .msk</td>
    <td></td>
  </tr>
  <tr>
    <td><img src="https://placehold.it/15/FF0000/?text=+" /> .phy</td>
    <td></td>
  </tr>
  <tr>
    <td><img src="https://placehold.it/15/FF0000/?text=+" /> .riff</td>
    <td></td>
  </tr>
  <tr>
    <td><img src="https://placehold.it/15/FF0000/?text=+" /> .shw</td>
    <td></td>
  </tr>
  <tr>
    <td><img src="https://placehold.it/15/FFFF00/?text=+" /> .trn</td>
    <td>Represents a terrain chunk of 64x64 size. Known info: heightmaps.</td>
  </tr>
  <tr>
    <td><img src="https://placehold.it/15/FF0000/?text=+" /> .wld</td>
    <td></td>
  </tr>
  <tr>
    <td>...</td>
    <td>...</td>
  </tr>
</table>

##

### Templates code-style

Extension templates are written using [010 Editor](https://www.sweetscape.com/010editor/). While using it, a good way is to visualize parsed parts of a file even if particular byte sequence meaning is unknown  to you. Color scheme used by me (and proposed for usage by any contributor) is similar to status legend at [Filetypes](#filetypes) section:

- known meaning of byte sequence
- byte sequence usage is known but meaning is not (for example, 4-byte value can be an offset to unknown region)
- byte sequence contains a constant value across multiple file examples
- unknown meaning of byte sequence
