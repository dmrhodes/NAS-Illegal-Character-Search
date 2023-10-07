# NAS-Illegal-Character-Search
Script To find a set of pre defined characters within folder names in preparation for migration.
Typically I run this from Shell. 
Guide:
1. Save this file as whatever name you choose .py. Example CharSearch.py
2. Navigate to where you have saved the script from within your shell / terminal
3. run python3 CharSearch.py /path_to_check. Example would be: python3 find_illegal_chars.py /Volumes/General/test
4. Output would then prompt you for the characters you are searching for seperated by a comma. Example: "Please enter illegal characters to search for, separated by a comma (,): >,/,\"
5. Output woudl display within the shell as well as within a txt file alongside where you have saved the script.

This for me is a good way to scan external volumes for these offending characters, usualy with a read only account if to a NAS or server. 
