
<p align="center">
  <img src="http://i.imgur.com/2EReWN2.png">
</p>
<h1 align="center">Niklas' Houdini Library</h1>


<img align="right" src="https://img.shields.io/badge/License-MIT-yellow.svg">
&mdash; A collection of digital assets, shelf tools and code snippets.

## Documentation

The documentation can be found at https://niklasrosenstein.github.io/houdini-library

In the documentation, nodes will be marked with one of the following badges
to indicate the license that the HDA was saved with. Since I'm using a
Houdini Indie license, most of the assets are going to be Indie based.

* ![](https://img.shields.io/badge/Houdini-Apprentice-blue.svg)
* ![](https://img.shields.io/badge/Houdini-Indie-orange.svg)
* ![](https://img.shields.io/badge/Houdini-FX-green.svg)

## Installation

Use the green Download button on the upper right and choose "Download ZIP".
Alternatively, if you're familiar with Git, you can also clone this repository
and pull to get updates.

Once you've placed the library in a directory of your choice, update your
Houdini environment like so (by editing the `houdini.env` file in your user
preferences folder):

```
# Make sure HOUDINI_PATH has its default value. Omit this line if there is
# already one like this, otherwise make sure that it's the first line in
# the file.
HOUDINI_PATH="&"

# Add the library to the HOUDINI_PATH. Replace the path with the absolute
# path to where you placed the library. Use : instead of ; on macOS.
HOUDINI_PATH="$HOUDINI_PATH;C:\Users\niklas\repos\houdini-library"
```
