% FIND(shell) Um Pages | Um Pages
% 
% August 30, 2018
# NAME
find --

# SYNOPSIS


# DESCRIPTION

# Examples

find . -type f -exec perl -pi -e "s/BOOST_FOREACH\((.*),(.*)\)/for(\1 : \2)/g" {} \;

# OPTIONS

-type
: type of thing to search for; f = file

-exec
: execute the following shell command on each file found

