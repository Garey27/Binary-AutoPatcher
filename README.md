# Binary-AutoPatcher

This litle program search pattern in binary file and replace it according to JSON file.

Possible JSON Fields:
"pattern" - key field - tells program that we have pattern to find
    "name" - pattern name
    "search" - pattern to search in hex-format BEEF011001.. etc
    "wildcard" - skips selected byte in search pattern
    "max_search" - max bytes to compare
    "replace" - replace pattern at found position 
    "replace_wildcard" - wildcard for replacing
    "replace_offset" - possible custom offset, of iterator where to start replace
    
"pattern" field can used recursively, examples in test folder.
