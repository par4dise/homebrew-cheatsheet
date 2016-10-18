# My Homebrew cheat sheet
Terminology and most used commands.

## Glossary
**Formula**   
: A formula is a package definition written in Ruby.    
**Keg**   
: Installation prefix of a formula.    
**Cellar**   
: Place where kegs are located.

## Global
`brew list` - See what's installed locally.   
`brew list --versions` - See what's installed locally + version number.   
`brew info <formula>`- Information on a formula.   
`brew install <formula>` - Install a formula.   
`brew uninstall <formula>` - Remove a formula.

## Update
`brew outdated` - See what's outdated.   
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

## Licence
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)   
![CC BY 4.0 logo](https://i.creativecommons.org/l/by/4.0/88x31.png "CC BY 4.0 logo")

