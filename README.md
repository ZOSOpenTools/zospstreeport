[![Automatic version updates](https://github.com/ZOSOpenTools/zospstreeport/actions/workflows/bump.yml/badge.svg)](https://github.com/ZOSOpenTools/zospstreeport/actions/workflows/bump.yml)

zos-pstree

List visible processes in tree form

`pstree`                               
default

`pstree -A`                            
using ASCII box drawing characters

`pstree | cut -b -$(tput cols)`        
truncate to terminal width (no wrapping)
