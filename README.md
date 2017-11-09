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
    <td>3D model including mesh, materials, textures, nodes, bones, SFX, animations.</td>
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
    <td>Contains data about different .bdae models placed on a terrain chunk. Implicitly bound with .trn by file name.</td>
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

TODO
