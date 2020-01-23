# rrsync - Configurable and restricted rsync

This is a revised copy of a rrsync Perl program (originally authored by Joe Smith and later 
modified by WAyne Davison).

## Configuration options

There are two primary options:
* --read-only - only allow read-only to the directory
* --alias-config - use a coniguration file with the format "ALIAS = DIRECTORY" for each alias

A subdirectory is required unless using an alias file.

## Alias file

An alias file can be used to indicate multiple directories.

