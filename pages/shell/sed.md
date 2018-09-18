% SED(shell) Um Pages | Um Pages
% 
% August 30, 2018
# NAME
sed -- stream editor (that I use for find/replace)

# SYNOPSIS

used to regex find/replace stuff (usually)
the OSX version adds newlines to the end of files

# DESCRIPTION
sed -E -i "" "s/BOOST_FOREACH\((.*),(.*)\)/for(\1 : \2)/g" filename,extension

# OPTIONS

-E
: extended regex

-i
: edit in place; takes an extension for backu- files

