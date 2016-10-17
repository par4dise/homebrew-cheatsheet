# Homebrew cheat sheet
Terminology and most used commands.

[TOC]

## Glossary
Formula
: A formula is a package definition written in Ruby. 
Keg
:
Cellar
: Place where kegs are located.

## Global

`brew outdated` - See what's outdated

`brew list` - See what's installed locally.
`brew list --versions` - See what's installed locally + version number.
`brew install <formula>` - Install a formula.
`brew uninstall <formula>` - Remove a formula.

## <i class="icon-refresh"></i> Update

`brew update` - Update Homebrew itself.
`brew upgrade` - Upgrade everything.
`brew upgrade <formula>` - Upgrade a specific formula.

## Clean old versions

`brew cleanup -n` - See what's going to be cleaned.
`brew cleanup` - Clean everything.
`brew cleanup <formula>` - Clean a specific formula.

## Useful information
Path of Homebrew binaries: `/usr/local/Homebrew`
Path of installed formulae: `/usr/local/Cellar`

## See also
- [Homebrew homepage](http://brew.sh)
